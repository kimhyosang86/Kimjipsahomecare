김집사 홈케어 홈페이지

파일 구성
- index.html : 고객용 홈페이지
- admin.html : 휴대폰 관리자 페이지
- content.json : 사진/영상/글/링크 목록
- fixed-design.png : 고정 메인 디자인

관리자 사용법
1. 홈페이지 맨 아래 '관리자 페이지'를 누릅니다.
2. 처음 한 번만 GitHub Fine-grained Personal Access Token(연결키)을 입력해 '이 휴대폰에 연결하기'를 누릅니다.
3. 이후 같은 휴대폰/브라우저에서는 GitHub에 들어가지 않고 관리자 페이지에서 사진, 영상, 글을 바로 올립니다.
4. 공용 기기에서는 '이 휴대폰 연결 해제'를 누릅니다.

중요
- 연결키는 홈페이지 파일에 저장되지 않고 해당 휴대폰 브라우저의 localStorage에만 저장됩니다.
- 토큰은 kimhyosang86/Kimjipsahomecare 저장소 하나만 선택하고 Contents: Read and write 권한만 주는 Fine-grained token을 권장합니다.
