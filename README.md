# LaTeX macros for Robotics, Vision and Control

This file includes macros to create equations in the style of those used in the textbook "Robotics, Vision & Control".

```latex
\include{rvc-notation}
```

## Poses

* `\pose_A` is the pose of frame A
* `\pose[B]_A` is the pose of frame A with respect to frame B

## Coordinate frames

* `\frame{A}` is coordinate frame A which renders as {A}

## Points

* `\point{A}` is point A which renders in Roman bold font

## Vectors

Vectors are rendered in italic bold font

* `\vec{t}` is a vector t 
* `\vec[A]{t}` is a vector t with respect to frame A
* `\dvec{t}` is vector of `\dot{t}`
* `\dvec[A]{t}` is vector of `\dot{t}` with respect to frame A
