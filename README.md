### pyopengl
---
https://github.com/mcfletch/pyopengl

http://pyopengl.sourceforge.net/

```py
// tests/test_err_check_extension_check.py
import OpenGL
OpenGL.ERROR_CHECKING = False
OpenGL.USE_ACCELLERATE = False

from OpenGL.GLUT import *

def reshape(width, height): pass
def display(): glutSwapBuffers()

def main():
  glutInit([])
  glutInitDisplayMode(GLUT_RGBA|GLUT_3_2_CORE_PROFILE)
  glutCreateWindow(b"test")
  glutReshapeFunc(reshape)
  glutDisplayFunc(display)

  from OpenGL.GL = import glGenVertextArrays, glVertex3f
  assert bool(glGenVertexArrays)
  try:
    if fgDeinitialize: fgDeinitialize(False)
  except NameError as err:
    pass

if __name__ == "__main__":
  main()
```

```
```

```
```


