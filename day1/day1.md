# Git 명령어

- git status (상태 확인하기)
- git add (스테이지에 추가하기)
- git commit -m (수정내용 확정하기)
- git push (Romote 저장소로 보내기)
- git pull (Romote 저장소의 내용을 Local 저장소로 가져오기)
- git commit --amend(마지막 커밋 수정하기)
    - git config --global core.editor "code --wait"

## Git Branch

여러 개발자들이 동시에 다양한 작업을 할 수 있게 만들어 주는 기능이 바로 '브랜치(Branch)' 입니다. 각자 독립적인 작업 영역(저장소) 안에서 마음대로 소스코드를 변경할 수 있지요. 이렇게 분리된 작업 영역에서 변경된 내용은 나중에 원래의 버전과 비교해서 하나의 새로운 버전으로 만들어 낼 수 있습니다.

- git branch (브랜치 목록 보기)
- git branch [브랜치 이름] (브랜치 생성)
- git checkout [브랜치 이름] (브랜치 변경)
- git switch [브랜치 이름] (브랜치 변경 - 2.23 버전 이상)