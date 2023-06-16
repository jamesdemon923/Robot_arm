# Robot_arm

## Set up

* Operating & compiling system: Cmake + Visual Studio 2019(x64) in Windows11
* Framework: [OpenGL](https://github.com/opengl-tutorials/ogl)

## Build the Robot_arm model in Blender

Build the Robot_arm model in Blender and output each component as .obj file.

## Implement keyboard-based interaction with the robot arm

Use the **transformation matrix** to implement it.

## Create a Blinn-Phong model

Blinn-Phong model:
$$
L = L_{a}+L_{d}+L_{s}=k_{a}I_{a}+k_{d}(I/r^{2})max(0,\vec{n} \cdot \vec{l})+k_{s}(I/r^{2})max(0,\vec{n} \cdot \vec{h})^{p}
$$


## Enable the Color picking

By reading the color of the pixel under the mouse cursor, it can identify which object is being pointed at. This color is then converted back to an integer ID representing the specific object. Depending on the ID, a corresponding boolean flag is toggled, indicating whether the object is selected or not. While the color rendering is generally hidden from view, it can optionally be displayed, showing each object in its unique picking color.

## Result
