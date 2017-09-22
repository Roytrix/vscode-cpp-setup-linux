Visual Studio Code c++ default setup Linux only version 
by roytrix 

Settings and folder setup for quick start of a c++ new project for gcc compiler with clang-format for intellisense.  

Folder description:  

.vscode:  
  c_cpp_properties.json: custom include to most used lib for gcc and clang to work correctly.  
  launch.json: vscode default gdb setup with path to bin folder.  
  settings.json: default vscode.  
  tasks.json: build task with gcc put the executable file in the bin folder.  
    
bin: Output executable.  

build: All object file.  

doc: Notes and documentation of project.  

include: All project header files.  

prototype: Idea testing folder to keep them if needed later but to not polute the project.  

src: The application sources files.  

test: All test code files.  




