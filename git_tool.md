# 명령어
markdown 파일 생성

 echo "# test" >> README.md

초기화

 git init	

커밋할 파일 선택

 git add README.md

커밋

 git commit -m "first commit"

 git branch -M main

로컬과 원격저장소 연결

 git remote add origin https://github.com/ye-bin-kim/test.git

로컬의 커밋을 원격저장소에 업로드

 git push -u origin main

원격 저장소의 업데이트 내용을 로컬로 업데이트 받는법

 git pull origin main

사용자 확인

 git config --global user.name <사용자 이름>

 git config --global user.email <사용자 이메일>

 git config --list

커밋기록 확인 

 git log

깃허브에서 다운

 git clone <git을 다운받을 주소>


... 로컬 = library , 원격저장소 = github
