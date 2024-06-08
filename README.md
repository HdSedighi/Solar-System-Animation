
           ![Rec0061-ezgif com-video-to-gif-converter](https://github.com/HodaSedighi/Solar-System-Animation/assets/34411345/70f3fa9c-f23c-4919-83a1-452c434a3892)


The provided code creates a simple animation of a solar system with the Sun at the center and a single planet (representing Earth) orbiting around it. Here's an introduction to the code:

- **HTML Structure**:
  - The HTML structure consists of a `div` element with the class `solar-system`, which serves as the container for the entire solar system animation.
  - Inside the `solar-system` div, there are two nested div elements: one representing the Sun with the class `sun`, and another representing the orbit of the planet with the class `orbit`. The planet itself is represented by a div with the class `planet`, which is nested inside the `orbit` div.

- **CSS Styling**:
  - The CSS styles are used to position the elements and create the visual effects for the solar system animation.
  - The Sun is styled as a yellow circle with a diameter of 100px and positioned at the center of the container using absolute positioning and the `transform: translate(-50%, -50%);` property.
  - The orbit of the planet is styled as a circle with a diameter of 400px and positioned at the center of the container.
  - The planet is styled as a blue circle with a diameter of 20px and positioned at the center of the orbit. Its initial position is defined using the `transform: translate(-200px, -50%);` property, which places it at a distance of 200px from the center of the orbit (representing its initial position in the orbit).

- **Animation**:
  - The planet's orbit animation is defined using the `@keyframes` rule named `orbit`.
  - The animation starts with the planet at its initial position (0% keyframe) and rotates it around the Sun by 360 degrees while maintaining its distance from the Sun (100% keyframe). This creates the illusion of the planet orbiting around the Sun in a circular path.
