
git init
git add .
git commit -m "Initial commit"

git branch -M main
git switch -c develop

git remote add origin https://github.com/사용자명/저장소명.git
git push -u origin develop

# 현재 변경 상태 확인
git status

# 브랜치 목록 확인
git branch

# 원격 브랜치까지 확인
git branch -a

# 커밋 기록 확인
git log --oneline

# 기존 브랜치로 이동
git switch main
git switch develop

# 원격 변경 내용 받아오기
git pull

# 원격 저장소 정보 확인
git remote -v