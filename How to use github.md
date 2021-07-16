## 0 왜 쓸까

1. 간단하게 백업이 가능
2. 버전 관리가 가능 
3. 일종의 클라우드 시스템으로 협업이 가능

## 1. 용어

Local Repository  : 지역저장소

Remote Repository : 원격저장소 

Push : Local Repository -> Remote Repository

Pull : Remote Repository -> Local Repository

## 2. 명령어

`git log` 지역저장소 확인

`git remote add origin [git 저장소 https]` 지역저장소와 원격저장소를 연결

- 여기서 origin은 저장소의 별명인데 같은 별명의 저장소가 존재할 경우 error: remote origin already exists. 라고 뜨는것같음.
  - origin2라고 다른이름으로 해봤더니 해결됨

`git remote` 원격저장소 표시

- `git remote -v` 원격 저장소 주소 표시

`git push`  업로드 절차시작

- `git push --set-upstream origin master` 깃허브 계정등록

`git log`  깃 로그표시

`git status` 깃 상태표시

`git add [파일명]` 깃에 파일 추가하기

`git commit -m [수정사항]` 추가한 파일을 등록하기

`git clone [https]` 원격저장소->지역저장소 로 복제







