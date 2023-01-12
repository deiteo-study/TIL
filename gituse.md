# Github 사용...

working dir (작업영역) 

     git add  (working dir -> staging area)

→ staging area (commit으로 남기고 싶은 내용) 

    git commit -m 'message(자세한 설명)' (staging area -> repository)

→ Repository (저장)


  `git status : 현재 상태` (git에서 제일 많이 쓰게 될 것)


```
git remote add origin <url> 주소에 깃을 연결
git branch -M 이름          이름수정 (main or master 이름설정에 따라서 오류가 날 수도 있다)
git push -u origin main     깃허브에 푸시

git clone <url>    깃허브에서 클론을 복사해옴
-> 사이트에서 다운로드만 하면 .git 없이 코드만 다운받아옴
```


- git commit 만 입력시 vim 모드에 들어가짐 → 나오기 위해서 ESC로 명령모드→ :q! 로 탈출

- Repository (특정 디렉토리를 버전관리하는 저장소)
    - git init 명령어로 로컬 저장소를 생성
    - .git 디렉토리에 수정사항 기록