# React
React를 공부한 것을 기록합니다.



- context란 ?


  ![image](https://user-images.githubusercontent.com/79883776/206171967-259391f0-77a9-4b21-bebe-e06b5f75a6e4.png)
  
  
  컴포넌트 트리에서 두 컴포넌트에서 상태값을 공유해야 된다면?
  
  state를 가장 근접한 부모 컴포넌트로 올린다.
  
  그리고 props로 전달한다.
  
  ![image](https://user-images.githubusercontent.com/79883776/206172300-5c4d6040-eb68-4165-b7ec-0b41e04ca3a1.png)
  
  - 만약 제일 말단에 잇을때는 계속 props를 아래까지 전달해야 한다 => 비효율적이다.
    즉, 모든 컴포넌트들이 필요하다면 어플리케이션 전박적으로 필요한 경우에 Context API를 사용할 수 있다.
    언어, 테마 (다크모드), Login
    그래서 자주 Context API를 사용한 것들이 바뀌면 re-rendering 된다. => 그래서 빈번히 업데이트가 되는 상태는 X
  
  ![image](https://user-images.githubusercontent.com/79883776/206172985-c0e9b7a9-a71a-4310-ab13-b11673a47fc7.png)
  
  
 엄브렐라
