# java-language

## Front-End

### Para usarmos o java no front end precisamos utilizar o *Thymeleaf* com o *SpringBoot* 

O Thymeleaf é um motor de templates (template engine) usado no Spring Boot para gerar páginas HTML dinâmicas no servidor. Ele permite que o backend envie HTML pronto para o navegador, sem precisar de um frontend separado como Angular ou React.

Essa abordagem é muito usada para aplicações web server-side rendering (SSR), como sistemas administrativos, portais e dashboards, onde a necessidade de interatividade complexa no frontend é menor.

Como o Thymeleaf Funciona no Spring Boot?
O fluxo básico é assim:

1️⃣ O usuário acessa uma URL na aplicação.
2️⃣ O Spring Boot processa a requisição no backend.
3️⃣ O controlador retorna um template HTML preenchido com dados do backend.
4️⃣ O navegador exibe a página gerada.