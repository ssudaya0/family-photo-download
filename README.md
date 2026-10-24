# 가족 사진 정리 (Windows)

MYBOX에 있는 가족 사진을 **사람별로 정리**해 주는 프로그램입니다. 받아서 설치할 것은 세 가지이고, ChatGPT를 먼저 설치해 아래 안내 글을 붙여 넣으면 나머지는 ChatGPT가 한 단계씩 알려 줍니다.

- 사진은 읽기만 합니다. 원래 사진은 바뀌거나 지워지지 않습니다.
- 모든 일은 이 컴퓨터 안에서만 합니다. 사진을 인터넷 어디로도 보내지 않습니다.

## 1. 받아서 설치할 것

| 순서 | 받을 것 | 링크 | 설치하고 할 일 |
| --- | --- | --- | --- |
| 1 | ChatGPT | [Microsoft Store](https://apps.microsoft.com/detail/9plm9xgg6vks?hl=ko-KR&gl=KR) | 로그인 |
| 2 | MYBOX 탐색기 (Windows 10 64bit 이상) | [MYBOXInstaller.exe](https://appdown.pstatic.net/naver/mybox/installer/MYBOXInstaller.exe) | **다음** → **설치** → **NAVER 로그인**. 파일 탐색기에 MYBOX (N:)가 생깁니다 |
| 3 | 가족 사진 정리 | [person_cluster.zip](https://github.com/ssudaya0/family-photo-download/releases/latest/download/person_cluster.zip) | 바탕 화면에 **모두 압축 풀기** → **start.bat** 실행 (보안 경고는 **추가 정보 → 실행**). 처음 한 번 5~15분 |

## 2. ChatGPT에 붙여 넣을 안내 글

막힌 화면은 **Windows + Shift + S**로 찍어 ChatGPT에 **Ctrl + V**로 붙이면 무엇을 누를지 알려 줍니다.

```text
아래 '가족 사진 정리' 설치 안내를 한 단계씩 같이 해 주세요. 제가 "다 했어요"라고 하면 다음 단계를 알려 주고, 화면 사진을 붙이면 무엇을 눌러야 하는지 알려 주세요.

[받을 것]
1. MYBOX 탐색기: https://appdown.pstatic.net/naver/mybox/installer/MYBOXInstaller.exe 실행 → 다음 → 설치 → NAVER 로그인. 파일 탐색기에 MYBOX (N:) 드라이브가 생긴다.
2. 가족 사진 정리: https://github.com/ssudaya0/family-photo-download/releases/latest/download/person_cluster.zip 를 받아 바탕 화면에 '모두 압축 풀기'.

[실행]
3. person_cluster 폴더의 start.bat 실행. 'Windows에서 PC를 보호했습니다'가 나오면 '추가 정보' → '실행'. 처음에는 Python·패키지·얼굴 모델을 받느라 5~15분 걸리고, 검은 창은 닫으면 안 된다.
4. 앱에서 '폴더 선택…' → MYBOX (N:)의 가족 사진 폴더 → '이 폴더로 시작하기'.
5. '이름 붙이기' 탭: 다른 사람 얼굴은 눌러 체크 해제, 이름 입력, '선택한 ○개에 이름 저장'. '사진 보기' 탭: 사람 이름으로 거르고 ZIP으로 저장.
주의: person_cluster 폴더를 지우면 붙인 이름이 사라진다.
```

## 3. 사용 설명서

## 📖 [가족 사진 정리 사용 설명서 (MANUAL.md)](MANUAL.md)

설치, 화면 구성, 이름 붙이기, 사진 보기와 저장(ZIP·인물별 폴더), 인물 관리, 설정, 문제 해결까지 실제 화면 그림과 함께 정리했습니다. 문제가 생기면 [9장 문제 해결](MANUAL.md#9장-문제-해결)을 보세요.

- person_cluster 폴더는 지우지 마세요. 붙인 이름이 안의 data 폴더에 저장됩니다.
- 새 버전은 같은 링크로 받아 기존 person_cluster 폴더에 덮어쓰면 됩니다.

그림 속 사진과 이름은 설명을 위해 만든 가짜입니다. MYBOX 설치 파일 링크는 [MYBOX 공식 다운로드 페이지](https://mybox.naver.com/about/explorer-guide/win)의 [다운로드 Win x64] 버튼과 같은 주소입니다.
