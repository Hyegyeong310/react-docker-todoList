# React-docker-todoList

- docker image 받기<br>
  `docker pull hyegyeong310/react-docker-todo-list`

- docker container 실행<br>
  `docker run -it -p ${PORT}:80 hyegyeong310/react-docker-todo-list`<br>
  `localhost:${PORT}에서 확인`

- docker container background 실행<br>
  `docker run -d -p ${PORT}:80 hyegyeong310/react-docker-todo-list`

- docker image 확인<br>
  `docker images`

- docker container 확인<br>
  `docker ps -a`<br>
  `docker ps // 실행 중인 container만 확인`

- docker container 재실행<br>
  `docker start ${container id} // docker ps -a에서 확인 가능`

- docker container 중단<br>
  `docker stop ${container id}`
