## 230823 ##
1. 로컬 저장소 ex생성<br>
`$ git init`<br>
`code($ git init)`<br>


2.README.md 파일 생성<br><br>
`$ touch README.md`<br>
`$ git add .`<br>
`$ git commit -m " "`<br>

3.온라인 저장소 생성<br>
`$ git remote add origin https://github.com/sslee1210/README.md.git`<br>

4.ReadME.md 파일 온라인 저장소 업로드<br>
`$ git push -u origin main, git push -u origin master`<br>

<b>*한번 commit을 했다면 $ git commit -am " "로 줘도 됨.<br></b>

### github에서 내려 받기 ###

`$ git pull origin main`


### clone과pull 특징 ###

1. clone: 로컬에 저장소가 없는 경우. 저장소 자체를 복사
2. pull: 로컬에 연결된 저장소에 있는 경우. 저장소 안에 있는 파일 내려받기


충돌(CONFLICT)시 해결 방법
 온라인과 로컬 각각 수정이 일어났
1. pull을 이용하여 온라인 저장소에 로컬로 파일 내려받기
2. 받은 로컬 저장소의문서를수정 후 commit,push
