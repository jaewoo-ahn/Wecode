### 1.git branch feature/~,git checkout feature/~
클론을 해온 프로젝트는 내 `local`에는 `master branch`를 그대로 가져온것이다. `master branch`는 그프로젝트의 원본이므로 수정을 하면안되고(신성한 영역!) 수정할 기능별로 `feature branch`를 설정하여 설정한 곳에서 수정을 해야 한다.
명령어 :`git branch feature/~` (branch 설정)
      `git checkout feature/~` (설정한 branch로 이동)

### 2.모든 수정이 끝났을 때 git add.을 한다 git add.은 작업 디렉토리(working directory) 상의 변경 내용을 스테이징 영역(staging area)에 추가하기 위해서 사용하는 Git 명령어이다.
명령어 : `git add .`

### 3.git commit -m "~"
자신이 무슨 수정을 하였는지를 말하는 코멘트를 올리는 것
명령어:
`git commit -m "~"` : 1줄로 코멘트를 올릴때 사용
`git commit` -> `i(insert)` -> `코멘트 작성` -> `esc` -> `: `->` wq`
코멘트를 여러줄 작성 할 때 사용