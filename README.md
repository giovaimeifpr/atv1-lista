1 Quais protocolos (os principais) são usados em uma comunicação realizada
na web? Descreva muito brevemente o papel de cada um deles.

HTTP - transfere os dados entre o navegador e o servidor, requisições e resposta.
HTTPS - mesmo que o http porém de forma criptografada garantindo mais segurança e confidencialidade.
TCP/IP - Transmissão de pacotes em várias partes ordenadas entre os dispositivos físicos. Dessa maneira evita que os dados fiquem desordenados trazendo uma confiabilidade na entrega das informações.

2. Alguns autores usam o termo “arquitetura da web” para se referir a como as
camadas tecnológicas da web estão organizadas e aos princípios que
definem a troca de informações entre essas camadas. Por questões
didáticas e de simplificação, convencionou-se chamar essa arquitetura de
“arquitetura cliente x servidor” ou arquitetura “requisição x resposta”.
Explique de forma simplificada como funciona essa arquitetura.

Para o considerar que estamos utilizando o WWW, é preciso que haja uma requisição por parte do usuário assim ocorrendo uma comunicação web. A maneira mais conhecida são os sites de internet, que logo utilizam navegadores de internet para se comunicar com um servidor e obter respostas na tela do computador. 
Ao digitar www.ifpr.edu.br, o navegador faz uma requisição para o servidor que hospeda o site e retorna as informações que contém nele.


3. Em uma arquitetura web, qual o papel desempenhado pelo protocolo
HTTP?

Responsável pela comunicação entre o cliente e o servidor, definindo requisições e respostas formatadas.


4. O HTTP possui padrões uniformes para requisição e para resposta.
a) Dê ao menos três exemplos métodos de requisição e suas
características;

GET - Método que o cliente solicita ao servidor uma requisição e aguarda um retorno.
POST - Método que o cliente envia requisições ao servidor para salvar informações.
DELETE - Método que manda uma requisição de exclusão do servidor.


b) Dê ao menos três exemplos status de respostas e quando ocorrem;

Status 200 - Sucesso. Quando a conexão obteve sucesso.
Status 404 - Não encontrado. Quando a requisição não encontrou dados.
Status 500 - Erro de servidor. Quando a requisição não encontra nada no servidor.


5. Em uma arquitetura web é sempre o cliente quem inicia o processo de
comunicação: o cliente requisita, o servidor responde. Contudo, aplicações
web como Gmail ou Instagram, “empurram” informações novas ao cliente,
tais como um novo e-mail ou uma “curtida” em uma determinada
publicação. Hipoteticamente, quais estratégias poderiam ser empregadas
para se chegar a esse resultado?

Através da comunicação bidirecional em tempo real entre o servidor e cliente, como websockets.
Após a conexão estabelecida o servidor e cliente podem trocar mensagens em tempo real.

