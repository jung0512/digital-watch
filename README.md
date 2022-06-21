# 디지털 시계
오늘은 디지털시계를 만들어 보았다.
# js 코드
![image](https://user-images.githubusercontent.com/102035198/174732049-3462a250-5310-4a18-a91d-8aa5ce7c3e56.png)<br>
id가 Time,go,stop인 객체를 각각 h1,go,stop에 저장한다<br>
![image](https://user-images.githubusercontent.com/102035198/174738692-88a7c9da-1f01-48a1-b95c-6a843622da24.png)<br>
현재 시, 분, 초를 알려주는 코드입니다<br>
시,분,초를 hour,min,sec에 저장해준다<br>
![image](https://user-images.githubusercontent.com/102035198/174738971-c6fef374-607f-4a30-a2f1-42141275da29.png)<br>
시각을 형식대로 출력해준다<br>
html파일에 있는 h1에 시간을 출력해준다<br>
![image](https://user-images.githubusercontent.com/102035198/174731621-192fc29e-3a31-4b13-83cb-015607896670.png)<br>
버튼을 눌렀을 때 시작되고 멈추는 코드입니다<br>
go버튼을 눌렀을 때 handleId를 setInterval(getTime, 1000)값을 넣어 작동시킨다<br>
stop버튼을 눌렀을 때는 handleId를 다시 0으로 초기화 시켜주어 작동을 멈춘다<br>
![image](https://user-images.githubusercontent.com/102035198/174733130-ae85bfc0-01e7-4380-aecf-8d7590cae398.png)<br>
container클래스를 text-align: center로 가운데 맞춤을 해준다<br>
clock클래스는 border를 2px로 주고 색상을 blue로 주어 파란색 테두리를 만들어줬다<br>
![image](https://user-images.githubusercontent.com/102035198/174735309-2dbc6a31-7f15-4e45-b5b5-2c84b2e3f92d.png)<br>
시간이 표시되는것을 h1태그로 만들어 주고<br>
go,stop버튼을 만들어 주었고<br>
js파일을 연결시켜주었다<br>
# 출력화면
![image](https://user-images.githubusercontent.com/102035198/174735645-8ba79232-8ca0-4d43-8e1e-7a026a3a4936.png)<br>
감사합니다
