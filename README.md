# Install_excute_for OIDC

### 실행환경
- java -version : java version "11.0.11" 2021-04-20 LTS
- mvn -v : Apache Maven 3.8.1
- node -v : v15.14.0
- npm -v : 7.20.5


### remote code
- 클라우드 서버와 DB를 이용함 => frontend만 로컬에서 실행하여 접속
- git clone https://github.com/ewha-joy/remote_frontend
- cd remote_frontend
- npm install
- npm start
- localhost:3002 접속
- 아래의 아이디 와 비밀번호를 통해 해당 서비스 이용가능


### local code git clone & excute

- <a href = https://github.com/ewha-joy> ewha-joy code </a>
- 로컬환경에서 서버와 프론트엔드 실행 (단, db는 클라우드를 이용함)
- 아래의 8개 레포지토리 git clone
![image](https://user-images.githubusercontent.com/37402084/129603345-e0d00ead-c01a-4ca2-a61a-ed8565d59378.png)

1) <a href = https://github.com/ewha-joy/config-server> config-server </a>
- git clone https://github.com/ewha-joy/config-server
- cd config-server
- mvn clean package
- cd target
- java -jar [자바 실행 파일]

2) <a href = https://github.com/ewha-joy/eureka-server> eureka-server </a>
- git clone https://github.com/ewha-joy/eureka-server
- cd eureka-server
- mvn clean package
- cd target
- java -jar [자바 실행 파일]

3) <a href = https://github.com/ewha-joy/api-gateway> api-gateway </a>
- git clone https://github.com/ewha-joy/api-gateway
- cd api-gateway
- mvn clean package
- cd target
- java -jar [자바 실행 파일]

4) <a href = https://github.com/ewha-joy/cash-service>cash-service </a>
- git clone https://github.com/ewha-joy/cash-service
- cd cash-service
- mvn clean package
- cd target
- java -jar [자바 실행 파일]


5) <a href = https://github.com/ewha-joy/user-service>user-service </a>
- git clone https://github.com/ewha-joy/user-service
- cd user-service
- mvn clean package
- cd target
- java -jar [자바 실행 파일]


6) <a href = https://github.com/ewha-joy/webtoon-service>webtoon-service </a>
- git clone https://github.com/ewha-joy/webtoon-service
- cd webtoon-service
- mvn clean package
- cd target
- java -jar [자바 실행 파일]



7) <a href = https://github.com/ewha-joy/NFT-server>NFT-server </a>
- git clone https://github.com/ewha-joy/NFT-server
- cd NFT-server
- npm install
- node server.js


8) <a href = https://github.com/ewha-joy/FrontEnd>FrontEnd </a>
- git clone https://github.com/ewha-joy/FrontEnd
- cd FrontEnd
- npm install
- npm start
- localhost:3000 접속
- 아래의 아이디 와 비밀번호를 통해 해당 서비스 이용가능

![image](https://user-images.githubusercontent.com/37402084/129605327-747454ed-b003-4e75-acc1-ae21a8dcdc6e.png)

![image](https://user-images.githubusercontent.com/37402084/129605358-a95775d3-be9a-46e1-8225-106b9c2c68f0.png)



### ID & PW
- 작가권한 : author_joy1886 / joyjoy1886*
- 유저권한 : joy_user_1886 / joyjoy1886*


