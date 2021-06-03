# Git Command

> 기본명령어



##### init

`.git`폴더를 생성해주는 명령어



##### add

`git add <file name>`

working directory에 있는 파일을 staging area에 올리는 명령어.



##### commit

staing area에 있는 파일들을 하나의 commit으로 저장하는 명령어



- 기본 사용법

  - `-m`:커밋 메세지를 작성하기위한 옵션

  `git commit -m "message"`



###### remote

- add

  ```
  git remote add <remote nmae><url>
  ```

- remove: 원격저장소를 삭제

  ```
  git remote remove origin master
  ```

  

  ```
  git init
  git add .
  git commit -m "message"
  git push origin master
  ```

  

  ##### status

  git의 현재 상태를 확인하는 명령어

- 기본명령어

  ```
  git status
  ```





