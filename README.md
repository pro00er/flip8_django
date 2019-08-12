# flip8_django
- [모두의 연구소 - 풀잎스쿨 8기 Django with TDD](http://home.modulabs.co.kr/product/%eb%b6%81%ec%b9%98%ea%b3%a0-django%ec%b9%98%ea%b3%a0/) 과정 실습을 위한 repository
- Django(Python Web Framework) 기본학습 - 매 시간 pair programming 과 TDD 실습으로 진행됨.
- 주교재 : [obey the testing goat 영문판](https://www.obeythetestinggoat.com/pages/book.html)

## Repository 활용
- 매 풀잎 pair programming 전, repository(이하 repo) 를 pull 받아서 오늘 시작할 부분 전까지 
### 초기세팅 
1. 원하는 directory로 이동한 후에 아래 명령어로 repo clone 		
	`git clone https://github.com/pro00er/flip8_django`
2. `cd flip8_django` 혹은 파일탐색기에서 이동하여 원하는 폴더에 clone 되었는지 확인
3. pycharm 실행 - `open`해서 프로젝트 불러옴
4. virtual enviorement 세팅  
  - 방법1. requirements.txt 로 들어가서 code view창 상단 메시지 - requirements 적용
  - 방법2. terminal 창에서 실행
    - 적용하고 싶은 가상환경 scripts의 requirements 실행
        $ ../가상환경이름/Scripts/activate 
        $ pip install -r requirements.txt
5. 제대로 실행되는지 확인 `python manage.py runserver` 
 
## 매 시간 전 프로젝트 업데이트 된 내용 가져오기
1. repo update된 내용 확인 `git pull`
2. 받아온 내용이 제대로 실행되는지 확인
