# crawling_naver
로그인이 필요한 네이버 데이터를 크롤링 할 수 있게 도와주는 코드

전제조건
python 프로그램이 존재. chromedriver 파일 다운로드 받아야 함. chromedriver과 chrome 이 패치되어 호환이 되지 않는다면 새로운 chromedriver를 다운받아 사용해야 함.
크롬드라이버 다운로드 주소 : https://sites.google.com/a/chromium.org/chromedriver/home


사용법
1. 8번 # options.headless = True 의 #를 지워서 활성화 시킨다.(활성화 하지 않을 경우 크롬이 실행되어 과정을 보여줌.)
2. 11번의 executable_path 의 주소를 자신이 다운로드 받은 chromedriver의 위치로 바꾼다.
3. 26번 '아이디'를 자신의 아이디로 바꿈.
4. 30번 '비밀번호'를 자신의 아이디의 비밀번호로 바꾼다.
5. 44번째 줄 # url 의 # 을 지우고 url = '주소' 로 적는다.
6. 필요한 html을 알아서 크롤링 한다.
