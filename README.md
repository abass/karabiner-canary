# Canary & Goku Keyboard Layout Config (Canary)
I use [Canary](https://github.com/Apsu/Canary) as my default keyboard layout and I wanted to share my [Karabiner Elements](https://karabiner-elements.pqrs.org/) layout settings to help others use the same layout or take inspiration from how I've set up my secondary layer.

*Please note that this only works with MacOS*

## What Is Goku?
[Goku](https://github.com/yqrashawn/GokuRakuJoudo) is a compiler that allows you to write and compile to Karabiner much easier (and more quickly). If you look at the file `goku.edn` you'll see how easy it is to map everything out. Even more complex secondary layers.

## How Do I Use Goku
1. Follow [this video here](https://www.youtube.com/watch?v=vysHEYTp0H4) to setup Goku on your machine (that's how I did it)
2. Simply copy the `goku.edn` file from this repo here to your `Users>name>.config` folder, then rename it to `karabiner.edn`.
3. Once it is in there, make sure in Karabiner you have a profile set up called `Default` (as running Goku will overwrite it — if you want to keep your current profile, rename it to something else, then create a new profile called `Default`).

*Feel free to add/modify any of the mappings (I've documented the Goku file to explain how to do everything)*

## Without Goku (Normal Karabiner)

### Use My Entire Config
1. Simply copy the `karabiner.json` file to `Users>name>.config>karabiner`
2. (make sure you first backup your existing `karabiner.json` file if you are already using it for something).

*You'll probably want to also delete some of the other profiles I have mapped for other layouts (in Karabiner Preferences)*

### Use Just Canary Or Extended Layer Mapping
1. Simply open the `canary.json` or `extended_layer.json` file and copy any of the relevant rules to your existing Karabiner file to `Users>name>.config>karabiner`
2. Be sure to remove all of the descriptive comments that I have in the json files or it won't work

## Customizations
Feel free to visit the Karabiner Preferences "Complex Modifications" tab to delete any additional mappings I have, like the "⌘ QWERTY" or "Extended Layer" mappings.

## Important Notes
**You must have your computer set to QWERTY in order for the mappings to work correctly, everything here is mapped from the starting point of QWERTY.**
