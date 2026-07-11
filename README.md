# 🏋️ Gym Trainer

An offline-friendly exercise library and workout-plan builder covering **1,323 exercises** with animated GIF demonstrations.

**Live site:** https://prateekvishnu.github.io/gym-trainer/

## Features

- **Browse & filter** by target area, tools (equipment), difficulty level, and muscle — plus live search.
- **Exercise detail** modal with animated GIF, muscles worked, and step-by-step instructions.
- **Difficulty tags** (Beginner / Intermediate / Advanced) auto-derived for every exercise.
- **Suggested sets × reps** on plan exercises.
- **Favorites** ⭐ saved in your browser.
- **Ready-made plans** (Full-Body, Push/Pull/Legs, Upper/Lower, Dumbbell-Only) and a **custom plan builder** saved to `localStorage`.
- **Export My Plan to PDF** via the browser print dialog.

## How it works

The app is a single static `index.html` plus a `data.js` dataset. Exercise GIFs stream from the
[jsDelivr CDN](https://www.jsdelivr.com/) copy of the open-source
[ExerciseGymGifsDB](https://github.com/JahelCuadrado/ExerciseGymGifsDB) library, with a fallback to a
local `assets/gifs/` folder when running offline.

## Credits

Exercise animations © the [ExerciseGymGifsDB](https://github.com/JahelCuadrado/ExerciseGymGifsDB) project.
