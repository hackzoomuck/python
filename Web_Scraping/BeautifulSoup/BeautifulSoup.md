 #### BeautifuleSoup Parser
 
1) BeautifulSoup4 내장 파서
 soup = BeautifulSoup(파싱할문자열, 'html.parser')

2) lxml HTML 파서 사용 (외부 C 라이브러리)
 • html.parser 보다 좀 더 유연하고, 빠른 처리
 • 설치 : pip3 install lxml
 • soup = BeautifulSoup(파싱할문자열, 'lxml')
 
 Tag를 찾는 2가지 방법
 1. find를 통해 태그 하나씩 찾기
 2. 태그 관계를 지정하여 찾기 (CSS Selector 사용)
 
 #### BeautifuleSoup : find()
 
find() 메서드 사용
 • find (‘tag_name’) : 태그 이름으로 엘레먼트 찾기
 • find (‘css_class_name’) : CSS 클래스 명으로 엘레먼트 찾기
 
 #### BeautifuleSoup : find_all, select()
 
find_all() 메소드 사용
 • find_all(‘tag_name’) : 태그 이름으로 엘레먼트 찾기
 • find_all(‘css_class_name’) : CSS 클래스 명으로 엘레먼트 찾기
