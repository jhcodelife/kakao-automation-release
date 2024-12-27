# kakao-automation-release
카카오톡 자동 메시지 어플리케이션입니다.
카카오톡 PC버전이 실행중이어야 하고, PC버전을 자동화하여 메시지를 전송합니다. 

# 사용법
1. 메시지를 작성합니다. (최대 5개, 이미지 가능)
2. 보내려는 대화 상대의 대화창을 모두 열어둡니다.
3. **👉프로그램의 '열려있는 대화창' 목록이 잘 수집되었는지 꼭 확인합니다.👈**
4. '메시지 보내기'를 실행합니다.

# MacOs ([다운로드](https://github.com/jhcodelife/kakao-automation-release/blob/main/macos/KakaoMacro_v1.0.tar.gz))
다운로드 링크에서 아래처럼 다운로드 버튼을 통해 내려받기

<img width="500" alt="image" src="https://github.com/user-attachments/assets/ff200976-d8ea-4723-afd8-1361b7088674" />

## 개발자 코드 사인 필수 
1. 압축 후, 응용프로그램(Applications)으로 이동합니다.
2. 터미널에서 아래 커맨드를 사용해 코드 사이닝합니다.
```
codesign --force --deep --sign - /Applications/KakaoMacro.app
```
3. 정상적으로 동작하지 않을 시, 아래 두 권한이 부여되어 있는지 확인합니다.
   - 개인정보 및 보안 > 화면 및 시스템 녹음
   - 개인정보 및 보안 > 손쉬운 사용
![실행화면](https://github.com/jhcodelife/kakao-automation-release/blob/main/macos/kakao_screenshot_macos.gif)

# Windows ([다운로드]([https://github.com/jjhok/kakao-automation-release/tree/main/windows](https://github.com/jhcodelife/kakao-automation-release/blob/main/windows/KakaoMacro_v1.0_windows.zip)))
다운로드 링크에서 아래처럼 다운로드 버튼을 통해 내려받기

<img width="500" alt="image" src="https://github.com/user-attachments/assets/ff200976-d8ea-4723-afd8-1361b7088674" />

- 개발 환경이 없어서 충분히 테스트 되지 않았습니다. 
- 압축 후 보안 프로그램에 의해 실행파일이 삭제될 수 있습니다. 보안 설정 해제 후 사용할 수 있습니다.
- 실행화면
![실행화면](https://github.com/jhcodelife/kakao-automation-release/blob/main/windows/kakaoMacro_windows.gif)
