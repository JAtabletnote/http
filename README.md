http
Requset ->  HTTP <- Response

Git 2022.01.03
VCS (Version Control System)
 즉각적으로 동기화 시키는 기능 Distributed Version Control 분산된 히스토리를 가지고 있어서 서로의 정보를 통해서 계속 일을 이어나갈 수 있음. (오프라인에서도 OK)

Git은 프로젝트의 전체적인 내용을 스냅샷처럼 가지고 있어서 오류가 덜함
쉽고빠른 브랜칭을 통해서 협업을 효율적으로 할 수 있음.

git add -option

cd project (project 파일로 이동)
mkdir git (git파일생성)
cd git
ls -al

git init (깃추가)
ls -al (숨겨진파일확인)

open .git (오픈)
rm -rf .git (삭제)

git config --gloval alias.st status (git status -> git st 줄임)

명령어와 명령어의 속성값을 보고 싶을 때는 git config --h (속성값 확인가능)