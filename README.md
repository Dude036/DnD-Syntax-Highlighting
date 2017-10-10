# Pathfinder Syntax Highlighting

This is a simple Pathfinder Quest Syntax Highlighter for Sublime Text Editor 3. This was created to aid in producing quests for Pathfinder. More languages or interpretations to come.

## Installation

### General purpose single installation

* Under Tools/Developer, create a New Syntax. Copy/Paste the entire raw DnD.submline-syntax file into it, and save.

### Installation with Version Control

* Clone the repository inside your packages directory. You can find it under Preferences/Browse Packages... inside Sublime.

## API Reference

This was built using Sublime Text Editor 3 version 3143, and the newest Sublime Syntax highlighting schema using YAML 1.2.

## Supported Highlighing features

### Quotes

* "Quote goes within the the double quotation marks."

### Key Words

* Note(s)
* Economy
* Resources
* Description
* Pickup
* Location(s)
* People
* Reward(s)
* Items
* Quantity
* Pricing
* Weapons
* Armor
* Shields
* Consumable
* Food
* Drink
* Drinks
* Potion(s)
* Potion
* Encounter(s)
* AC
* Flat
* HP
* Size
* Speed
* Init or Initiative

### Money, Health, and Number Information

*Supports expressions followed by information and will classify it as such.*

* 350 XP, 20 gp, 5x times, 15 lbs, 1 ft

### Stats

* Strength or STR
* Dexterity or DEX
* Intelligence or INT
* Wisdom or WIS
* Constitution or CON
* Charisma or CHA

### Saves

*Can have save or Save at the end of each phrase.*

* Will
* Fortitude or Fort
* Reflex or Ref

### Skills

*Contains all possible skills per Pathfinder Skill set. Will also highlight every use of Check(s) and check(s)*

* Acrobatics
* Appraise
* Bluff
* Climb
* Craft
* Diplomacy
* Disable Device
* Disguise
* Escape Artist
* Fly
* Handle Animal
* Heal
* Intimidate
* Knowledge (arcana)
* Knowledge (dungeoneering)
* Knowledge (engineering)
* Knowledge (geography)
* Knowledge (history)
* Knowledge (local)
* Knowledge (nature)
* Knowledge (nobility)
* Knowledge (planes)
* Knowledge (religion)
* Linguistics
* Perception
* Perform
* Profession
* Ride
* Sense Motive
* Sleight of Hand
* Spellcraft
* Stealth
* Survival
* Swim
* Use Magic Device

### Items

Items are variable, and they can have any name, so when creating a new item, use the carot to begin, and two semi-colons to end. Example:

* ^ Item Name Here ::

### Spells

Spells also have variable names so to have a spell iuse angle brackets around the name. Example:

* \<Spell Name Here\>

### Enemies and Enemies

Enemies are given a very loud color for easy reference. Similairly to Items, there is a start and an en character. Two exclamation marks to begin the name, and  two semi-colons to end the name. Example:

* !! Enemy Name Here ::

Events also use exclamation points to begin their string, but useonly a single exclamation point. Example:

* ! Event Name ::


### DC and Dice Rolling

To make it easy enough to spot, I added a highlighter for every instance of dice rolling or difficulty Example:

* 1d20
* DC15

### Special Characters

There are characters that have little purpose. and are subdues to not make them not as noticable. These include symbols as:

* @
* ~
* $

They are both the open and the close comment, and all work in tandem. I.e. Highlighted ~Not Highlighted@ Highlighted

## Contributions

If there are issues with this, please submit a bug report. If there is an issue and you know how to fix it, feel free to do so.

## Legal Information

Paizo, Pathfinder, and their logos are trademarks of Wizards of the Coast LLC are registered trademarks of Paizo Inc®. All Rights Reserved.
This repository is not affiliated with, endorsed, sponsored, or specifically approved by Paizo Publishing®, LLC in any way. For more information about Paizo Publishing® or any of other trademarks or other intellectual property, please visit their website at http://paizo.com/pathfinderRPG.
