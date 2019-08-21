# LaTeX macros for Robotics, Vision and Control

This file includes macros to create equations in the style of those used in the textbook "Robotics, Vision & Control".

```latex
\include{rvc-notation}
```

## Poses

* `\pose`        abstract pose
* `\pose[f]`    pose with respect to a frame
* `\pose_A` is the pose of frame A
* `\pose[B]_A` is the pose of frame A with respect to frame B
* `\estpose`  estimated pose, with hat
* `\posedot`   derivative of abstract pose

## Coordinate frames

* `\frame{A}` is coordinate frame A which renders as {A}

## Points

* `\point{A}` is point A which renders in Roman bold font

## Vectors

Vectors are displayed in bold italic font

* `\vec{t}` is a vector t 
* `\vec[A]{t}` is a vector t with respect to frame A
* `\dvec{t}` is vector of `\dot{t}`
* `\dvec[A]{t}` is vector of `\dot{t}` with respect to frame A
* `\ddvec[f]{x`}  a double dotted vector 
* `\vech[f]{x}` a homogeneous vector (tilde above)
* `\vecb[f]{x}` a vector with bar 
* `\tvec[f]{x}` a homogeneous vector with a tilde
* `\hvec[f]{x}` an estimated vector with a hat

## Matrices

Matrices are displayed in bold font
* `\mat{x}`     a matrix
* `\mat[f]{x}`  a matrix with a coordinate frame
* `\dmat[f]{x}`  a matrix derivative
* `\sk{v}`  -> [v]x skew symmetric matrix

## Unit Quaternion

* `\q` displays as q with a bubble on top


## Lie Groups

Displayed in Roman font

* `\SO{n}`  special orthogonal group: SO(n)
* `\SE{n}`  special Euclidean group: SE(n)
* `\so{n}`  Lie algebra of SO(n): so(n)
* `\se{n}`  Lie algebra of SE(n): se(n)

## MATLAB code

Display a block of code in blue fixed-width font
```latex
\begin{Code}
[x,e] = eig(A);
\end{Code}
```

## Miscellaneous

### Units

* `\unit{U}` sets the contents in math mode with a preceding half space, eg. `\unit{m s^{-2})`
* `\mm`
* `\deg`
