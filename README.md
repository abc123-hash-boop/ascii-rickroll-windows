# ascii-rickroll-windows
## Rickroll in Windows Terminal!
### You need a C++ compiler, like ``` g++ ```
If you are using Windows 10/11, run:
```powershell
winget install -e --id Microsoft.VisualStudio.2022.BuildTools
```
If you installed Visual Studio, skip this step
### Before Compile
Open ``` x64 Native Tools Command Prompt for VS 2019 ```
Make sure you have ``` g++ ```
```cmd
C:\Program Files (x86)\Microsoft Visual Studio\2019\Community>g++
g++: fatal error: no input files
compilation terminated.
```
Change dir to source code.
### Compile
now, paste compile command.
This may working on 64-bit computers.
```cmd
g++ -o rickroll.exe rickroll.cpp
```

<img width="1460" height="997" alt="image" src="https://github.com/user-attachments/assets/3bc17e26-f1f6-4569-96f5-098526610b0f" />
### Run
Now, you can run the file, I hope this is helpful.
```cmd
start rickroll.exe
```
<img width="2000" height="1186" alt="image" src="https://github.com/user-attachments/assets/af9efbbe-1010-4ea0-bca8-1e7c7730ad46" />
