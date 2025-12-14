# ISI Mods Unbound

A 7 Days to Die (7D2D) mod that lets you install any mod on any thing. It also lets you stack mods and remove the restriction on installing similar mods at once allows you install similar mods at once.

Examples:

- Any Mod on Anything: Burning Shaft on a Knife, Full Auto on Armor
- Stackable Mods: Install 4 x Full Auto mods on an M60 Machine Gun... or a Chainsaw
- Mod Are No Longer Exclusionary: Using a Barrel Extender no longer prevents you from adding a Silencer.
- Install Full Auto and Drum Magazine mods in _armor_ so _every_ gun fires faster and has a larger magazine
- Stack attribute mods in the weapons or tools that need them

Please drop a comment if you find a fun combination (so others can try it out).

![knife with burning shaft, barbed wire, chain, and spike mods](images/knife.png)
![outfit with full auto, drum magazine and two quad pocket mods](images/outfit.png)
![chainsaw with four full auto mods](images/chainsaw.png)
![m60 with barrel extender and silencer mods](images/m60.png)

## Somewhat Bound

- Full Auto and Burst Trigger Mods have minimal effect on Bows.
  - Originally, installing these mods on bows caused reload issues and eventual game crashes/corrupted saves.
  - I determined that raising the BurstRoundCount above 1 was causing the bug, so I disabled that effect so that we could safely install those mods on bows.
- Drone mods cannot be installed in Armor.
  - Attempting to put Drone mods in Armor interrupts the game, opening a console full of red errors.

## Other Notes

- Mods with no effect
  - Some mods do not do anything if installed on something it wasn't designed for.
  - Example: Installing a Motor Tool Tank Mod on a Motorcycle does not increase the size of the gas tank
- Stackable Effects
  - While the game will let you stack any mod, sometimes the actual effects do not stack
  - Stacks: Full Auto Mods, Pocket Mods, Attribute Mods, etc.,
  - Does not stack: Impact Bracing Mod

## Testing

1. Install incompatible mods together (e.g., Barrel Extender + Silencer)
2. Stack multiple identical mods (e.g., 4x Full Auto on M60)
3. Install weapon mods on armor, tools, vehicles, and drones
4. Test Bow compatibility - install Burst/Full Auto mods on bows to confirm no crashes
5. Test Drone mod restriction - confirm drone mods cannot be installed in armor
