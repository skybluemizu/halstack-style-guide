
## DXC Toggle Visual Guidelines

#### Overview

Toggle buttons can be used to put together related options that share a common attribute modification.
It allows the user to switch from one selected option to another in the same control, having one option selected at a time. Also, there can be another variation that allows selecting multiple options from the current toggle group.


##### *Appereance*

The appearance of the toggle looks like button component, because it is based on the same specifications to keeping consistency along with the application, but in this case are offered fewer visual modes.

###### Modes

Two modes are presented: __basic__ and __outlined__.
<div> <img src="images/toggle_modes.png"/></div>

###### States

Different states are defined in the life cycle of the component:
__Normal__, __selected__, __unselected__, __disabled__ and __clicked__.


##### *Theming*

###### Light theme

Yellow: #FEDD00  
Black: #000000  
Grey unselected option (default): #F6F6F6  
Disabled opacity (default): 0.5  
Grey selected option (outlined): #EEEEEE  
Grey unselected option (outlined): #FFFFFF  
Disabled opacity (outlined): 0.25  
<br>
<div> <img src="images/toggle_light.png"/></div>

###### Dark theme

Same colors are using for the default mode in the dark theme. New colors for the outline mode are defined as follow:

Grey selected option (outlined): #EEEEEE  
Hover grey unselected: #666666  
Disabled opacity (outlined): 0.5  
<br>
<div> <img src="images/toggle_dark.png"/></div>

##### *Design Specifications*

| Property           | Value|
|--------------------|------:|
| Margin            | `15px` |
| Padding right/left (item)| `30px` |
| Padding top/bottom (item)| `12px` |
| Border Radius | `4px` |
| Border thickness| `2px` |
| Min. height| `43px` |
| Font size| `14px` |
| Font weight| `Regular` |

<br>
<div> <img src="images/toggle_specs.png"/></div>

###### Icon Usage

Inside the toggle button, it is possible to use icons to represent recognizable actions.
The specifications for icon usage differs a little bit in relation to text usage.

The size of the icons should be 24 by 24 pixels, it must be centered respecting to the box that contains it vertically and horizontally. 
The ideal padding for each option is 10 pixels for top and bottom and 12 pixels to right and left sides.

The behavior in regard to colors and interactions are the same that for the previous.

###### User Interface Design Considerations

Toggles should be used in place of radio buttons whenever the options are
- Minimal in number, i.e. 3 or 4 maximum choices where only one selction is required
- Opposites of each other