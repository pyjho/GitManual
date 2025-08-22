# Git 명령어 정리

- 브랜치 생성 후 체크아웃
   - 위 두가지 기능을 한번에. 즉, 브랜치를 생성하고 체크아웃하는 기능을 의미 
```bash
git checkout -b A main
        =
git branch A main # main 브랜치를 기반으로 A 브랜치 생성
git checkout A    # A브랜치로 이동
```
    
- 특정 커밋시점으로 파일 되돌리기
 ```bash
git checkout HEAD~1 index.html # 1커밋 전으로 되돌리기
 ```


