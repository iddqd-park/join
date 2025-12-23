# Q Join

[English](./README.md)

순수 클라이언트 기반의 이미지 이어붙이기 도구입니다. 여러 장의 PNG 또는 JPG 이미지를 드래그 앤 드롭하면, 파일명 순서대로 자동 정렬하여 세로로 길게 이어붙입니다. 서버 전송 없이 브라우저에서 즉시 처리되며, 결과물은 PNG나 JPG로 다운로드할 수 있습니다. 웹툰, 스크린샷 정리 등에 유용합니다.

# Our Philosophy
IDDQD Internet은 별도의 DB나 회원가입 없이, 순수 HTML/JS만으로 브라우저에서 즉시 실행되는 도구를 개발합니다. AI 기능을 제공할 때도 데이터 상태를 유지하지 않으며(stateless), 어떠한 기록도 남기지 않는 원칙을 고수합니다.

# Link
- [Q Join 실행하기](https://app.iddqd.kr/join/)
*(브라우저에서 즉시 실행됩니다)*

# Splash
![Splash](splash.jpeg)

# Features
- **세로 이어붙이기**: 여러 이미지를 하나의 긴 이미지로 합칩니다.
- **스마트 정렬**: 파일명에 포함된 숫자를 인식하여 올바른 로케일 순서(예: 1.png, 2.png, 10.png)로 자동 정렬합니다.
- **프라이버시 보호**: 모든 이미지는 브라우저 내부의 HTML5 Canvas에서 처리되며, 서버로 업로드되지 않습니다.
- **다양한 포맷**: 결과물을 무손실 PNG 또는 용량 최적화된 JPG(품질 80/100)로 저장할 수 있습니다.
- **편리한 UI**: 드래그 앤 드롭 및 다중 파일 선택을 지원합니다.

# Usage
1. 웹 브라우저에서 앱을 엽니다.
2. 이미지를 드롭존에 드래그하거나 **파일 선택하기** 버튼을 눌러 추가합니다.
3. 왼쪽 목록에서 파일 순서가 맞는지 확인합니다.
4. **이미지 합치기** 버튼을 누릅니다.
5. 미리보기를 확인하고 원하는 포맷(**PNG**, **JPG 80**, **JPG 100**)으로 다운로드합니다.

# Tech Stack
- **Core**: HTML5, CSS3, JavaScript (ES6+)
- **Libraries**: jQuery 3.7.1, Bootstrap 5.3.3
- **Rendering**: HTML5 Canvas API를 사용한 이미지 처리

# Contact & Author
박실장
- IDDQD 인터넷 e-솔루션 및 e-게임 사업부 개발실장
- 기습코딩꾼 & 최상무의 모사꾼
- 홈페이지: https://iddqd.kr/
- 깃허브: https://github.com/iddqd-park
