# visor-iterm2-colors

A [Visor/TotalTerminal](http://totalterminal.binaryage.com/) color scheme for [iTerm2](http://www.iterm2.com/).

### iTerm2
![iTerm2](http://f.cl.ly/items/173Y0O2C363E1i0H180R/iterm2.png "iTerm2")

### Visor/TotalTerminal
![Visor/TotalTerminal](http://f.cl.ly/items/2o0q0C2s0x2d2t343X1E/visor.png "Visor/TotalTerminal")

The RGB values for the Visor profile in *Visor/TotalTerminal* are defined as:

|            | Black    | Red        | Green      | Yellow      | Blue        | Magenta     | Cyan        | White       |
| ---        | ---      | ---        | ---        | ---         | ---         | ---         | ---         | ---         |
| **Normal** | 78,78,78 | 255,108,96 | 168,255,96 | 255,255,182 | 150,203,254 | 255,115,253 | 156,255,255 | 238,238,238 |
| **Bold**   | 85,85,85 | 255,0,0    | 0,255,0    | 255,255,0   | 0,0,255     | 255,0,255   | 0,255,255   | 255,255,255 |

| Text        | Bold Text   | Selection | Cursor    |
| ---         | ---         | ---       | ---       |
| 242,242,242 | 255,255,255 | 65,65,65  | 255,249,0 |

## FAQ
**Q:** Why does magenta seem brighter than it does in *Visor/TotalTerminal*?

**A:** In *iTerm2*, RGB values are stored internally as floating point numbers.
Upon inspection of the RGB slider, you'll notice they're defined as the exact
same values as in *Visor/TotalTerminal* but unfortunately, due to floating point
converstion, the shade is ever so slightly different. As far as I know, this is
the closest approximation.
