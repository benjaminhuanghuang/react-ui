## No global 
Since CSS selectors are global, it’s necessary to avoid any possibility of naming collision.

## Unidirectional styles
Since components can be used across applications, it’s necessary for component styles to be unidirectional; that is, child components cannot modify styles outside
of their scope.

layout focused CSS attributes like margin, width, height, etc. and CSS selectors that extend beyond the scope of their
component should be avoided.


## Shareable constants
Modern interfaces are highly interactive. Therefore, it’s necessary to be able to share constants between HTML, CSS and JavaScript.

## Deterministic resolution
Component behavior must be predictable. So, it’s necessary to avoid situations where
loading styles asynchronously can result in different results.

## Isolation
Since components must be modular, it’s necessary for their styles and behavior to be isolated and well encapsulated.

## Extendable
Since components can be used in many contexts, it’s necessary to be able to extend their styles and behavior.