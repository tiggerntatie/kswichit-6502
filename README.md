# kswichit-6502

[Kswichit 6502 Microprocessor Kit Simulator](https://tiggerntatie.github.io/kswichit-6502/)

A JavaScript 6502 assembler and simulator compatible with the [6502 Microprocessor Kit designed by Wichit Sirichote](https://www.kswichit.net/6502/6502.html).

The original code is (C)2006-2010 Stian Soreng - www.6502asm.com

Adapted by [Nick Morgan](https://github.com/skilldrick/6502js) and [Eric Dennison](https://github.com/tiggerntatie/kswichit-6502) (for the kswichit compatibility).

Released under the GNU General Public License (see http://gnu.org/licenses/gpl.html)

## Notes

Current implementation features are very limited:

* Default code execution begins at 0x200.
* Support for 8-bit LED display (GPIO1) at 0x8000.

Unsupported:

* Tick interrupt
* IRQ key
* LCD display option
