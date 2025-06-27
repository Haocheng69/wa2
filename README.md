This is a chaotic, physics-based space simulation built with p5.js, featuring planets, moons, comets, black holes, a Doomsday event, and a few cursed surprises.
Users can create and destroy planetary systems, adjust gravity, trigger cosmic disasters, and watch orbital madness unfold — all in a fun and interactive way.
This simulation is inspired by Newton's Law of Universal Gravitation, modeling how celestial bodies interact using simplified orbital physics.
Real-world concepts simulated include:
Orbital mechanics (planets orbiting stars)
Gravity-based attraction
Comet impacts and collisions
Black holes and accretion
Moon orbits around planets
Merging of planetary bodies


| Class       | Description                                                                                                               |
| ----------- | ------------------------------------------------------------------------------------------------------------------------- |
| `Body`      | Represents planets, moons, and the sun. Includes physics like attraction, movement, trail drawing, and collision merging. |
| `Comet`     | Represents comets that enter the system, destroy planets, and trigger events like Doomsday.                               |
| `BlackHole` | Represents a gravitational singularity that consumes nearby matter and fades over time.                                   |
| (Main file) | Manages the UI, setup, draw loop, and simulation state.                                                                   |



| Control             | Action                                        |
| ------------------- | --------------------------------------------- |
| `Start Simulation`  | Begins the simulation.                        |
| `Click anywhere`    | Adds a new planet (may have moons).           |
| `Spawn Black Hole`  | Adds a black hole at a random position.       |
| `Remove Black Hole` | Fades and disables the black hole.            |
| `Doomsday`          | Removes the sun with a comet.                 |
| `Comet Shower`      | Rains 15 🥔 comets onto the system.           |
| `Slider    `        | Controls the strength of gravity.             |
| `Reset`             | Clears the simulation.                        |
| `Instructions`      | Shows detailed instructions.                  |
| `??`                | Opens a joke translation of instructions.     |

 Features
Sun: Fixed at the center; attracts planets.
Planets: Orbit the Sun. May spawn with moons. Can merge with each other.
Moons: Orbit planets with velocity adjustments.
Comets: Spawn periodically or manually. May shrink/destroy planets on impact.
Black Hole: Pulls all objects. Grows by absorbing mass. Can be removed.
Doomsday: Spawns a comet that destroys the Sun.
Comet Shower: Spawns 15 comets rapidly.
Gravity Slider: Adjust the gravitational constant G (try max for chaos).
❓ "??" Button: Opens a cursed goofy translation of the instructions.



