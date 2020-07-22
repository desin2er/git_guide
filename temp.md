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