# Catálogo de jogos
<br/>

### Crud desenvolvido durante curso ministrado por Thiago Campos, desenvolvedor .NET para o Bootcamp Decola Tech na plataforma Digital Innovation One. 
<br/>

### Foi abordado durante o curso: 
Conceitos sobre a utilização e importancia do padrão de desenvolvimento com Injeção de dependência. 
<br/>
<br/>

### Mapeando a requisições na web; 

Quando o cliente realiza um request para o servidor back end, 

Passa primeiramente por um Middleware, que cuidará desse request, aplicando tratativas ou verificando autenticação por exemplo, antes de enviar a requisição para o controller.

Quando a requisição chega ao controller tratamos com nossa lógica, produzindo o response. 

A classe services por sua vez é responsável pela lógica de negócio, não se comunica direto com o banco, no entanto orquestra chamadas através do Repository e pode chamar outros serviços. 

O Repository, como já mencionado, é responsável por segregar o acesso ao banco de dados,

Entity é uma representação do nosso banco. 

E a DTO que é a representação do que esta sendo trafegado. 

<br/>
<br/>



