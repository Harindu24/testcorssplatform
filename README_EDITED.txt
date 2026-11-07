Download the zip file and extract it
Download the CMake and install it from https://cmake.org/download/
Download the OpenCV and install it : -
    For windows : - https://opencv.org/releases/
    For Mac OS  :- brew install opencv (Open Homebrew and paste this command)
    For linux(Ubuntu/Debian) : - sudo apt install libopencv-dev (Open the terminal and paste this command)
    For linux(Arch) : - sudo pacman -S opencv (Open the terminal and paste this command)
Open the extracted file --> open CMakeLists.txt :-
    Replace the extracted folder name to "Replace_me" and save it.
Create a folder and name it as "build" .
Open the build folder --> right click and select Option "Open Terminal/CMD/Powershell here"

Then run these commands: (Mac os and Linux) -
    " cmake .. "
    " make "
Then run these commands: (Windows) -
    " cmake --build ."
Then open the application in the build folder.

Look inside the build folder replaced_name_in_fourth_step.exe / replaced_name_in_fourth_step and double click it .
