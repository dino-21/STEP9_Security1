


<img width="762" alt="28" src="https://github.com/dino-21/STEP9_Security1/assets/80396471/f23b5725-8ea0-4819-b2ce-b45ce92cf84e">

![35](https://github.com/dino-21/STEP9_Security1/assets/80396471/7d280fd0-3354-4e0e-b680-e8b1591d5803)

![24](https://github.com/dino-21/STEP9_Security1/assets/80396471/532abcfc-6d56-487c-aa13-fd5418d38034)



1 스프링 시큐리티는 필터를 사용한다.

2 스프링 프로젝트를 따로 만든다

3 자바11, 톰캣 9.0 인지 확인

4 update Maven


5  pom.xml 라이브러리에 
Spring Security Core 4개 추가

메이븐 업데이트 

6 security-context.xml 생성
 네임스프레이스에서 security항목을 체크


7 web.xml 설정
<param-value>
	/WEB-INF/spring/root-context.xml
	/WEB-INF/spring/security-context.xml
</param-value>


8 security-context.xml 설정 추가


9 시큐리티가 필요한 URI 설계

/sample/all 
/sample/member
/sample/admin




10 SampleController.java 파일 만들기 



11 인증(Authentication)과 권한 부여(authorization-인가)

12 로그인과 로그아웃 처리



13 여러 권한을 가지는 사용자 설정 – 2개의 권한을 가지도록 지정

14 접근 제한 메시지의 처리


15 views 폴더에 accessError.jsp파일을 생성한다.


16  AccessDeniedHandler 인터페이스를 구현하는 경우


17 커스텀 로그인 페이지


18 CSRF(Cross-site request forgery) 공격과 토큰


19 로그아웃 처리와 LogoutSuccessHandler


20 로그인 성공과 AuthenticationSuccessHandler






