장점:  
1. CSS 파일 오픈할 필요없이 JS 파일에서 바로 스타일넣을 수 있다.  
2. 여기 적은 스타일이 다른 JS 파일로 오염되지 않는다. 원래 그냥 CSS파일은 오염됩니다.  
3. 페이지 로딩시간 단축
4. props로 재활용가능
```
`${ props => props.bg }` 
```
단점:  
1. JS 파일이 매우 복잡해짐.그리고 이 컴포넌트가 styled 인지 아니면 일반 컴포넌트인지 구분도 어렵다.
2. JS 파일 간 중복 디자인이 많이 필요할때 결국 다른 파일에서 스타일 넣은 것들 import 해와서 써야한다.그러면 CSS파일 쓰는것과 큰 차이는 없다. 