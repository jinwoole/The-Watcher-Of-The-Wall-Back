# The-Watcher-Of-The-Wall-Back
Simple Monitoring  
대충 쓴 기획: 단일 컨테이너, No DB, No File, Stateless  

시나리오  
client: You OK?  
Watcher: Let me see... Hey You guys OK?  
Herd: Yeah, We think so.  
Watcher: They're OK. Here is a report.  
  
끝.  

필요한거  
1. Client의 OK 요청을 받을 API  
2. 요청 받을 클라이언트의 도메인과 요청할 서버들의 IP와 Port를 담은 Config 파일  
3. 도커파일  
