[![release](https://github.com/nofairTCM/NpcChat/actions/workflows/publish.yml/badge.svg)](https://github.com/nofairTCM/NpcChat/actions/workflows/publish.yml)

# NpcChat
npc 챗 부분을 담당하는 모듈입니다, https://github.com/qwreey75/RBX_UI_PROJECT 의 소스코드가 일부 포함되어 있습니다  

## 빌드하기
필요에 따라서 소스코드에서 모듈을 직접 빌드해야 할 수도 있습니다  

일단 빌드하기 위해서 이 저장소를 복사해와야 합니다. win64 기준으로 cmd 를 적합한 위치에서 연 후  
> git clone --recursive https://github.com/nofairTCM/NPC-Chat.git  
다음과 같이 입력해서 이 저장소를 복사해오세요  

그 후 복사된 폴더로 이동합니다  
> cd InstallerPlugin  
이제 cmd 창을 닫지 말고 아래 단계로 내려가세요  

일단 rojo 가 없는 경우 [rojo](https://github.com/rojo-rbx/rojo/releases) 를 받아서 지금 폴더로 옮깁니다 (압축을 푼 후)  
이제 rojo.exe 가 폴더 안에 있어야 합니다  

그런 다름 cmd 라인에서  
> rojo serve test.project.json  
를 입력하고 로블록스 플러그인(rojo) 를 받아 연결합니다  
그럼 성공적으로 모듈과 필요 라이브러리가 해당하는 루트로 설치됩니다  

주의 : 설치 관리기로 설치할 때와 설치 방식이 다르기 때문에 이 방식으로 설치 후  
설치기로 다시 설치 하려고 하면 오류를 일으킬 수 있습니다  
