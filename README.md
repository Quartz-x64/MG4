# MG4
## Devlog
Write your Devlog here.
FloatAnimation makes each fish food object bob up and down over time.
Start() runs once when the object becomes active. It usually records the object’s starting position and initializes animation values, such as _up and _timer.
Update() runs once per frame. It changes the object’s vertical position so the food moves upward and downward smoothly.
_up indicates which direction the food is currently moving: up or down. When the food reaches one end of its motion, the script switches _up so it travels the other way.
_timer tracks elapsed time, often to control how long the food moves in one direction before switching.
Together, Update() uses _up to choose the movement direction and _timer to track progress, creating the repeated floating motion.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
