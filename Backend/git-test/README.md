## Git Command

- `git init` repository를 생성하고 깃과 깃허브를 연결하기 위한 디렉토리를 생성하고 설정하여 git 작업을 위한 초기화를 진행한다.
- `git remote add origin <remote repository url>` 초기화한 디렉토의 git local을 github와 연결시키기위한 명령어
- `git add <file name>` 해당 branch에서 local에 있는 프로젝트 작업물을 remote storage에 보내기 위한 사전단계
- `git commit` add 한 프로젝트 작업물을 remotew storage에 보내는 작업 이때, 작업한 내용에 대하여 메시지를 작성하여 commit할 수 있도록 한다.
- `git push origin <branch name>` commit한 프로젝트 작업물에 대한 branch를 원격 저장소로 보냄
- `git pull origin <branch name>` 원격저장소에 있는 프로젝트를 로컬저장소로 가져오기 위함
- `git merge <branch name>` 푸시한 원격저장소의 프로젝트 작업물을 원격저장소의 main으로 merge함
