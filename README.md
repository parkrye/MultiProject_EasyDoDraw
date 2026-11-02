# EasyDoDraw

그림 그리기 · 애니메이션 도구. Android 앱과 Windows PC 프로그램이 같은 기능으로 동작. EasyDo 시리즈.

## 다운로드

최신 버전 0.2.0 — [Releases](https://github.com/parkrye/MultiProject_EasyDoDraw/releases)에서 받아 설치.

| 파일 | 대상 |
|---|---|
| `EasyDoDraw-<버전>.apk` | Android 10 이상 |
| `EasyDoDraw-<버전>.exe` | Windows 설치 프로그램 |
| `EasyDoDraw-<버전>.msi` | Windows 설치 프로그램(MSI) |

- Android: 처음 설치 시 "출처를 알 수 없는 앱" 설치 허용 필요. Play 프로텍트가 검사 화면을 띄울 수 있음
- Windows: 코드 서명 없는 설치 파일이라 SmartScreen 경고가 뜰 수 있음 → `추가 정보` → `실행`
- 업데이트는 새 파일을 같은 방식으로 덮어 설치. 작품 · 설정 유지
- 앱 안 업데이트 알림 없음. `설정 → 앱 정보 → 새 버전 받기`로 이 페이지 열기
- 서명 인증서 SHA-256: `362d130ee7722a6221a18015ed1f26704b9a30dade62042a48ace31e7cd23b2a`
- 버그 · 제안은 [Issues](https://github.com/parkrye/MultiProject_EasyDoDraw/issues)에

## 기능

- **브러시**: 펜 · 연필 · 잉크 펜 · 마커 · 캘리그래피 · 에어브러시 · 수채(물감 섞기) · 크레용 · 스프레이 · 문지르기 · 흐리게 · 지우개 2종, 기본 18종(유화 붓 · 분필 · 스펀지 · 별 뿌리기 · 나뭇잎 포함) + 사용자 브러시. 크기 · 불투명도 · 흐름 · 간격 · 경도 · 모양(둥글기 · 각도 · 진행 방향 · 펜 기울기) · 지터 · 흩뿌리기 · 질감 · 시작 가늘게 · 손떨림 보정(평균 · 끈 방식)
- **브러시 팁 · 질감**: 이미지 팁(여러 장 · 순서/무작위/획 방향), 종이 질감(세기 · 크기 · 이동), 칠하기 혼합 모드
- **브러시 가져오기**: Photoshop `.abr` · Procreate `.brush` `.brushset` · 클립 스튜디오 `.sut`(썸네일 팁) · Krita `.kpp` · MyPaint `.myb` · GIMP `.gbr` `.gih` · 이미지(PNG · JPG · WEBP). 묶음 단위 관리 · 삭제
- **텍스트 레이어**: 다시 편집 가능(텍스트 도구로 누르면 편집 · 끌면 이동), 가져온 TTF · OTF 글꼴, 굵게 · 기울임, 정렬, 행간 · 자간, 세로쓰기, 외곽선. 칠하면 일반 레이어로 자동 변환. ORA 저장 시 유지
- **캔버스 프리셋**: 기본 · 화면/영상 · SNS · 인쇄(A/B 규격 · 레터 · 엽서 · 명함) · 만화/웹툰 · 아이콘/이모티콘 · 픽셀 아트 분류, px · mm · cm · inch 단위와 DPI, 내 프리셋 저장 · 삭제
- **필압**: Android 스타일러스, Windows 펜(WM_POINTER, Windows Ink 장치). 설정에서 필압 곡선 조절
- **레이어**: 그룹 · 통과 그룹 · 클리핑 · 알파 잠금 · 잠금 · 참조 레이어 · 혼합 모드 19종 · 불투명도 · 병합 · 보이는 레이어 병합 복사, 여러 레이어 선택(길게 누르기) → 그룹 · 병합 · 숨기기 · 삭제
- **레이어 마스크 · 조정 레이어**: 마스크 칠하기(흰색 보임 · 검정 숨김) · 켜기/끄기 · 적용 · 삭제, 조정 레이어 11종(밝기 · 대비 ~ 그라디언트 맵, 곡선 포함) 값 다시 편집 · 아래 레이어와 병합 시 굽기. ORA 저장 시 유지, PSD 는 픽셀로 반영
- **선택**: 사각 · 원형 · 올가미 · 다각형 · 자동 선택(허용 오차 · 참조 레이어), 더하기 · 빼기 · 교차, 흐리게 · 확장 · 축소 · 테두리 · 반전
- **채우기 · 그라디언트**: 틈 막기 · 확장 채우기, 선형 · 원형 · 각도 · 반사 · 다이아몬드 그라디언트, 반복 · 거울 반복 · 디더링, 올가미 채우기(둘러싼 영역 바로 채움)
- **도형**: 직선 · 화살표 · 곡선 · 사각형 · 둥근 사각형 · 타원 · 정다각형 · 별 · 다각형(점 찍기), 선 · 채우기 · 둘 다. 퀵셰이프: 브러시 획 끝에서 잠시 멈추면 직선 · 타원 · 다각형으로 정리(설정에서 끔)
- **색**: 색상환(색조 고리 + 채도 · 명도) · HSV · RGB · 팔레트, 색 조화(보색 · 유사색 · 삼각 · 분할 보색 · 사각), 최근 색
- **변형**: 이동 · 크기 · 회전 · 뒤집기 · 원근 · 격자 변형 · 유동화(밀기 · 비틀기 · 오목하게 · 볼록하게)
- **보조**: 대칭(좌우 · 상하 · 4분할 · 방사형), 평행 자 · 1/2/3점 투시 · 타원 자, 격자 · 격자 맞춤 · 픽셀 격자
- **필터**: 밝기 · 대비, 색조 · 채도, 레벨, 곡선, 색상 균형, 반전, 흑백, 세피아, 포스터화, 한계값, 그라디언트 맵, 가우시안 · 동작 흐림, 선명하게, 노이즈, 모자이크, 엠보스, 윤곽선 (미리보기)
- **캔버스**: 크기 · 이미지 크기(보간 선택) · 자르기 · 내용에 맞게 자르기 · 회전 · 뒤집기, 보기 확대 · 회전 · 좌우 반전
- **파일**: OpenRaster(.ora) 기본 저장, PSD 읽기 · 쓰기(레이어 · 그룹 · 혼합 모드 유지), PNG · JPG · WEBP 내보내기(배율), 이미지 가져오기 · 참조 이미지 창
- **애니메이션**: 보기 메뉴에서 켜기. 맨 위 레이어 · 그룹 = 프레임, 첫 레이어 배경 고정(선택), 어니언 스킨(앞 빨강 · 뒤 초록, 장 수 · 불투명도), 타임라인(프레임 추가 · 복제 · 선택), 1~30fps 재생, GIF · PNG 프레임 묶음(zip) 내보내기. 설정은 ORA 에 저장
- **타임랩스**: 그리는 과정 자동 기록 → GIF 내보내기
- **보기 · 기록**: 내비게이터(전체 미리보기 · 현재 화면 영역 · 눌러 이동 · 확대 슬라이더), 작업 기록 목록(눌러 그 단계로 이동)
- **입력**: 두 손가락 확대 · 회전 · 이동, 두 손가락 탭 실행 취소 · 세 손가락 탭 다시 실행, 손바닥 무시, 휠 확대 · Shift+휠 가로 이동 · 가운데 버튼 이동 · 오른쪽 클릭 스포이드
- 자동 저장, 실행 취소 단계 설정, 밝게 · 어둡게 테마, 왼손 모드
- **설정**: 필압 · 터치 · 제스처 · 저장 · `화면` / `데이터`(백업 만들기 · 백업에서 복원, zip 하나, 복원 전 확인 대화상자) / `앱 정보`
- **앱 정보**: 앱 이름 · 버전 · 개인정보 · 저작권 · 새 버전 받기 · 오픈소스 라이선스

### 키보드 단축키(PC)

| 키 | 동작 | 키 | 동작 |
|---|---|---|---|
| B / E | 브러시 / 지우개 | Ctrl+Z / Ctrl+Y | 실행 취소 / 다시 실행 |
| G / Shift+G | 채우기 / 그라디언트 | Ctrl+S | 저장 |
| I | 스포이드 | Ctrl+Shift+E | 내보내기 |
| U | 도형 | Ctrl+A / Ctrl+D | 전체 선택 / 해제 |
| M / Shift+M | 사각 / 원형 선택 | Ctrl+Shift+I | 선택 반전 |
| L / Shift+L | 올가미 / 다각형 올가미 | Ctrl+C · X · V | 복사 · 잘라내기 · 붙여넣기 |
| W / Shift+W | 자동 선택 / 유동화 | Ctrl+Shift+C | 병합 복사 |
| V / Shift+V | 이동 · 변형 / 격자 변형 | Ctrl+T | 변형 |
| T / H | 텍스트 / 손 | Ctrl+J / Ctrl+E | 레이어 복제 / 아래와 병합 |
| [ / ] | 브러시 크기 | Ctrl+G / Ctrl+Shift+G | 그룹 / 그룹 해제 |
| X / D | 색 바꾸기 / 기본 색 | Ctrl+Shift+N | 새 레이어 |
| Space+끌기 | 화면 이동 | Ctrl+0 / Ctrl+1 | 화면 맞춤 / 실제 크기 |
| Tab | 패널 숨기기 | Ctrl++ / Ctrl+- | 확대 / 축소 |
| Delete | 지우기 | Shift+R | 회전 초기화 |
| Esc / Enter | 취소 / 완료 | Alt+클릭 | 스포이드 |

## 개인정보

인터넷 권한 없음 · 광고 없음 · 수집 · 전송 없음.

- 계정 · 광고 · 사용 통계 · 오류 보고 없음
- 작품 · 설정 · 브러시 · 글꼴은 기기 안에만 저장(Android 앱 전용 폴더, Windows `%APPDATA%\EasyDoDraw`). 앱 삭제 시 함께 삭제

## EasyDo 시리즈

| 앱 | 용도 | 플랫폼 |
|---|---|---|
| [EasyDoDraw](https://github.com/parkrye/MultiProject_EasyDoDraw) | 그림 · 애니메이션 | Android · Windows |
| [EasyDoWrite](https://github.com/parkrye/AppProject_EasyDoWrite) | 소설 · 글쓰기 | Android |
| [EasyDoRead](https://github.com/parkrye/AppProject_EasyDoRead) | 책 · 문서 읽기 | Android |
| [EasyDoShelve](https://github.com/parkrye/AppProject_EasyDoShelve) | 웹 소설 서재 | Android |
| [EasyDoPhoto](https://github.com/parkrye/AppProject_EasyDoPhoto) | 카메라 · 사진 편집 | Android |
| [EasyDoDiet](https://github.com/parkrye/AppProject_EasyDoDiet) | 식단 · 운동 기록 | Android |
| [EasyDoZip](https://github.com/parkrye/AppProject_EasyDoZip) | 파일 · 압축 관리 | Android |
| [EasyDoGame](https://github.com/parkrye/AppProject_EasyDoGame) | 미니 게임 모음 | Android |
| [EasyDoMix](https://github.com/parkrye/AppProject_EasyDoMix) | 영상 · 오디오 편집 | Android |
| [EasyDoRecord](https://github.com/parkrye/AppProject_EasyDoRecord) | 녹음 | Android |
| [EasyDoStudio](https://github.com/parkrye/DesktopProject_EasyDoStudio) | 화면 녹화 · 영상 편집 | Windows |

## 라이선스

MIT License · © parkrye. 포함된 서드파티 라이브러리 라이선스는 앱 안 `설정 → 앱 정보 → 오픈소스 라이선스`에서 확인.
