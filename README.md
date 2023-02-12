# CS:GO configuration files

This is a set of personal configuration files (`cfg`) for the game
[Counter-Strike: Global Offensive][csgo-on-steam], which configure certain game
settings, bind controls and shortcuts, and enhance the gameplay itself.

## Installation and usage

To install it, place the [`assets` folder](assets) content in the directory
where the game was installed, such as
`Steam/steamapps/common/Counter-Strike Global Offensive`. At the end of the
process, all the `cfg` files should be in the `csgo/cfg` folder.

The last thing to do is set the following arguments in the game's launch
options, replacing `THREADS` with the desired number of threads and `HERTZ`
with the display refresh rate:

```text
-novid -nod3d9ex -high -threads THREADS -tickrate 128 -freq HERTZ -refresh HERTZ +fps_max 0 +fps_max_menu 0 +exec main
```

That's it. Right after running the game, the console should confirm that the
files were successfully loaded.

If help is needed, execute `exec help` in the console or, if a match is in
progress, press the <kbd>HOME</kbd> key. This will print in the console some
guidance on using the resources provided by these settings, in addition to the
buy menu shortcuts that have been set.

## License

This project is licensed under the
[GNU General Public License v3.0 or later][gpl-3.0-or-later-license]. Please
read the full [license agreement](COPYING.md) for more information.

<!-- Links -->
[csgo-on-steam]: https://store.steampowered.com/app/730/CounterStrike_Global_Offensive
[gpl-3.0-or-later-license]: https://www.gnu.org/licenses/gpl-3.0.html
