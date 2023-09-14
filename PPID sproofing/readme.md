# bof化断链实现PPID sproofing

正常情况下启动的进程其父进程为explorer.exe

![图片](https://github.com/ziansec/Snake/assets/81213597/714db7cd-bdf1-462e-9af8-b96369e2b83c)

通过断链让其父进程为本身

![图片](https://github.com/ziansec/Snake/assets/81213597/770c7375-5d22-4770-b60c-a13ebf7ff6a7)

# 用法

```c++
COM_CreateProcess <path>
EG:COM_CreateProcess C:\windows\system32\notepad.exe
```
