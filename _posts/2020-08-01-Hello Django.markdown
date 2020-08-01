< 가상환경 세팅 >
1. pip install django -장고 설치 
2. django-admin starproject [프로젝트 이름 쓰기]- 프로젝트 만들기 
3. python manage.py startapp [앱 이름]- 앱 폴더 만들기 
4. setting.py(프로젝트 폴더 안에 있다.) 에서 app 연결 - 앱 연결하기 
5. templates 폴더 안에 html 파일들을 추가 - 기능 구현할 html 파일 만들기 
6.  app 안에 views.py(함수 형식으로 html 을 불러와 데이터 처리) 생성 -함수 작성 파일 생성 
7. url.py에서 path를 이용, html 파일과 연결
8. python manage.py runserver 서버 돌리기 


settings.py(app 추가 시키기) -- templates(html 파일 생성)--views.py( 함수 생성)-- urls.py (path 이용 html 연결) 
