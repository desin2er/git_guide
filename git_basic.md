# GitHub 기본 사용법

### I. GitHub 사이트
1. [GitHub](github.com/) 페이지 이동
2. 가입 및 로그인
3. repositories 생성
4. Git Bash 실행
     - git clone "주소"
     - git add .
     - git commit -m "내용"
     - git push
5. 확인한다.

---
```
<master>
$ git clone "clone_path"

$ git add .
or
$ git add -p
    - 하나씩 확인하며 넣는다.

$ git commit -m "message.." ex> "update file" , " create file"
$ git push
$ git pull

<brach>
(master) $ git branch branch_name
    - branch 생성
$ git checkout branch_name
    - [branch_name]으로 이동
(branch_name) $ git checkout master
(master) $
$ git merge master branch_name
$ git branch
    - branch list
$ git branch --delete branch_name
or
$ git branch -D branch_name
    - 강제로 삭제
```
