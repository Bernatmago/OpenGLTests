# OpenGLTests

Based on The Cherno OpenGL series on youtube: https://thecherno.com/opengl

**Note:** Build on x86

Project dependencies (included):
- GLFW https://www.glfw.org/
- GLEW http://glew.sourceforge.net/
- GLM https://github.com/g-truc/glm
- Imgui https://github.com/ocornut/imgui
- Stb-Image https://github.com/nothings/stb/blob/master/stb_image.h

## How to add a new test
1. Extend test Class and define all the necessary steps on each method
2. Add the test on ``` Application.cpp ``` using ``` testMenu->RegisterTest<test::TestClass>("Test Name"); ```

