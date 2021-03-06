# visor-iterm2-colors

A [Visor/TotalTerminal](http://totalterminal.binaryage.com/) color scheme for [iTerm2](http://www.iterm2.com/).

### iTerm2
![iTerm2](/docs/images/iterm2-colors.png "iTerm2")

### Visor/TotalTerminal
![Visor/TotalTerminal](/docs/images/visor-colors.png "Visor/TotalTerminal")

The RGB values for the Visor profile in *Visor/TotalTerminal* are defined as:

|            | Black    | Red        | Green      | Yellow      | Blue        | Magenta     | Cyan        | White       |
| ---        | ---      | ---        | ---        | ---         | ---         | ---         | ---         | ---         |
| **Normal** | 78,78,78 | 255,108,96 | 168,255,96 | 255,255,182 | 150,203,254 | 255,115,253 | 156,255,255 | 238,238,238 |
| **Bold**   | 85,85,85 | 255,0,0    | 0,255,0    | 255,255,0   | 0,0,255     | 255,0,255   | 0,255,255   | 255,255,255 |

| Text        | Bold Text   | Selection | Cursor    |
| ---         | ---         | ---       | ---       |
| 242,242,242 | 255,255,255 | 65,65,65  | 255,249,0 |

## FAQ
**Q:** Why do some colors seem brighter/different than in *Visor/TotalTerminal*?

**A:** In *iTerm2*, RGB values are stored internally as floating point numbers.
The exact RGB values from *Visor/TotalTerminal* are used (verifiable with the
RGB slider) but unfortunately, due to floating point converstion, the colors
are ever so slightly different. As far as I know, this is unavoidable.

**Q:** How do I most closely mimic the text style in *Visor/TotalTerminal*?

**A:** The default 12pt. Monaco typeface gets you most of the way there.
Through comparison, I've found the following character spacing values to be a
close approximation.

![iTerm2 Character Spacing](/docs/images/iterm2-char-spacing.png "iTerm2 Character Spacing")

You may also want enable "Draw bold text in bold font" in the Text Rendering
heading under the Text section.

![iTerm2 Text Rendering](/docs/images/iterm2-text-rendering.png "iTerm2 Text Rendering")
