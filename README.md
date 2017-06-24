# project

## 프로그램설치

1. nginx-1.12.0 (nginx.org > download > nginx/Windows-1.12.0)
2. nssm 2.24 (nssm.cc > Download > nssm 2.24)
3. 7-zip (7-zip.org > Download 64-bit x64) -> install
4. C:\hanbit-node 아래에 압축풀기(7-zip 으로 각각 여기에 압축풀기) nginx, nssm

## nginx 서비스등록

1. C:\hanbit-node\nssm-2.24\win64 에서 nssm install nginx 실행
2. Path: C:\hanbit-node\nginx-1.12.0\nginx.exe 선택
3. Install service 버튼 클릭
4. 콘솔에서 services.msc 실행
5. nginx 시작

## 프로젝트 생성

1. WebStorm 실행
2. File -> New -> Project -> Angular CLI -> C:\hanbit-node\project-client (This Window)
3. File -> New -> Project -> Node.js Express App -> C:\hanbit-node\project-server (New Window)
