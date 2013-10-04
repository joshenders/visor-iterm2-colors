# visor-iterm2-colors

A [Visor/TotalTerminal](http://totalterminal.binaryage.com/) color scheme for [iTerm2](http://www.iterm2.com/).

The RGB values for the Visor profile in [Visor/TotalTerminal](http://totalterminal.binaryage.com/) are defined as:

|            | Black    | Red        | Green      | Yellow      | Blue        | Magenta     | Cyan        | White       |
| ---        | ---      | ---        | ---        | ---         | ---         | ---         | ---         | ---         |
| **Normal** | 78,78,78 | 255,108,96 | 168,255,96 | 255,255,182 | 150,203,254 | 255,115,253 | 156,255,255 | 238,238,238 |
| **Bold**   | 85,85,85 | 255,0,0    | 0,255,0    | 255,255,0   | 0,0,255     | 255,0,255   | 0,255,255   | 255,255,255 |

| Text        | Bold Text   | Selection | Cursor    |
| ---         | ---         | ---       | ---       |
| 242,242,242 | 255,255,255 | 65,65,65  | 255,249,0 |

# FAQ
**Q:** Why does magenta seem brighter than it does in Visor?
**A:** In iTerm2, the RGB values are stored internally as floating point
numbers. In Visor, they're an integer triplet. You'll notice they're defined as
the same values in the RGB slider but due to floating point converstion, the
shade is ever so slightly different. As far as I know, this is the closest
approximation.
