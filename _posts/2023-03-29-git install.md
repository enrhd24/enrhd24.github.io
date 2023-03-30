---
layout: post
title: "Git get Start"
date: 2023-03-29 10:00:00 +0900
categories: GIT
tag: [GIT, github]
---
### [git setup settings](https://www.lainyzine.com/ko/article/how-to-set-git-repository-username-and-email/)
---
#### [1] [git](https://git-scm.com/downloads) ==  [2] [git GPG keys Create](https://docs.github.com/ko/authentication/managing-commit-signature-verification)<br>
#### [3] repositories Private -> Public 변경
#### [4] git fetch 와 git pull의 차이점
#### [5] git branch의 최소설정방법
#### [6] git reset 되돌리기 및 강제 푸쉬하기
#### [1] [git](https://git-scm.com/downloads)<br>
#### [2] [git GPG keys Create](https://docs.github.com/ko/authentication/managing-commit-signature-verification)<br>
#### [3] repositories Private -> Public 변경<br>
#### [4] git fetch 와 git pull의 차이점<br>
#### [5] git commit 상태돌기기 및 git check out
---

#### [1] git
> 1. [vscode](https://code.visualstudio.com/download)<br>
> 2. git의 nano를 visual code Git's으로 선택
> 3. Windows Terminal에서 git 명령어 사용
> 4. git Bash의 "ssh-keygen" -> cd ~/.ssh -> cat id_rsa.pub -> Ctrl + c
> 5. git 홈페이지 -> Settings -> SSH and GPG keys -> Title , key 입력
> 6. Windows Terminal OF <br>
git config --global user.name "Your Name"<br>
git config --global user.email you@example.com <br>
> 7. Windows Terimal 창을 껃다 끼기
> 8. git 홈페이지의 Create Repositories
> 9. mkdir "username" -> cd "username"
> 10. git clone "my Repositories path"
> 11. git echo "This is my first commit" >README.md
> 12. git add. -> git commit -m "first commit" <br> git push origin main 

[2] git GPG keys Create
> 1. gpg --full-generate-key -> 1 -> Real name : " " -> Email address : " " -> o
> 2. gpg --default-new-key-algo rsa4096 --gen-key -> 1번이 안된 경우 사용하세요.
> 3. gpg --list-secret-keys --keyid-format=long
> 4. gpg --armor --export GPGkeys입력 -> -----BEGIN ~ BLOCK----- Ctrl + C
> 5. git 홈페이지 -> Settings -> SSH and GPG keys <br> 
     GPG keys[New GPG key] -> Title, key[Add GPG key]

[3] repositories Private -> Public 변경
> 1. Repositories Settings OF Danger Zone<br> 
> -> Change visibility <br>
> -> change to public <br>
> -> I want to make this repository public <br>
> -> I have read and understand these effects <br>
> -> Make this repository public

[4] git fetch 와 git pull의 차이점
 > fetch : 원격 저장소의 변경사항 확인 [데이터 노 변화]<br>
 > pull : 원격 저장소의 변경사항 확인 [최신 데이터 변화]<br>
 > git fecth // git diff ...origin

[5] git branch의 최소설정방법
 > git restore . : 최신 commit 상태로 돌리기<br>
 > git branch : 브랜치 이름 보기<br>
 > git branch "..." : 브랜치 생성<br>
 > git checkout "..." : 브랜치 이름 변경 <br>
 > git pull origin main : fetch 와 최신자료 가져오기 
[6] git reset 되돌리기 및 강제 푸쉬하기
