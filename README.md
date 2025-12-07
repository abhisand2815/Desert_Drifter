# Desert Drift Runner 🏜️💨

A 2D endless-runner hoverboard game built using HTML5 Canvas, CSS, and JavaScript.
Your goal is simple: dodge rocks, hit boost pads, and survive as long as possible while gliding across animated desert dunes.

## ⭐ Overview

Desert Drift Runner is a fast-paced browser game where the player rides a hoverboard over dynamic, wave-animated desert terrain. Rocks spawn randomly as obstacles, while glowing boost pads give temporary speed boosts and extra score. The game includes smooth physics, clean controls, start and game-over overlays, and a live score/speed HUD — all implemented without external libraries.

## 🚀 Features

1) Smooth hoverboard movement & jump mechanics
2) Wave-based animated desert dunes (sine function)
3) Rocks as obstacles with instant Game Over
4) Glowing boost pads that increase speed + score
5) Real-time HUD (Score + Speed)
6) Start screen, Game-Over overlay, and Restart system
7) 100% vanilla JavaScript, no frameworks used

## 🎮 Controls
|  Action   |  Key     | 
| :-------- | :------- | 
|  Jump | `Space / ↑ Arrow` | 
|  Restart | `R` | 

## Project Preview
<img width="1200" height="537" alt="screenshot" src="https://github.com/user-attachments/assets/637557d5-30a8-402d-aba3-6b09cf3f0489" />

## 📡 APIs Used
### HTML5 Canvas API
Used to render everything on screen:
1) getContext("2d")
2) fillRect(), stroke(), arc(), ellipse()
3) createLinearGradient(), createRadialGradient()
4) requestAnimationFrame()
5) Custom roundRect()

### JavaScript DOM API
1) document.getElementById()
2) window.addEventListener("keydown"/"keyup")
3) Keyboard event codes (e.code)

### Math & Timing API
1) Math.sin() → animated dunes
2) Math.random() → obstacle spawning
3) performance.now() → smooth timing


## Acknowledgements

 - [HTML5 Canvas Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
 - [JavaScript Game Loop Guide](https://developer.mozilla.org/en-US/docs/Games/Anatomy)
 - [MDN JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
- [CSS Gradients & Styling](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient)
- [Game Math & Sine Wave Concepts](https://gamedevelopment.tutsplus.com/tutorials)
 - [Inspiration (Endless Runner Games)](https://en.wikipedia.org/wiki/Endless_runner)

## 📜 License

This project is open-source and free to use for learning and personal development.



