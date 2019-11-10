# springboot-demo-monitor

### CONFIGURAÇÃO
- incluir a dependência:
    * implementation 'de.codecentric:spring-boot-admin-starter-server:2.1.6'
- incluir as anotações na classe application:
    * @Configuration
    * @EnableAutoConfiguration
    * @EnableAdminServer
- alterar a porta do servidor no application.yml:
    * server.port=8081
- acessar o console:
    * rodar esse projeto admin, depois rodar o projeto clietn
    * http://localhost:8081