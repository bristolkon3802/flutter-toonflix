# toonflix

### 설치

- flutter create toonflix
- toonflix/code .

### 추가 마켓플레이스

- Dart
- Flutter
- Error Lens

### vscode settings
- 설정 > open user settings > "source.fixAll": true

### Tools 정의

- Row 의 CrossAxis 는 세로 방향, Row 에서는 가로가 Main
  crossAxisAlignment: CrossAxisAlignment.start, 처음으로 정렬
  crossAxisAlignment: CrossAxisAlignment.end, 밑으로 정렬
  mainAxisAlignment: MainAxisAlignment.spaceBetween, 양옆 센터정렬
  clipBehavior: Clip.hardEdge, icon 이 박스 밖으로 넘쳐흐를경우 튀어나온거 히든 처리
- Column 의 CrossAxis 는 가로 방향, Column 에서는 세로가 Main
- SizedBox => size 가 있는 box 를 만들어 줌
- Colors.white.withOpacity(0.8)
- Color(0xFF181818) / Color.fromRGBO(255, 255, 255, 0.8)
- Text('Hello Word',style: TextStyle(color: Colors.white,fontSize: 28,fontWeight: FontWeight.w800))
- Container(decoration: BoxDecoration(color: Colors.amber,), //위아래 15, 왼쪽오른쪽 40
    child: Padding(padding: EdgeInsets.symmetric(vertical: 15, horizontal: 40), child: Text('Transfer'),),
  )





