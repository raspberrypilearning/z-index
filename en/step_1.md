In CSS, `z-index` is a property that controls the layer order of elements on the z-axis (the axis that comes out of the screen towards the viewer). 

**TODO** Request redraw of image:
![A smartphone on its side showing the width of the phone screen as the x axis, the length as the y axis and the z axis coming out of the screen.](images/phoneAxes.png)

https://developer.mozilla.org/en-US/docs/Web/API/Device_orientation_events/Orientation_and_motion_data_explained/axes.png

You can use the `z-index` property to make elements appear in front of or behind each other. 

Styling an element with z-index of `1`, will cause it to appear on the 'top' layer in front of other elements, (which are set to `0` by default).