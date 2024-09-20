1. Docker:
- image-> mysql/mysql-server:latest
 port-> 3036:3036
 MYSQL_ROOT_PASSWORD=root

2. How to run:
   + Application run as debug
   - gradle build -x test
   - in git bash ./gradlew build -x test

3. POST http://localhost:8080/user/name
4. GET http://localhost:8080/users
5. PUT http://localhost:8080/user/1?name=tester
6. DELETE http://localhost:8080/user/3

