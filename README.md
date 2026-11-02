# 배포 전용 저장소

sunghoon219-kor의 프로그램 설치 파일을 나눠 주는 곳입니다. **소스 코드는 여기 없습니다.**

| 프로그램 | 새 판 정보 | 설치 파일 |
|---|---|---|
| rmt 원격 데스크톱 | [rmt/latest.json](rmt/latest.json) | [릴리즈 rmt-v…](https://github.com/sunghoon219-kor/releases/releases) |
| ClaudeBook (Claude Code 세션 관리·대화) | [claudebook/latest.json](claudebook/latest.json) | [릴리즈 claudebook-v…](https://github.com/sunghoon219-kor/releases/releases) |

- 프로그램은 `<이름>/latest.json`을 읽어 새 판을 알고, 릴리즈에서 설치 파일을 받습니다.
- `latest.json`의 `signature`는 배포 PC에만 있는 키로 서명한 값입니다. 앱은 서명과 SHA-256이 맞을 때만 설치하므로, 이 저장소의 파일이 바뀌어도 서명이 맞지 않으면 설치되지 않습니다.
- 올리기는 배포 스크립트(D:\Deploy\deploy.ps1)가 합니다. 손으로 고치지 마세요.