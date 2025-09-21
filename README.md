The project is fully adapted to different devices and screen resolutions. To achieve this, we used:
* **Media queries (`@media`):** Point style change for breakpoints of `320px`, `768px', `1024px` and `1536px'.
* **Mobile-First approach:** Styles were first developed for mobile devices, and then adapted for wider screens.
* **Adaptive Images:** Using the `max-width: 100%` property and the `<picture>` tag to optimize loading on different devices.
* **Hiding/rearranging elements:** Elements that are not essential for the mobile context are hidden or repositioned using `flex-order` and `display`.
