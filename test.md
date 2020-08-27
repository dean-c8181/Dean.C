Github 정리
기억하지말고 기록하라
집요하게 물고 늘어져라
있어야 할 곳을 제자리에 두고 모두가 알아보기 쉽게 해라
공부하는 습관을 만들어라 매일 꾸준히 조금씩



 첫 시작(새로운 저장소 생성부터)

Github 사이트에서 New repository 생성

 기존 프로젝트(클론 작업)

git clone {gitUrl} {directory}
git clone {reopsitory 주소} {로컬 저장한 파일(디렉토리)}
__ex) git clone https://github.com/dean-c8181/Dean.C.git ./myReact/projectSSY

git diff // 로컬에서 작업한 것 중 달라진 것들 요약해서 보여줌(파일과 변경 내용이나옴)

git add {fileName}
git에 add시킴 {fileName}은 파일경로를 적어야하고 폴더 또는 파일명 둘 다 가능 __ex) git add ../myReact/src/ 또는 git add ./src/myApp.js
git add는 우선 작업한 것을 commit  전까지 대기 시키는 상태이며  
git commit을 하면 그동안 add 했던 파일들이 묶여서 commit 된다.

git commit -m “{커밋(update)제목}”
 __ex) git commit -m “first commit!!!!”

git log // commit 히스토리 내역

git push // commit 한 파일들을 깃허브 repository에 동기화 시킴.(실제 업로드됨)
git status // 현재 로컬에서 수정한 파일들을 알려줌(파일들만 알려줌)






