# Easy2Paper

논문 전용 PDF 뷰어 Easy2Paper의 설치 파일을 배포하는 저장소입니다.
논문 PDF를 열면 번역·요약·도표 해석까지 한 화면에서 할 수 있습니다.

## 최신 버전 받기

| 기기 | 설치 파일 |
| --- | --- |
| Windows 10 · 11 | [Easy2Paper-Windows-Setup.exe](https://github.com/hanjw0126/E2P_Release/releases/latest/download/Easy2Paper-Windows-Setup.exe) |
| macOS (Apple 실리콘) | [Easy2Paper-macOS.dmg](https://github.com/hanjw0126/E2P_Release/releases/latest/download/Easy2Paper-macOS.dmg) |
| Linux | [Easy2Paper-Linux.AppImage](https://github.com/hanjw0126/E2P_Release/releases/latest/download/Easy2Paper-Linux.AppImage) |
| Android | [Easy2Paper-Android.apk](https://github.com/hanjw0126/E2P_Release/releases/latest/download/Easy2Paper-Android.apk) |

위 링크는 항상 가장 최근 버전을 가리킵니다. 이전 버전은 [Releases](https://github.com/hanjw0126/E2P_Release/releases)에서 볼 수 있습니다.

## 처음 실행할 때

아직 개발자 서명이 없어 처음 한 번 보안 경고가 뜹니다.

- **Windows**: "Windows의 PC 보호" 창에서 **추가 정보 → 실행**
- **macOS**: "손상되었기 때문에 열 수 없습니다"가 뜨면 터미널에서 `xattr -cr /Applications/Easy2Paper.app`
- **Linux**: `chmod +x Easy2Paper-Linux.AppImage` 후 실행
- **Android**: 브라우저·파일 앱의 "출처를 알 수 없는 앱 설치" 허용

PDF 보기·목차·형광펜·서재는 로그인 없이 무료로 쓰고, 번역·요약 같은 AI 기능은 앱 오른쪽 위에서 로그인한 뒤 토큰으로 씁니다.

이 저장소에는 설치 파일만 올라오며, 릴리즈는 자동으로 만들어집니다.
