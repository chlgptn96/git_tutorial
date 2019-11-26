#git 연습

## 저장소 생성

    - git init
        - git config
        user.name 이름
        - git config
        user.email 이메일
                        --파일 생성(작업DIR안쪽에 readme.md가 생성됐습니다.)--

## 변경 사항 Staging

    - git add 파일명
    - git add * : 변경 사항 전체
    - git add . : 현재디렉토리 아래 모든 변경 사항

## 변경 사항을 저장소로
    - git commit -m "현재 변경사항의 설명"

## 변경 로그의 확인
    - git log

## Staging 추적 제외를 위한 설정 파일
    - .gitignore에 제외할 파일명의 패턴을 명시