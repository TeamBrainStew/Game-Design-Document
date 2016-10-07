# Game-Design-Document

This is an extremely basic GDD. I’ll flesh it out more as I get more information.

I’m using the list for milestones on pg 160 in the book.

Characters, objects, levels:  
Tier 1 characters: “runner”, “walker”, “thrower”. Each category uses the same model, to make their behavior more predictable by the player, but needs to have very distinctive texture and particle effects to make their element equally recognizable.  
Tier 2 character: Frost Giant boss. Only mob in his particular spawn, but does not prevent other spawns around him. Cannot be absorbed.  
Tier 3 characters: This is only if we are waaaaaaay ahead of schedule: I’d like to see if we could dual-element a mob, so that it will effectively have to be killed twice with different crystals. 

Tier 1 objects: The weapon itself with the variant crystals, and the energy tank. Wall/floor art to mark spawn locations.  
Tier 3 objects: again, these are irrelevant to gameplay and are only considered to be bonus features: wall/floor décor objects (torches, sconces, maybe rubble on the ground)

Tier 1 level: Two-story map with multiple up/down pathways. Large enough for the player to move around, but small enough that an ignored wave will quickly become a serious threat. The player’s weapon does not have a very long range, so we might not need huge rooms or very long hallways.  
Tier 2 level: Less individual floor space, more stories.  
Tier 3 level: Doors that can be closed to block off enemies (but can be opened by certain enemy types), randomized floor plans, moving walls to change layout during game.

Cinematics: no. If we are going to make anything like a cinematic, it will be, at most, a short, pre-rendered in-engine sequence that uses existing objects, behaviors, etc. The kind of scene that played on old SF2 arcade games between title screens. But honestly, we should almost certainly not bother.

Gameplay features:  
Tier 1 features: Gun has in/out mode and four crystals. Enemies spawn in at least three forms, in one of four elemental flavors. Waves composed of multiple spawn events, increasing in difficulty until player dies. Wave/spawn/kill counter for scoring (to be discussed). WASD control scheme, with individual keys for each crystal and a single key to toggle absorb/project.  
Tier 2 features: More enemy types, more complex spawn patterns. Finer control over gun (perhaps short-range spray vs long-range line).  
Tier 3 features: Dual-element creatures. Creatures at higher waves with unexpected attack behaviors. An XP system allowing the player to improve his equipment (larger tank, more project damage, more absorb damage, increased heat gauges and/or decreased burnout cooldowns on crystals, different weapon attacks or improvements on existing attacks) as waves progress.

Engineering features:  
Tier 1 features: weapon damage/type (absorb/project * crystal), enemy attack patterns, behaviors and scripts, level design  
Tier 2 features: increased complexity of enemy type/behavior, increased complexity of map/spawn locations and behaviors  
Tier 3 features: Engineering will be responsible for determining if we have the time and ability to add in any Tier 3 features, and if so, which.  

UI:  
Very simple.  
Weapon in right hand. Obvious crystal prominent at front (barrel end).  
Tank in left hand. Tank will display absorb/project setting.  
HP display.  
Not sure we should include some kind of minimap, but perhaps.  

Art style:  
We have the enemy models chosen for each type of enemy, and will layer the requisite effects on them to make their element obvious.  
The scenery is Ancient Egyptian in styling; sandstone, hieroglyphics. Walls bear signs of the elements, the elementals themselves, and the Egyptian gods, perhaps painted or inset with jewels.  
Need to discuss lighting with Engineering – general sourceless light, specific sources like wall sconces, perhaps light cast from the monsters themselves beyond bright particle effects.  
  
Technical:  
UE4. Looks like we’re using Blueprint for enemy behavior.  
Github for version control, documentation, and schedule repository.  
Online large-scale storage (currently Mediafire) for huge UE4 files.  


As stated at the beginning, this is very basic. I’ll clean it up as we have a chance to discuss the individual elements. Confirming listed features will allow us to generate a schedule.   




