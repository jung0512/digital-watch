# 디지털 시계
오늘은 디지털시계를 만들어 보았다.
# js 코드
![image](https://user-images.githubusercontent.com/102035198/174732049-3462a250-5310-4a18-a91d-8aa5ce7c3e56.png)<br>
handleId를 0으로 초기화 시켜줬다.<br>
html 코드에서 지정한 id를 불러 온다<br>
![image](https://user-images.githubusercontent.com/102035198/174731141-6c5cbb32-f2b8-4e61-bfff-ec78a6b3e8b6.png)<br>
현재 시, 분, 초를 알려주는 코드입니다<br>
![image](https://user-images.githubusercontent.com/102035198/174731621-192fc29e-3a31-4b13-83cb-015607896670.png)<br>
버튼을 눌렀을 때 시작되고 멈추는 코드입니다<br>
go버튼을 눌렀을 때 handleId를 setInterval(getTime, 1000)값을 넣어 시작시킨다<br>
stop버튼을 눌렀을 때는 handleId를 다시 0으로 초기화 시켜주어 작동을 멈춘다<br>
![image](https://user-images.githubusercontent.com/102035198/174733130-ae85bfc0-01e7-4380-aecf-8d7590cae398.png)<br>
text-align: center로 가운데 맞춤을 해준 다음 border를 2px로 테두리를 만들어준다<br>
![image](https://user-images.githubusercontent.com/102035198/174735309-2dbc6a31-7f15-4e45-b5b5-2c84b2e3f92d.png)<br>
시간이 표시되는것을 h1태그로 만들어 주고<br>
go,stop버튼을 만들어 주었고<br>
js파일을 연결시켜주었다<br>
# 출력화면
![image](https://user-images.githubusercontent.com/102035198/174735645-8ba79232-8ca0-4d43-8e1e-7a026a3a4936.png)
