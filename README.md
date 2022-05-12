YesDev-Project
ToDo-List using Python Django framework in backend and React in FrontEnd.

Quais os desafios que encontrou em desenvolver essa aplicação?

De modo geral, pode-se afirmar que APIs são mais abstratas e necessitam de mais capacidade de raciocínio, de tal modo que é sempre um desafio muito interessante. Posso 
afirmar que um dos maiores desafios foi justamente a integração entre o FrontEnd com o BackEnd.

Como rodar a sua aplicação?

O projeto está dividido em duas pastas: uma de FrontEnd e outra de BackEnd. No caso da primeira, basta certificar-se de ter instalado o Node, e caso não tenha, basta 
digitar na linha de comando sudo apt-get install nodejs. Em seguida, digite o comando npm install(gerenciador de pacotes), e digite npm start. Da mesma forma, acesse a 
pasta de BackEnd e digite no terminal python manage.py runserver. Basta certificar-se de que ambas as aplicações estarão rodando simultaneamente, e assim a aplicação 
React irá chamar a Api em Django.

Como você testaria sua aplicação?

Pelo fato de ser uma aplicação mais simples, é algo quase automático detectar potenciais bugs e falhas e corrigí-los. No entanto, em aplicações comerciais e mais robustas, o ideal seria realizar testes, e sempre que possível, refatorar o código para torná-lo mais semântico e organizado, ao mesmo tempo com maior simplicidade. É importante também fazer testes com deploy de uma versão "demo", para que assim seja possível testar a segurança, velocidade e até mesmo fornecer uma resposta rápida para o cliente.

Descreva você utilizando Json!

Como em muitas aplicações em python é necessário fazer uso de dicionários, acredito que seja algo relativamente fácil e natural fazer uso de dados em formato Json, 
tendo em vista que é muito semelhante. No entanto, conforme disse anteriormente, APIs geralmente representam um desafio razoável, dado seu elevado nível de abstração, 
e dessa forma, por mais que seja algo simples, certas vezes pode ser um obstáculo, em conjunto com os demais pequenos problemas a serem enfrentados.


