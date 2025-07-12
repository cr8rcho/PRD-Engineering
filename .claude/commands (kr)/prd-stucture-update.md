# [+파일명] 서비스 설계 업데이트

## 기능 파일: $ARGUMENTS

기능 파일에 입력된 정보를 바탕으로 기존에 설계되어있는 /prd_screens 내부에 있는 구조를 기능 파일의 내용 기반으로 화면 구조를 업데이트 설게합니다. 철저한 리서치를 기반으로 작성하며, AI 에이전트가 자체 검증과 반복 개선을 수행할 수 있도록 문맥 정보를 충분히 포함시켜야 합니다.
만들려는 서비스에 대한 일반적인 화면 구조를 먼저 생성하고, 다시 검증하고, 화면 간의 구성이 잘 이루어지도록 합니다.
추가로 필요한 화면들이 있다면 추가로 구성합니다.

## 출력

화면의 구성에 따라 독립적인 md 파일을 생성하고, prd-screens 폴더를 하위에 화면의 hierarchy 에 따라 파일 생성

예제:
prd-screens/home/home.md
prd-screens/home/signin/login.md
prd-screens/home/signup/singup.md
