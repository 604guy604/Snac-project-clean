# Snac-project-clean
the latest updates to the snac project animal behavioral inference engine
SNAC — Wildlife Behavioral Inference
SNAC is a fully offline wildlife behavioral inference app for hunters, field trackers, SAR teams, and naturalists. Built for zero cell signal environments.
What SNAC Does
Most wildlife apps tell you what animal made a track. SNAC tells you what that animal is doing right now and where it's going next.
Point your camera at a track. SNAC identifies the species, estimates freshness from physical sign, reads the terrain and weather conditions, and outputs a field-grade behavioral inference:

Phase — is the animal feeding, traveling, or bedded
Location prediction — where is it now relative to this sign
Approach guidance — wind, thermals, terrain-specific
Predator alerts — when predator sign is present, prey behavior changes completely
Session synthesis — multiple tracks analyzed together to identify individuals and predict current position

How It Works
SNAC runs a custom JS inference engine built from 13,000+ species profile data points across 117 species. The vision pipeline detects tracks and identifies species. The inference engine reads the result alongside time of day, freshness of sign, moon phase, barometric pressure, wind, terrain, and hunting pressure to produce a single actionable field output.
The vision layer is a servant to the inference engine — never the decider.
Everything runs on-device. No internet required.
Species Coverage
117 species across North America, Europe, Africa, South America, and Australasia. Full behavioral profiles with cited peer-reviewed sources for every species. Circuit inference, track identification, pressure response, and seasonal behavioral data.
Built For

Hunters pursuing ungulates, predators, and upland game
Field trackers and wildlife monitors
Search and rescue teams operating in backcountry
Naturalists and wildlife photographers
Anyone who wants to understand what an animal was doing and where it went

The Build
SNAC started with 946 pages of handwritten field notes before a single line of code was written. The developer — a field tracker and hunter based in Maple Ridge, BC — had no prior programming experience when the project began.
The first prototypes were built on a smartphone. Development moved to a borrowed laptop before eventually landing on a proper machine. Every phase of the build was learned from scratch — React Native, JavaScript inference engines, YOLO computer vision, model training, Android builds, the full stack.
Two years of nights and weekends. One developer. No team, no funding, no CS degree.
The behavioral data powering the inference engine comes from 10+ years of field experience reading sign in coastal BC combined with peer-reviewed wildlife research cited for every species. The goal was to build the tool that didn't exist — one that thinks like a tracker, not a database.
