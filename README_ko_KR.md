# external-release-preview

실행 `Jaby.zip.external.exe`

### 기능
- 미니언 막타 원 그리기
- 다른 챔피언과 내 챔피언 사이에 라인 그리기
- 내 챔피언의 스크린 좌표 표시

### 주의
- 10.16.330.9186 버전 대상
- fully external ReadProcessMemory
- imgui 사용
- c++로 만들어짐

### 뭘봐 시발
![](https://github.com/jaby-zip/external-release-preview/blob/master/s1.png)  
  
![](https://github.com/jaby-zip/external-release-preview/blob/master/s2.png)  
  
  
### 로드맵
- 간단한 오브워커
- 스펠 쿨다운 트래커
- 미사일 오브젝트 표기


### 왜 만들었냐
전 이미 한섭,일섭 포함한 글로벌 서버를 대상으로 커널모드에서 도는 사설 플랫폼을 운영중입니다. 근데 코드작성하기가 줫같아요. 그래서 그냥 심심해서 퍼포먼스 테스트 겸 만들어봤습니다. 요즘 C#으로 만들어진 external script가 꽤 나오더라고요. oasys나 spaceglider 같은거요.
