# WEB VR

### Head : 

It has a title where we define the heading for the website. Meta tag is used by search engines to describe your page. Script tag loads the a-frame library which does all the cool 3D stuff. Without this script, the web page will not be able to render 3D Objects.

### Body : 

This is where we write the content for our website. In this example we are creating a scene using <a-scene> tag and inside the scene we are creating basic blocks or shapes called “primitives”. These are all built in primitives in A-Frame. In this example, we are making a cubical box, a sphere, a cylinder and a plane.

Each of these primitives also has “attributes” inside the opening tag like we used to have it for <image> tag, <div> tag, etc. For example <a-box> has position attribute: to specify x,y,z coordinate of box in the scene, rotation attribute: to specify the angle of rotation on x,y,z axis and colour attribute: to specify the colour of the box.