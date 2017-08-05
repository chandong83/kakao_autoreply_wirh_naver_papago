# kakao_autoreply_with_naver_papago    translate chatbot
# 카카오톡 자동응답(챗봇) 서비스와 네이버 파파고(papago)를 이용한 자동 번역 챗봇 만들기 - Node.js편



![스크린](./img/Screenshot.png)

<pre>
카카오톡 자동 응답 서비스와 네이버 파파고 서비스를 이용하면
나만의 번역기를 만들 수 있습니다.
(라즈베리파이와 같은 SBC를 이용하면 될 듯합니다.)
홍콩 과기대 김성훈 교수님께서 만드신 것을 보고 node js로 공부 겸 만들어 봤습니다.
https://github.com/hunkim/line-papago-bot

현재는 한국어를 영어로면 변경이 가능합니다.

코드는 동작하는 코드이지만
네이버 API ID & Key를 할당받아야하고
카카오톡 자동응답 서비스 신청을 해야합니다.

</pre>

~~~~~
//네이버 KEY
var client_id = '당신의 네이버 API ID';
var client_secret = '당신의 네이버 API 암호키';
~~~~~


필요한 패키지들은 다음과 같습니다.
~~~~
[적용 폴더]$ npm init -y
[적용 폴더]$ npm install request
[적용 폴더]$ npm install body-parser
[적용 폴더]$ npm install express
~~~~


##실행 방법
~~~
$node kakao_naver_papago.js
~~~

http://chandong83.blog.me/221067630252
