# RE:ESG 마음정원 v1.9.1 · RE:ESG Mind Garden

아마도랩에서 운영하는 무료 웹게임 체험판입니다. 이 ZIP을 풀어 `index.html`이 있는 배포 폴더에 내용을 올립니다. 같은 사이트 주소와 브라우저를 쓰면 이전 정원 기록을 계속 사용할 수 있습니다.

## 한국어 / English

- `index.html` — 한국어판, `en.html` — 영문판(English). 두 화면 모두 상단 오른쪽의 **한국어 | English** 버튼으로 언어를 바꿀 수 있습니다.
- 마지막으로 고른 언어는 브라우저에 기억됩니다. 영문을 고른 뒤 사이트 첫 주소로 다시 오면 `en.html`이 열립니다. 한국어판을 바로 열려면 `index.html?lang=ko`를 사용하세요.
- 한국어판과 영문판의 정원 기록은 **서로 따로 저장**됩니다. 한쪽에서 쌓은 정원·마음 기록이 다른 언어판에 섞이거나 덮어써지지 않습니다.
- 영문판의 무료 7일 기록지는 영문 PDF(`assets/free-week-en-*.pdf`)로 연결됩니다.
- 하루가 바뀌는 기준과 공개 마음광장의 날짜는 두 언어 모두 한국 시간입니다. 공개 마음광장을 열면 두 언어판의 글이 같은 광장에 함께 보입니다.

English: `en.html` is the English edition. Use the **한국어 | English** switch at the top right of either page. The last choice is remembered; open `index.html?lang=ko` to go straight to Korean. Korean and English gardens are saved separately in the browser, so they never overwrite each other. Game days follow Korea time (KST).

## 공개 마음광장과 기록

공개 마음광장은 기본적으로 닫혀 있습니다. 게임과 **내 기기 마음 연습장**은 로그인 없이 이용할 수 있습니다. 운영자가 Firebase 웹 설정과 Google 로그인, Firestore 규칙·인덱스를 준비한 뒤 `plaza-config.json`을 설정하면 공개 광장이 열립니다. 공개 글·댓글은 누구나 읽을 수 있으며, 직접 게시하거나 신고하려면 Google 로그인이 필요합니다.

정원과 개인 기록은 브라우저에 저장됩니다. 공개 글·댓글은 공개 문서 주소의 Firebase 사용자 식별자(UID)를 통해 같은 계정이 쓴 기록끼리 연결될 수 있습니다. 광장 문장에는 이름·연락처·주소·다른 사람의 신상 정보를 올리지 마세요.

캐릭터, 정원 이미지, 질문, 문장, 무료 기록지는 아마도랩의 권리에 따릅니다. 무료 체험 제공은 이 자료의 재배포·개작 허가를 부여하지 않습니다. 외부 음원, 글꼴과 Firebase SDK의 출처 및 라이선스는 `licenses/`에서 볼 수 있습니다.

1.9.1부터 JSON 백업은 작성 언어를 표시합니다. 이전 백업은 작성 언어를 직접 선택한 뒤 복원하세요. 다른 언어판의 백업은 해당 언어판에서 다시 선택합니다. 운영자는 공개 광장 활성화 전에 소스 ZIP의 1.9.1 Firestore 규칙을 적용하세요.
