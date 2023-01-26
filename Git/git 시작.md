## **Git Connection**

1. IDE 우측 상단의 Perspective에서 [Git] 선택. 만약 존재하지 않는다면 [Open Perspective]에서 [Git]을 선택하면 된다.
2. IDE 좌측 상단의 [Git Repositories] 옆으로 초록색 화살표로 파일을 받아오는 듯한 아이콘 [Clone a Git Repository and add the clone to this view] 클릭
3. Git 페이지에서 [Clone with HTTPS] 복사
4. IDE [Clone Git Repository] 팝업 내의 [Location] - [URL]에 3.에서 복사한 내용 붙여넣기
5. 하단의 [Authentication]에 본인 id/pw 입력 후 [Next]
6. remote repository에서 local로 clone 해 올 branch 선택 후 [Next] (보통 develop 버전만 clone 따 온다.)
7. [Destination] - [Directory]에 원하는 workspace 선택 후 [Finish]

## Git Pull

1. 업데이트를 받을 것이 있다면 프로젝트 파일에 ↓ 화살표가 존재 할 것이다.
2. 프로젝트 파일 마우스 우측 클릭 - [Team] - [Pull]

## Git Commit & Push

1. 커밋 & 푸쉬를 하기 전에 항상 Pull 받을 항목들이 있는지 확인. 커밋 직전 Pull을 받아주는 것이 좋다.
2. 프로젝트 리스트에서 커밋 할 파일 선택
3. 마우스 우측 클릭 - [Team] - [Commit]
4. 업데이트 한 파일이 Staged Changes에 있을 것이다.
5. 만약 새로 생성한 파일이라면 Unstaged Changes에 있을 것이다. 해당 파일을 클릭하고 우측 위의 초록색 + 버튼 [Add Selected Files to the index]를 클릭하면 Staged Changes로 이동한다.
6. 우측 Commit Message에 내용을 작성하고, [Commit] or [Commit anf Push]
   (Push도 바로 할 지 Commit만 할 지는 프로젝트 상황에 맞추어 알아서 선택하면 된다.)

## Git Merge

1. 소스를 서버에 있는 파일로 복구하고 싶을 때는, 복구하고 싶은 파일 마우스 우측 클릭 - [Team] - [Replace With] - [HEAD Revision]
2. 내 소스에서 추가해야 할 것이 있다면, 복구하기 전에 미리 소스를 백업해두자.