# Relase 브랜치 생성 후 추가적인 작업이 있는 경우 git flow practice

- dev 브랜치 생성

- login 기능 추가 (dev -> feature/login)

- logout 기능 구현 (dev -> feature/logout)

feature/login, feature/logout merge into dev branch

dev branch -> release branch(RB)

- find pw 기능 구현 ( RB -> feature/find_pw )

feature/find_pw merge into RB

RB merge into main

- main 운영 배포 완료

main merge into dev

... 이후 프로세스 반복

###################RESET###########################

# Relase 브랜치생성 후 추가 작업이 필요 없을 경우 git flow practice

- dev 브랜치 생성 (main -> dev)

- login 기능 추가 (dev -> feature/login)

- logout 기능 추가 (dev -> feature/logout)

feature/login, feature/logout merge into dev branch
dev branch -> release branch 
 (이후 추가 작업 없음)

release branch merge into main
- main 운영 배포 완료

main merge into dev
... 이후 프로세스 반복


###################RESET###########################

# Hotfix가 필요할 경우 git flow practice

(main과 dev가 Sync된 이후로 추가 commit이 있었다고 가정)