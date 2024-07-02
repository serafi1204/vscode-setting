## Installation
1. Install [visual studio code](https://code.visualstudio.com/download).
2. Install C++ extention
   - Navigate to the "Extension" sidebar.
   - Install "C/C++ Extension Pack".
4. Install [mingw](https://sourceforge.net/projects/mingw/). ([referance](https://m.blog.naver.com/dorergiverny/223032334186))
   - Default installation Directory: C:/mingw64  
5. Unzip [workspace.zip](https://github.com/serafi1204/vscode-setting/blob/main/C%2B%2B/workspace.zip) to your desired folder.
6. Open the extracted workspace folder in Visual Studio Code.
7. Run "main.cpp"
    - Open main.cpp in workspace.
    - Navigate to the "Run and Debug" sidebar.
    - Select the "(gdb) Launch" configuration
    - Debugging and check the output to ensure it displays "Hello world!".

## if doesn't work.
1. Check g++ path in "workspace/.vscode/task.json" at line 15.
2. Ensure the MinGW environment variable is correctly set.
2. Make sure to select "main.cpp". It debug with opened file.
