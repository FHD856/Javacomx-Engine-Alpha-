PLEASE NOTE THAT THIS IS ALPHA AND NOT THE FINAL VERSION
This editior has some features like a AI tool in case you can't figue out the commands,
Here are the Commands from the website itself:

na = NAME  —  Defines a new object with the given NAME. Following exte/fi/.pos lines attach to it.
  exte = EXTENSION  —  Sets the current object's extension label (literally a string like ent, dev, wld). NOT an entity type.
  fi = FILE  —  Sets the file or model associated with the current object (example: sun_light.obj).
  OBJECT.pos = xNUM*yNUM*zNUM  —  Sets the 3D position of an object. Format is ALWAYS x<number>*y<number>*z<number>.
  OBJECT.lightstr = NUM  —  Sets the light strength of an object (1-10).
  OBJECT.lightfall = NUM  —  Sets the light falloff multiplier used by the dynamic lighting formula.
  prog NAME  —  Defines a program with the given NAME.
  progmprop = timfore  —  'time forever' — marks the most recent program to run continuously in a loop.
  run NAME on world  —  Executes a program on the world. If timfore is set, it loops forever.
  combi diag CMD_A | CMD_B  —  COMBI module: runs commands diagonally/combined. Use 'combi diag a | b' or 'combi run a && b'.
  help [command]  —  Lists all commands, or explains one command in detail.
  load default  —  Loads the built-in default Javacomx script.
  gui  —  Switch to GUI mode.
  cli  —  Switch to CLI mode.
  clear  —  Clears the console output.
  pixden = NUM  —  Sets the world pixel density (grid resolution). Valid values: 8, 16, 24, 32, 48. Default is 24.
  cam = NAME  —  Switches the active camera to a named camera object. The camera must be defined with na = NAME and exte = cam.
  OBJECT.rot = xNUM*yNUM*zNUM  —  Sets the rotation of an object in degrees on each axis. Format: x<deg>*y<deg>*z<deg>.
  OBJECT.scale = NUM  —  Sets the uniform scale factor of an object. Default is 1.0.
  OBJECT.visible = true|false  —  Shows or hides an object in the world view.
  OBJECT.tag = LABEL  —  Assigns a string tag/label to an object for grouping or identification.
  stop NAME  —  Stops a running program by name. Halts its timfore loop if active.
  del NAME  —  Deletes an object from the world by name.
  list objects|programs  —  Prints all loaded objects or programs to the console.

Thank you for helping out by forking or going to the website i'll include here: https://java-comx-core.base44.app
Yes this is a base44 app so you don't need to download it to modify it.
