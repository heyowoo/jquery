# jquery

echo "# jquery" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:heyowoo/jquery.git
git push -u origin master

 
github에 새로운 repository 를 생성하고, terminal로 remote할때 발생할 수 있는 오류이다.



fatal: remote origin already exists. 에러

따라서 이때 remote origin없애벌

git remote rm origin

입력 후 하면 잘 된당 ㅎㅅㅎ