# 27hc641-as-2364-programming-adapter
Small adapter to program 27hc641 EPROMs to be used as pincompatible replacements for 2364 PROMs.

![render image](https://github.com/InsaneDruid/27hc641-as-2364-programming-adapter/blob/main/images/27hc641-as-2364-programming-adapter_render.png)

[Schematic](https://github.com/InsaneDruid/27hc641-as-2364-programming-adapter/blob/main/27hc641-as-2364-programming-adapter.pdf "Schematic")  

[Bill of Materials](https://htmlpreview.github.io/?https://github.com/InsaneDruid/27hc641-as-2364-programming-adapter/blob/main/bom/27hc641-as-2364-programming-adapter_bom.html "Bill of Materials")

## Usage
The 27hc641 itself is not directly pin compatible with the 2364 PROM. Fortunately, this only affects three address pins, so all it takes is to swap these address pins during the programming process so that the arrangement matches that of a 2364. This adapter does just that.

* Plug a 27hc641 into the adapter.
* Plug the adapter with the 27hc641 into your EPROM programmer and select 27hc641 as EPROM type.
* Program as usual.
* After programming, the 27hc641 is a direct replacement for a 2364 PROM and can be used without any further work or adapters.

## The License
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.  
See https://creativecommons.org/licenses/by-sa/4.0/.
