## Ada-Win32
### Ada bindings for Win32 - Generated from the win32 metadata

https://github.com/microsoft/win32metadata

### Prerequisites

You will need a working gcc/gnat **x64** Windows build environment. This release is **NOT** intended
to be used for 32 bit environments. You may need to build gcc/gnat **x64** from source if required.
Details/scripts on how to do this can be found on the mingw64 website, alternatively install using MSYS2.

### Project Status

v 1.0 Released

### Build instructions

  #### Notes
  This binding is supplied as a single source file (approx 35Mb in size and ~1m lines of code) The reason is due to the cyclic dependencies in mapping a metadata Namespace -> Ada package and flattening the heirarchy is currently seen as the most appropriate solution.
  
  Do **NOT** try and view/edit the source in IDE's that support intellisence as the file size will/may cause the IDE to become unresponsive due to the time to parse the file for colorization and syntax checking purposes.
  
  #### Instructions
  
  To build run **gprbuild -p -P Win32_ada.gpr**
  
  To install run **gprinstall -p -P Win32_ada.gpr**

### Examples

  tba

### Feedback

Welcome
