해당 프로젝트는 Intellij/Spring Boot로 제작되었습니다.
아래 코드를 application.properties에 입력해주세요.

# Security
spring.autoconfigure.exclude=org.springframework.boot.autoconfigure.security.servlet.SecurityAutoConfiguration

# Java Mail SENDER
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=hajincheol123@gmail.com
spring.mail.password=krgzgzbjdxdnrwix
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
spring.mail.properties.mail.smtp.smtp.ssl.trust=smtp.gmail.com

dialogflow.project-id=devhub-fjly
dialogflow.credentials.path=classpath:static/devhub-fjly-217883c354c9.json
