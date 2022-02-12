# AutoIconChanger
서버 아이콘을 움짤처럼 바꿔주는 플러그인 입니당

![test](https://user-images.githubusercontent.com/99476164/153716713-500dacad-bef5-4d42-b0ab-a91c2846a7a9.gif)

# Config
```yaml
#이미지를 어떻게 바꿀지 정하는 곳이에요.
#INORDER_MODE: 파일이름 순서대로 서버 아이콘을 바꿔요.
#RANDOM_MODE: 랜덤으로 서버 아이콘을 바꿔요.
swapMode: INORDER_MODE

#클라이언트에게 어떻게 보여줄지 정하는 곳이에요.
#ONPING: Ping이 수신될 때마다 서버 아이콘을 변경해요.
#MILLIS_<TIME>: 시간에 도달했을 때 서버 아이콘을 변경해요. 예를 들자면 MILLIS_15000으로 설정하면 서버 아이콘을 15초마다 변경해요.
swapTime: ONPING

#콘솔에 플러그인 로그를 보여줘요.
#false 이여도 여전히 에러는 콘솔에 계속 표시되요.
consoleOutput: false
```
