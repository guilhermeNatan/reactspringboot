# React spring boot 
Exemplo de projeto usando springboot com react js 


# Tecnologias utilizadas 
- IDE Intelij 
- spring jpa 
- spring data rest 
- spring security  
- maven
- lombok 
- react js 
- yarn 
- node js 

 # Modulos do projeto 
 - main/java: todo código de back-end usando spring rest  
 - main/js: código front-end 
 - resources/static/built : pasta onde fica o arquibo bundle.js gerado pelo webpack ao transpilar o código react . 
 - resources/templante: contêm a unica página em html da aplicação, servido como ponto entrada da execução da aplicação. 
 
 # Configuração 
- Dentro do arquivo webpack.config.js esta configuração que determina onde  será gerado o arquivo bundle.js, este arquivo 
contêm o código transpilado pelo webpack
 - O arquivo  package.json contêm as dependencias do front-end 
 - O arquivo application.properties contêm as configurações do spring.
 
[obs]: Dentro do arquivo index.html é feito o link do que seria a pagina base da aplicação com o conteudo 
gerado pelo bundle.js:  <script src="/built/bundle.js"></script>. 

# Passos para executar o projeto 
 - execute o build do plugin frontend-maven-plugin pelo proprio maven. 
 - [Importante] configure a variavel de ambiente PATH com o caminho do diretorio bin do yarn criado dentro target  
 C:\Local\dev\reactspringboot\target\node\yarn\Yarn\bin 
 - execute a classe ReactspringbootApplication.java a aplicação será executada iniciada e pode ser acessada  http://localhost:8080/
 
 
 