## Git Command

- `git init` : git 초기화 명령어로, 로컬에서 현재 위치에 git 로컬 저장소를 새로 생성하는 명령어이다. 프로젝트의 루트 폴더에서 init을 하면 폴더 내에 .git 이라는 폴더가 생성된다.
- `git remote add origin <remote repository url>` : 로컬 git 저장소와 원격 저장소<remote repository url> 를 연결하는 명령어이다. git push, git pull 명령어를 사용했을 때 remote 로 연결되어 있는 원격 저장소와 push/pull 이 이루어진다.
- `git commit` : 로컬 저장소 내에 add 로 스테이징한 작업 내용을 기록하는 명령어이다. commit 명령어 뒤에는 해당 commit의 작업 내용을 설명하는 텍스트를 작성하여 함께 저장할 수 있다. 
- `git push origin <branch name>` : 현재 로컬 저장소 브랜치의 commit 된 내용을 원격 저장소의 <branch name> 에 업로드한다. 원격 저장소에 해당 브랜치 이름이 없는 경우 생성된다.
- `git pull origin <branch name>` : 원격 저장소의 <branch name> 의 내용을 내려받아 현재 로컬 저장소의 브랜치에 병합한다.
- `git merge <branch name>` : 현재 로컬 저장소 브랜치에 <branch name> 의 내용을 끌어와 병합한다. 병합 과정에서 동일한 부분에 다른 코드가 있는 경우 conflict가 일어날 수 있다.
