# Advanced Starter Pack 2

This version implements the requested Advanced Starter concept as closely as standard Unciv JSON allows.

HUMAN / ADVANCED STARTER:
- Modern Armor: Agriculture
- Mechanized Infantry: Agriculture
- Advanced Starter difficulty gives both units to the human player at game start.
- Modern Armor starts with the requested combat promotions.
- Both are never Barbarian units.

NORMAL / AI TECHNOLOGY:
- Modern Armor AI: Lasers, Aluminum
- Mechanized Infantry AI: Mobile Tactics
- M1A1 Abrams: Lasers, Aluminum

IMPORTANT:
Unciv's standard Units.json has one requiredTech per unit. It does not have separate humanRequiredTech and aiRequiredTech fields. Therefore this pack uses separate AI-version unit names to preserve the requested technology split in JSON-only form. The AI versions become available at their normal technologies.

The fields use requiredResource (the correct Unciv field name), not resourceRequired.

Images:
- Images/UnitIcons/Modern Armor.png
- Images/UnitIcons/Mechanized Infantry.png
- Images/UnitIcons/M1A1 Abrams.png
- matching UnitPortraits are included.
- 
