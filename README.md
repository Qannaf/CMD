# CMD Command

* THE BASIC COMMANDS OF CMD
````
cls         to erase all the contents of the console
echo        to write a text on the command prompt
date        to change the system date
print       to allows to print file
time        to can change the system time
exit        to close the command prompt
````


* Create file
````
mkdir newfile
````
* Create file and write 
````
echo "# Now I write in side README file :)" >> README.md
````

* Folder tree structure
````
tree /f
````

* Show file in folder 
````
ls    or    dir       or ls .. for floder-1
````

* SHUTDOWN PC
````
shutdown /s              to shutdown
shutdown -s -f -t 3600   to shutdown after 1 hour
shutdown /r              to restart
shutdown /o /r           to call Windows recovery
````

* Ip configuration
````
ipconfig  or  ipconfig /all
````

* Information of  system
````
systeminfo
````

* Clear DNS resolution cache 
````
ipconfig /flushdns
````

* Build project with CMake and Visual studion 16 2019
````
cmake -G "Visual Studio 16 2019" -A "x64" cd ..
````

* Environment variables
```
setx MyVariable_DIR "C:\myFolder"         to show message 
            or
set MyVariable_DIR "C:\myFolder"

setx Path "%Path%; %MyVariable_DIR%\bin"       to add variable to Path 
```


* Quit cmd
````
exit
````


## Path
```
setx Path "%USERPROFILE%\AppData\Local\Microsoft\WindowsApps;C:\opencv-4.5.1\build\x64\vc15\bin;C:\Program Files\Git\bin;C:\Program Files\Git\cmd;C:\Program Files\PCL 1.11.1\bin;C:\Program Files\OpenNI2\Redist;%PCL_ROOT%\bin;%PCL_ROOT%\3rdParty\FLANN\bin;%PCL_ROOT%\3rdParty\Qhull\bin;%OPENNI2_REDIST64%;C:\Program Files\OpenNI2\Tools;%PCL_ROOT%\3rdParty\Boost\lib;%USERPROFILE%\.dotnet\tools;C:\Utilisateurs\qannaf.as\AppData\Local\Programs\Microsoft VS Code\bin;%PCL_ROOT%\3rdParty\VTK\bin;%FLANN_ROOT%\bin;C:\Program Files\VTK\bin;"
```

## Delete folder
```
rmdir nameFolder        or          rm nameFolder           or          del nameFolder
```
