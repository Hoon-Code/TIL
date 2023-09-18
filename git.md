# Git

## 최초설정
커밋에 기록되는 사용자 정보
```bash ( 터미널에 입력하는 코드 입려시 입력해줌)
git config --global user.name<name>
git congif --global user.email<email>
```

## 로컬명령어 ( 앞에 . 있는 파일은 숨김파일)
- `git init`
    -`.git` git repository를 생성 하는 명령어
- `git add <file name>`
    - 작업한 파일들 `working directory`에서 `staging area`로 추가 하는 과정
    - 일반적으로 모든 파일, 폴더를 한번에 추가하기 위해 아래의 명령어로 작성
    - `git add .`

- `git commit` ( 사진 찍는다 생각)
    - `staging area`에 올라간 파일들의 스냅샷을 찍어 `.git directory`에 저장
    - 일반적으로 -m 옵션을 넣어서 커밋메세지를 추가
    - `git commit -m "message"`

## 원격저장소
- `git remote`
    - 원격저장소 주소를 관리하기 위한 명령어
    - `git remote add origin <url>`

- `git push` 
    - 원격저장소에 로컬 코드를 업로드 하기 위한 명령어
    -`git push <remote> <branch>`