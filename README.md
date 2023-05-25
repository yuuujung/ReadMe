git init // 레퍼지토리 초기화
git add README.md

git remote add origin github주소
git remote -v 로 확인

<인증>
git config --global user.name "yuuujung"
git config --global user.email "dbwjd980611@naver.com"

git add --all
git commit -m "메세지 내용"
git branch -M main
git push -u origin main
