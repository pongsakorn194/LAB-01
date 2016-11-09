# OOAD-LAB1

## LAB1

### สรุปผลการทดลอง

จาก code เปิดการให้แสดง MessageBox ขั้นมาว่า Hello World! This is my first win32 program! และ MB_OK คือการกด ok แล้วออก
```
#include <windows.h>

int WINAPI
WinMain(HINSTANCE hInst, HINSTANCE hPrev, LPSTR  lpCmdLine, int nCmdshow)
{
    MessageBox(NULL, "Hello World! This is my first win32 program!",
    "Lesson1", MB_OK);
    return 0;
}
```


### ตอบคำถาม
ข้อ1 ตอบ ไม่มีข้อผิดพลาด

ข้อ2 ตอบ
Code
```
#include <windows.h>

int WINAPI
WinMain(HINSTANCE hInst, HINSTANCE hPrev, LPSTR  lpCmdLine, int nCmdshow)
{
	MessageBox(NULL, "Pongsakorn", "Lesson1", MB_OKCANCEL);
	return 0;
}
```
Photo

<img src="https://github.com/pongsakorn194/LAB-01/blob/master/Homework/photo2.png?raw=true">


