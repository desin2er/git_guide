## 기본 명령어
```bash
<master>
$ git clone "clone_path"

$ git add .
or
$ git add -p
    - 하나씩 확인하며 넣는다.

$ git commit -m "message.." ex> "update file" , " create file"
$ git push
$ git pull
```
## 100MB 이상 파일 업로드
```bash
git lfs install
git lfs track "*.json"

git add .
git commit -m "message.."
git push orgin master

100MB 에러 로그 제거
git repack && git gc
java -jar bfg-x.xx.xx.jar --strip-blobs-bigger-than 100M RepositoryName.git
* xx 다운로드 받은 버전 입력
```
에러 로그 제거 파일
[jar file 다운로드](https://rtyley.github.io/bfg-repo-cleaner/)  

---
## brach 생성 및 제거
```bash
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
