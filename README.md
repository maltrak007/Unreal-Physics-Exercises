# Unreal Physics Exercises

A set of university exercises experimenting with **physics in Unreal Engine**, including the **Chaos** destruction/physics system. Each exercise contains the C++ source (saved as `.txt` for easy reading) and a gameplay video capture.

## Exercises

| # | Topic | Key classes |
|---|---|---|
| 1 | Particle emitter | `EmisorParticulas`, `Particle` |
| 2 | Gravity fields acting on particles | `GravityField`, `Particle` |
| 3 | Rotating particles | `EmisorParticulasRotatorias`, `RotatingParticle` |
| 4 | Rigid solids and spheres | `Solid`, `SolidSphere`, `GameMode` |
| 5 | Physics game mode setup | `GameMode` |
| 7 | Ball repelled by volumes | `Pelota`, `RepelBallVolume` |
| 9 | Ball collision detection | `DetectBallCollision` |
| 10 | Impulse applied by a rectangle | `ImpulseRectangle` |
| 12 | **Own exercise: parkour** — wall-running component plus a jump pad that launches the player | see `Ejercicio12` |

## Structure

```
Fisica_GonzaloLinanAldana/
  EjercicioN/
    Codigo/   C++ headers and sources (.txt)
    Video/    Demo capture (PracticaNVideo.mp4)
```

Exercise 12 has an `Explicación.txt` and an `EjercicioPropio` folder with the parkour mechanic description and video.

## Using the code

Copy the `.h` / `.cpp` contents into a C++ Unreal project (removing the `.txt` suffix), add the classes to your module and compile. The videos show the expected behaviour.

## Author

**Gonzalo Liñán Aldana** — [GitHub](https://github.com/maltrak007)
