# Cthulhu Rising

## Wireframes
_color coded sections_
* Header: Blue
* Nav: Purple
* Hero: Green
* Intro Info: Orange
* Panels: Red
* Footer: Yellow

###



## Sass Usage
_take notes on how to use SASS. 10 individual and specific uses:_

<!-- |:---:|:---:| -->
| Goal | Sass |
|:------:|:-------:|
| Logically separate styling into distinct and modular sections | use imports to combine separate scss files into a single 'main.scss' file |
| Keep padding and margin consistent across layout elements | Use extends to apply basic styling to layout/container elements |
| Generate responsive columns | Use loop to create a standard 12 column grid system
| Use a consistent color theme throughout the site | Declare color variables to be used as a palette |
| Add special color tints/shades/mixes for hover states and other special cases from chosen color palette variables | Create variations of colors using functions to adjust current color scheme |
| Reset default browser styling | Use a mixin that includes browser specific prefixes for box-sizing property |
| media queries: we need em | store media query information for various screen sizes in mixins and include those mixins within style definitions for components with responsive styles  |
|  | nesting |
|  |  |
|  |  |
|  | why doesn't this one count? |

Basic Layout Wireframe:
![Basic Layout](layout-basic.jpg)
Side-nav Layout Wireframe:
![alt text](layout-sidenav.jpg)
