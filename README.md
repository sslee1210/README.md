## 230823 ##
1. 로컬 저장소 ex생성
$ git init
`code($ git init)`

2.README.md 파일 생성
$ touch README.md
$ git add .
$ git commit -m " "

3.온라인 저장소 생성
$ git remote add origin https://github.com/sslee1210/README.md.git

4.ReadME.md 파일 온라인 저장소 업로드
$ git push -u origin main, git push -u origin master

*한번 commit을 했다면 $ git commit -am " "로 줘도 됨.