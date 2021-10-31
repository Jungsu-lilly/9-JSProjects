# 9-JSProjects
HTML, CSS, JS 를 사용한 간단한 웹 어플리케이션 9가지입니다.<br>

## 1. Quiz-APP
- 사용자가 지정한 퀴즈가 출제되며 답이 맞은 경우 점수 추가, 틀린 경우 -1 점.<br>
- 문제는 4개의 보기중에 하나를 선택해 제출합니다. 문제를 다 풀면 점수가 표시됩니다.<br><br>

## 2. Recipe APP
출처:'https://www.themealdb.com/api/json/v1/1/random.php'<br>
- 음식 레시피를 DB에서 불러와 랜덤하게 음식 사진과 이름이 출력됩니다.<br>
- 하트 버튼을 눌러 favorite 목록에 해당 음식을 추가할 수 있습니다.<br>
- favorite 목록의 음식아래 x버튼을 눌러 제거할 수 있습니다.<br><br>

## 3. Note-App
- 노트에 글을 쓰고 저장하면, Mark Down 으로 출력됩니다.
- CRUD 기능 구현
- localStorage 를 활용합니다. (2. Recipe App과 동일)<br><br>

## 4. Todos-App
- write todo list
- 완료된 일은 좌클릭해 선으로 그을 수 있다.
- 하나 list를 우클릭해 지울 수 있다.<br><br>

## 5. Movie-app
DB 출처:
APIURL = "https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=04c35731a5ee918f014970082a0088b1&page=1";<br>
IMGPATH = "https://image.tmdb.org/t/p/w1280";<br>
SEARCHAPI = "https://api.themoviedb.org/3/search/movie?&api_key=04c35731a5ee918f014970082a0088b1&query=";<br>
- Movie database 에서 유명한 영화 20개를 추출해 출력.<br>
- 각 영화의 이름과 평점이 표시됩니다.<br>
- 원하는 영화를 Search 할 수 있습니다.<br>
- 마우스를 갖다 대면 영화의 개요가 나타납니다.<br><br>