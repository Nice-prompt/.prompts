# React Native Reanimated Prompts - Complete Concept Coverage

## 1. Basic Shared Values and useSharedValue Hook

**Prompt:** Create a React Native component that demonstrates the fundamental concept of `useSharedValue` in Reanimated. Build a simple counter that increments when a button is pressed, but the counter value should be animated smoothly. Show how to use `useAnimatedStyle` to connect the shared value to a View's style properties (like opacity or scale). Include proper TypeScript types and explain the difference between shared values and regular React state.

**Concepts Covered:** `useSharedValue`, `useAnimatedStyle`, basic animations, TypeScript integration

---

## 2. Interpolation and Value Mapping

**Prompt:** Design a scroll-based animation component where a header shrinks and changes opacity as the user scrolls down. Use `interpolate` to map scroll position values to different style properties (height, opacity, translateY). Create smooth transitions between different scroll ranges and demonstrate how to use `extrapolate` options (clamp, extend, identity). The header should have a minimum and maximum height with smooth transitions.

**Concepts Covered:** `interpolate`, `extrapolate`, scroll-based animations, value mapping

---

## 3. Spring and Timing Animations with withSpring and withTiming

**Prompt:** Build a interactive card component that can be dragged around the screen and snaps back to its original position when released. Use `withSpring` for the snap-back animation and `withTiming` for other state changes (like card rotation during drag). Implement different spring configurations (damping, stiffness, mass) and timing curves. Show how to chain animations and use callbacks to trigger events when animations complete.

**Concepts Covered:** `withSpring`, `withTiming`, gesture handling, animation chaining, callbacks

---

## 4. Gesture Handler Integration with PanGestureHandler

**Prompt:** Create a swipeable card stack (like Tinder) using `react-native-gesture-handler` and Reanimated. Implement `PanGestureHandler` with `useAnimatedGestureHandler` to handle drag gestures. Cards should rotate and move based on pan gestures, with different behaviors for left/right swipes. Include velocity-based animations and card stack management where swiped cards are removed and new ones appear from behind.

**Concepts Covered:** `useAnimatedGestureHandler`, `PanGestureHandler`, gesture-driven animations, velocity calculations

---

## 5. Layout Animations with Entering/Exiting

**Prompt:** Build a dynamic todo list where items can be added and removed with smooth layout animations. Use Reanimated's entering and exiting animations (`FadeIn`, `SlideInLeft`, `SlideOutRight`, etc.) and create custom entering/exiting animations using `withSequence` and `withDelay`. Implement staggered animations where multiple items animate in sequence, and show how to customize animation duration and easing curves.

**Concepts Covered:** Layout animations, entering/exiting animations, `withSequence`, `withDelay`, custom transitions

---

## 6. Advanced useAnimatedScrollHandler and Scroll Animations

**Prompt:** Create a parallax scrolling screen with multiple layers moving at different speeds. Use `useAnimatedScrollHandler` to track scroll position and implement complex scroll-driven animations including: parallax backgrounds, sticky headers, revealing/hiding elements based on scroll direction, and scroll-to-reveal animations. Include momentum-based effects and scroll velocity calculations for advanced interactions.

**Concepts Covered:** `useAnimatedScrollHandler`, parallax effects, scroll direction detection, momentum animations

---

## 7. Shared Element Transitions and Navigation

**Prompt:** Implement a shared element transition between two screens (like a photo gallery to detail view). Create smooth hero animations where an image smoothly transitions from a grid view to a full-screen detail view. Use Reanimated with React Navigation and demonstrate how to synchronize animations across screen transitions. Include proper handling of status bar, safe areas, and different screen sizes.

**Concepts Covered:** Shared element transitions, navigation integration, hero animations, cross-screen coordination

---

## 8. Custom Hooks and Reusable Animation Logic

**Prompt:** Design a set of custom hooks that encapsulate common animation patterns: `useBouncyPress` (for button press animations), `useFadeInOnMount` (for component mounting animations), `useRotatingIcon` (for loading spinners), and `useProgressAnimation` (for progress bars). Each hook should be highly configurable with options for duration, easing, and animation values. Show how to compose these hooks and make them reusable across different components.

**Concepts Covered:** Custom hooks, animation encapsulation, reusable patterns, composition

---

## 9. Performance Optimization and runOnJS

**Prompt:** Build a complex animated dashboard with multiple animated components, charts, and real-time data updates. Demonstrate performance optimization techniques including: proper use of `runOnJS` for side effects, avoiding unnecessary re-renders, optimizing worklet functions, and using `useAnimatedReaction` for responding to shared value changes. Include performance monitoring and show how to debug animation performance issues.

**Concepts Covered:** `runOnJS`, `useAnimatedReaction`, performance optimization, worklets, debugging

---

## 10. Advanced 3D Transformations and Complex Animations

**Prompt:** Create an immersive 3D card flip component with perspective transformations, shadows, and complex gesture interactions. Implement multiple gesture handlers (pan, pinch, rotation) working together, 3D matrix transformations, and physics-based animations with realistic momentum and friction. Include advanced features like gyroscope integration for device tilt effects and complex animation sequences that combine multiple transformation types.

**Concepts Covered:** 3D transformations, multiple gesture handlers, physics simulations, device sensors, complex animation sequences

---

## Additional Learning Resources

Each prompt builds upon previous concepts while introducing new ones. Start with prompt 1 and work your way through to master React Native Reanimated comprehensively.

**Key Learning Path:**
1. Master shared values and basic animations (Prompts 1-2)
2. Learn gesture integration (Prompts 3-4)
3. Understand layout animations (Prompt 5)
4. Advanced scroll handling (Prompt 6)
5. Navigation integration (Prompt 7)
6. Code organization and reusability (Prompt 8)
7. Performance and optimization (Prompt 9)
8. Advanced 3D and complex interactions (Prompt 10)

**Best Practices to Follow:**
- Always use TypeScript for better development experience
- Leverage worklets for performance-critical animations
- Use appropriate easing curves for natural motion
- Test animations on physical devices for real performance
- Consider accessibility in animated components
- Profile and optimize animation performance regularly