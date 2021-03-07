# AutoInput-for-my-Son
python code ง่ายๆ สำหรับควบคุม Mouse และ Keyboard เนื่องจากเห็นคุณลูกเล่นเกมแล้วต้องการเก็บเลเวลด้วยการต้องคลิกเมาส์ซ้ำๆ ถึงขนาดเอาเมาส์ไปนั่งกดระหว่างที่ดูโทรทัศน์ไปด้วย คุณพ่อเลยหาวิธี Auto click ให้ จะได้ไม่เสียสุขภาพ 😁

Source code available at https://github.com/asweigart/pyautogui

Source code available at https://github.com/learncodebygaming/pydirectinput

If you need help installing Python, visit https://installpython3.com/



### Installation
You need python install on your machine 

วิธีติดตั้ง python on windows https://installpython3.com/windows/


### add-on lib
```
C:\>pip install pyautogui
C:\>pip install pydirectinput
```

### How to run

```
C:\>python autoclick.py
```


ปล. จริงๆ สามารถควบคุมการกด Keyboard ได้ด้วยนะครับลองศึกษาจากผู้พัฒนาต้นทาง หรือสอบถามที่ผมก็ได้ครับ ใครเอาไปลองแล้วมีไอเดียแจ๋วๆ มาแชร์กันได้ครับ 😆
### ตัวอย่างอื่นๆ
```
    >>> import pyautogui
    >>> import pydirectinput
    >>> pydirectinput.moveTo(100, 150) # Move the mouse to the x, y coordinates 100, 150.
    >>> pydirectinput.click() # Click the mouse at its current location.
    >>> pydirectinput.click(200, 220) # Click the mouse at the x, y coordinates 200, 220.
    >>> pydirectinput.move(None, 10)  # Move mouse 10 pixels down, that is, move the mouse relative to its current position.
    >>> pydirectinput.doubleClick() # Double click the mouse at the
    >>> pydirectinput.press('esc') # Simulate pressing the Escape key.
    >>> pydirectinput.keyDown('shift')
    >>> pydirectinput.keyUp('shift')
``` 
