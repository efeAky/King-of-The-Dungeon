# King-of-The-Dungeon
King of the Dungeon
A text-based dungeon crawler RPG where you must explore a dangerous temple, collect treasures, buy
essential items, and defeat three powerful bosses to save the village.
Game Overview
Navigate through a branching dungeon filled with traps, treasures, and monsters. Strategic resource
management and tactical combat decisions determine your success. Each boss requires a specific item to
defeat, forcing players to explore, collect gold, and shop wisely.
Character Classes
Choose from three distinct classes, each with unique advantages:
Warrior: 15 HP, 5 Attack, 0 Gold - High damage fighter specializing in offense
Sorcerer: 17.5 HP, 2.5 Attack, 0 Gold - Durable survivalist with the highest health
Aristocrat: 10 HP, 2.5 Attack, 10 Gold - Fragile but wealthy, can buy items immediately
Combat System
Turn-based combat with risk/reward mechanics:
Your Turn
Attack: 50% chance to deal full damage, 50% chance to take half damage from counter-attack
Wait: Take defensive stance and recover HP equal to half enemy damage (no risk)
Enemy Turn
Parry: 50% chance to avoid attack and deal full damage, 50% chance to take half damage
Evade: 50% chance to avoid attack and heal, 50% chance to take full damage
Game Mechanics
Exploration
Navigate between rooms using directional commands (Left, Right, Forward, Back)
Visit the Merchant to purchase essential boss items
Discover treasure rooms containing gold
Avoid or survive dangerous traps
Boss Battles
Each boss requires a specific item to challenge:
Goblin Boss requires Goblin Poison
Dragon Boss requires Dragon Sword
Vampire Boss requires Garlic
Resource Management
Collect gold from treasure rooms (10 gold each)
Purchase items from the Merchant (10 gold each)
Manage HP through combat choices and healing items
Map Layout
Gameplay Tips
Start by exploring treasure rooms to collect gold
Purchase all three boss items from the Merchant early
Traps deal 5 damage each but only trigger once
Use "Wait" when low on health for safe healing
Parry is high-risk/high-reward, Evade is safer but less rewarding
The Aristocrat's starting gold allows immediate item purchases
The Sorcerer's extra health makes them more forgiving for new players
Win Condition
Defeat all three bosses to save the village and win the game.
Spawn Point ────── Merchant
│
Temple Entrance
│  │ │
│  │ └──── Bloody Path ──── Vampire Boss // Treasure // Trapp
│  │
│  └────── Flaming Path ──── Dragon Boss // Treasure // Trapp
│
└───────── Dirty Path ────── Goblin Boss // Treasure // Trapp
Controls
Movement: Type directional commands (Left, Right, Forward, Back)
Combat: Type "Attack" or "Wait" on your turn, "Parry" or "Evade" on enemy turns
Shopping: Type item names or "Quit" to leave the merchant
Quit: Type "Quit" during exploration to exit the game
Game Features
Three unique character classes with different strategies
Balanced tactical combat system
Resource management and exploration
Multiple paths and room types
Persistent world state (cleared traps, defeated bosses, collected treasures)
Input error handling and case-insensitive commands
