JDK는 두개로 분류
JDK
Jre-os(Java.exe)

java가 잘 안될때는 컴파일 문제인지 실행 문제인지 알아야됨

cmd에 javac가 안되면 환경변수 변경
1. 검색에 환경변수 들어가서 시스템 변수에 JAVA_HOME추가 값은 C:\Program Files\Java\jdk1.8.0_202
2. 시스템변수 Path에 들어가서 %JAVA_HOME%\bin 추가후 맨위로 올리기
3. 기존 cmd끄고 다시 실행후 javac명령어 출력되면 성공
