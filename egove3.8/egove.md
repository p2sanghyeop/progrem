<beans:property name="prefix" value="/WEB-INF/views/" />
-> /WEB-INF/views/ 안에 있는 파일을 읽겠다는 뜻

<beans:property name="suffix" value=".jsp" />
-> .jsp로 끝나는 파일을 읽겠다는 뜻

<resources mapping="/resources/**" location="/resources/" />
-> resources 안에 있는 모든 파일을 일겠다

<context:component-scan base-package="com.app.board" />
->comm.app.board 부터 시작해 @Component가 있는 것을 자동으로  bean을 주입해 주겠다


