<h2> Configurações para execução em diretório local </h2>

Fora utilizado ferramentas como node e gulp. 
gulp: "É um JavaScript Task Runner"

Em principio, para instalação dos modules do node, pode se criar uma pasta para conter o projeto, e, em seguida, via terminal/cmd executar o comando a seguir: (assumindo que o node já esteja instalado)

>npm init -y

Em seguida, será usado novamente o npm para instalalção do gulp juntamente com alguns pacotes para execução. Um deles é o gulp-sass que permite a compilação sass dentro do projeto.

>npm install gulp browser-sync gulp-sass --save-dev

Para as dependências do bootstrap:

>npm install bootstrap jquery popper.js --save

Por fim, executamos:

>gulp

