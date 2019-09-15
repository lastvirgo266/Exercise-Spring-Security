# Exercise-Spring-Security


2019-09-14

OAuth를 이용하여 보안을 만들려고 했더니 잘 이해가가지 않아서 `코드로 배우는 웹 프로젝트` 교재를 통하여 Spring-Seucirty 학습을 하기로 함 
**Maven**을 통하여 버전관리를 하고 **Tomcat** 서버, **Oracle**을 이용함
  
  
  
  
Security에 관련된 security-context.xml 파일을 작성하고 필터를 적용하기위해 web.xml에 필터를 작성해줌. 여기서 철자를 하나라도 틀리면 오류가 발생하며 오타에 유의해야함
  
  
  
  

2019-09-15
  web.xml에서 설정을통해 접근제한을 할수 있음. 로그인을 하면 쿠키값으로 로그인 정보를 기억하는데 개발자 도구 - Applicaion탭에서 확인할 수있으며 이때 로그인을 할때 쿠키값이 변하는것을 볼수 있다.(쿠키값을 삭제하면 로그인 정보가 삭제된다) 또한 access-denied-handler를 통해 오류가 발생하면 URL은 그대로지만 error-page의 URI를 불러올수있다.
  
