# Introduction

Inspired by Jack Herrington's blasting fast react context video.
https://www.youtube.com/watch?v=ZKlXqrcBx88. Thank you Jack!

Use both `useSyncExternalStore` and `useRef` to share states in context/provider between react components,instead of `useState`, to just re-render only component that subscribes to a subset state that is published (or changed).

