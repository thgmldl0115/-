```
flask : template 폴더와 static 폴더 규칙만 유의 
template : 화면에 사용될 html문서넣기
static : template 에서 include될 css, js, images
(pdf 파일 확인할것)

app.run : 서버 기동

pip install flask

디폴트 포트 지정 5000, 로컬.

coin.html 
{% extends 'top.html' %} : include와 유사

main.js
let url = "http://192.168.0.12:5500/coin"
는 flask 포트번호여야함
```
