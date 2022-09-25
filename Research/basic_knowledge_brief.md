# 기본 개념

## 환경변수
> %변수명% 이러한 형식을 가지고 있다.  

환경 변수는 컴퓨터를 사용할 때 치환해서 사용할 수 있게 해주는 동적 이름값을 의미한다.  
환경 변수에는 윈도우가 설치된 경로, 임시 폴더, 특정 프로그램이 설치된 경로나 사용자 계정명 등이 포함되어 있어서 특정 폴더나 계정명에 접근할 때 치환해서 사용할 수 있다.  
> 폴더에 접근함에 있어 변수 값을 설정 해주면 편리하게 접근할 수 있다. 한 마디로 shortcut이라고 생각하면 된다.
- 대표적인 환경 변수
  - %SystemDrive% : C:\
  - %SystemRoot% : C:\Windows

## Ubuntu
다양한 Linux의 배포판 중 하나 (데스크톱 버전은 개인용 컴퓨터에 적합하다.)

## Unix
주로 서버용 컴퓨터에서 사용되는 운영체제로 아래와 같은 특징이 있다.
- 다중 사용자, 다중 작업을 지원한다.
- 트리구조의 파일 시스템을 가지고 있습니다.

## SSH
- Secure Shell의 줄임말로, 원격 호스트에 접속하기 위해 사용되는 보안 프로토콜이다.  
- SSH를 구성하는 가장 핵심적인 키워드는 'key(키, 열쇠)'입니다. 사용자(클라이언트)와 서버(호스트)는 각각의 키를 보유하고 있으며, 이 키를 이용해 연결 상대를 인증하고 안전하게 데이터를 주고 받게 됩니다.
- key의 구성방식에는 크게 비대칭키 방식 대칭키 방식이 있습니다.

## Reference
- [Reference](https://rootblog.tistory.com/225)
- [Reference](https://coding-factory.tistory.com/315)
- [Reference](https://library.gabia.com/contents/infrahosting/9002/#:~:text=SSH%EB%A5%BC%20%EA%B5%AC%EC%84%B1%ED%95%98%EB%8A%94%20%EA%B0%80%EC%9E%A5,%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EC%A3%BC%EA%B3%A0%20%EB%B0%9B%EA%B2%8C%20%EB%90%A9%EB%8B%88%EB%8B%A4.)