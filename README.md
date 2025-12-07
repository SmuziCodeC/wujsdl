# wujSDL

> A Pygame wrapper with boost and easy API  
> by **SmuziCodeC (SmuziCodes, wuj1av)**

![Made with Pygame](https://img.shields.io/badge/Made%20with-Pygame-red?logo=python)
![License](https://img.shields.io/badge/License-None--of--your--business-black)

---

## Why wujSDL?

- Fast rendering  
- Easy syntax  
- Can enable ModernGL easily  
- Open source (do whatever the hell you want)

> Yes, you can pirate it.  
> Yes, you can rewrite it in C++.  
> I don’t care.

---

## API

Just three lines. That’s all.

```python
import wujsdl as sdl
square = sdl.square(32, 32, "#FF0000", ((800-32) // 2, (600-32) // 2))
sdl.go("800x600 #FFFFFF Wujlav's Pygame Window")
