# pip 指令全記錄

- 安裝套件： 可以將 flask 換成任何想安裝的 Python 套件
```
pip install flask
```
- 更新套件：
```
pip install -U flask
```
- 移除安裝過的套件：
```
pip uninstall flask
```
- 安裝並且指定套件版本：
```
pip install -v flask==1.0
```
- 查看目前安裝過的清單：
```
pip list
```
- pip 安裝 requirements.txt 內的清單(一次安裝多個套件)：
```
pip install -r requirements.txt 
```
- 將安裝過的套件建立成 requirements.txt 文件清單：
```
pip freeze > requirements.txt
```