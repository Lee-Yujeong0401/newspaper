# newspaper

1.위치위그 : 깃허브 홈피

2.터미널 모드 (수동)
-로컬 저장소(현재 내 pc)
-원격 저장소(깃허브 repository)

git branch -M main 저장소 >브랜치 기본경로 생성
git remote add origin
git remote add origin-깃허브 소스 주소-원격저장소 연결

git config --global user.email 깃허브 계정 이메일 주소 >인증

add . 업데이트 할 파일 등록
git status 업데이트 대기 등록된 파일 확인 (new 초록색으로 보임)
git commit -m "첫 업로드" >깃허브 설명글

git config --global user.email "이메일 주소" ->(처음에만 하면 된다)

git push -u origin main //main 이라는 저장소 깃허브에 업로드

다음 업데이트부터는
-git add
-git commit -m "업데이트 설명글"
-git push -u origin main