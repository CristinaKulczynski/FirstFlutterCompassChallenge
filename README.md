| Perguntas e respostas |

1. Para que serve o método Scrum? Serve para gerenciar projetos de maneira ágil, maximizando a eficiência da equipe e acelerar a entrega dos projetos.

2. Como funciona o método Scrum? Podemos dividir em passos para melhor compreensão. O primeiro é ter uma visão total do projeto e este é responsabilidade do Product Owener, o segundo será dividir o projeto em um conjunto de objetivos e colocá-los em uma lista chamada Product Backlog. Com as prioridades definidas com a equipe presente, chega o mometno de dar o terceiro passo, que é dividir o projeto em ciclos, chamados de Sprints. Depois de terminar cada ciclo, é feita uma reunião com o intuito de melhorar aspectos do andamento do projeto, seja a respeito do time, das reuniões entre outros, visando a melhora continua da equipe. 

3. O que é Git? É um sistema de controle de versões, apesar de ser comumente utilizado para o desenvolvimento de softwares pode ser usado para registrar edições de uma grande variedade de arquivos. A estrutura empregada para organizar os arquivos no Git são os repositórios que contém os históricos completos das mudanças.

4. O que é um scrum Product Owener? É o(a) representante do cliente em um time de Scrum, que o "mediador" entre o cliente e a equipe de desenvolvimento. 

5. Qual o comando para a criação de um novo repositório no Git? git init

6. Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando? git add .

7. O que é a Branch master e para que serve? A Branch master é a parte principal do projeto, também chamada de ramo, servindo como base para novas ramificações, estas que permitem encapsular as mudanças e assegurar que códigos instáveis não sejam mesclados. 

8. Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo? git pull ou git pull <repositório> master e git merge
 
9. Qual a diferença entre git e github? O GitHub é um serviço de hospedagem web para o repositório de controle de versão Git, como uma rede para compartilhameto de códigos e projetos entre desenvolvedores. O Git não permite a vizualização em tempo real das mudanças, ao contrário do Github. Outra diferença é a interface que eles possuem, sendo uma intuitiva e de fpacil comprensão enquanto a outra demanda um pouco mais de tempo para a adaptação. 

10. Quais os dois verbos http que podemos utilizar para realizar um update? Explique a diferença entre eles. No PUT acontece a requisição de um recurso para fazer a modificação, mudando todos os dados deste recurso, caso não exista é possível criá-lo. O Patch, serve quando precisamos alterar apenas alguns dados de um recurso, não sendo possível criar um novo recurso a partir dele. Resumindo, o primeiro muda tudo e pode criar recurso e o segundo muda apenas alguns aspectos e não pode criar recurso.

11. Qual o status code que pode ser usado na criação de um novo usuário? 201 CREATED, utilizado como resposta de sucesso, indicando que a requisição foi bem sucedida e que um novo recurso foi criado.

12. Quais são os três status code que modem ser utilizados para realizar o delete? Eles são: 200(Ok) ação realizada; 202(Accepted) se a ação provavelmente teve sucesso, porém ainda não foi realizada; 204(No Content) se a ação foi realizada e nenhuma outra informação deve ser fornecida.

13. Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)! São listas de códigos de resposta em HTTP, respectivamente Informativa, Sucesso, Redirecionamento, Erro de cliente e Outros Erros.

14. O que é a linguagem de programação Dart? Dart é uma linguagem de programção multi-paradigma utilizada para o desenvolvimento de aplicações web, móveis e descktop, também apresenta fortes estrutuas típicas de linguagens orientadas a objeto. Surgiu com o intuito de substituir o JavaScript, porém não obteve sucesso nesse quesito. 

15. O que é o Flutter? É um framework de interface de usuário de código aberto. Perminte o desenvolvimento de aplicações multiplataforma, tranformando o código em Dart na linguagem nativa das plataformas selecionadas. 

16. Como inicio um novo projeto com Flutter? Com uma IDE de sua preferência instalada (Android Studio, IntelliJ), baixe os plugins necessários de Dart e Flutter e o Android SDK. Depois crie um emulador android. Clique respectivamente em File, New, New Project Flutter. Configure e comece a codar.

17. Quais ferramentas podemos utilizar para criação de novos apps usando Flutter? IDEs como Android Studio, Visual Studio e IntelliJ. Pacotes Pub e bibliotecas, além de Frameworks compartilhados por usuários do GitHub, como por exemplo SpriteWidget que é uma Game Engine. 

18. Qual a diferença entre uma variável final e uma variável var? Elas tem funções diferentes. A Final siginifica atribuição única, ela pode ser inicializada, porém uma vez que tenha sido atribuido um valor a variável não poderá ser alterada. A variável var significa que não precisamos atribuir um tipo para ela, no entando depois que ela receber o valor, só será permitido fazer transações com o mesmo tipo. 

19. Qual a diferença entre um Statefull e Stateless widget? O Stateless é um Widget estático enquanto o Statefull é mutável através da gerencia de estados.

20. Para que serve o conceito de gerenciamento de estado e como ele pode ser aplicado na prática? O Flutter é notificado pelo gerenciamento e sobre o que ele precisa redesenhar da forma mais performática possível, economizando o processamento. Uma forma simples de fazer isso é utilizando o setSate (função da classe Stateful Widget) que vem nativamente com o Flutter. 

21. Qual a finalidade dos métodos initState e dispose? O initState é chamado quando o Widget é incrementado e o dispose quando ele for removido permanetemente.
