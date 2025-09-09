- PUSH

  선택한 브랜치를 원격 서버로 전달한다는 의미
   
   ```bash
   git push 원격저장소_별칭 브랜치이름 
   git push -u origin main      # main브랜치를 원격으로 전송
   ```
   - 로컬에 생성한 브랜치를 원격저장소에 전송
   ```bash
   git push -u origin hotfix    # hotfix 로컬브랜치를 원격저장소에 전송
   ```
   - 원격저장소에 다른 사용자가 만든 동일한 브랜치명이 존재시 다른이름의 브랜치로 생성하는 법
   ```bash
   git push origin 브랜치명:새로운브랜치    # 새로운 브랜치명으로 원격에 전송
   ```
   