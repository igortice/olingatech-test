# Olinga Tech - Teste de nível para vagas de TI

## Sobre:

Esse repositório tem como objetivo avaliar candidatos para vagas de **junior**, **pleno** e **senior** para empresa
Olinga Tech.

Nesse teste o usuário vai ser levado a resolver problemas que são encontrados no dia a dia da empresa.

## Pré-requisitos:
- **Lógica de Programação**
- **Rails** v6.1.5
- **Ruby** v2.7.6
- **RVM**
- **Postgres SQL** v14.*
- **Node** v16.15.*
- **Yard** v1.22.*

<small>
    Obs: As versões acima são as que foram usadas para desenvolver o projeto, logo não é obrigatório o conhecimento
    dessas versões, mas é bom que use esta para fins de bom funcionamento e avaliação do projeto.
</small>

## Requisitos do Projeto:

> O teste consiste em um sistema de Visualizações de Posts, Comentários e Likes feita por Usuários cadastrados.
> 
> Todos os Posts são públicos e ficam em um rota que TODOS(cadastrados/não cadastrados) podem visualizar esses Posts.
> 
> Essa rota de Posts públicos só mostram Posts que foram publicados por Usuários Cadastrados.
> 
> O Usuário cadastrado vai ter uma região no qual ele pode fazer CRUD de seus POSTS.
> 
> Essa região mostra apenas os seus Posts com os seguintes campos:
> - Id
> - Status do Post
> - Titulo do Post
> - Data da Criação
> - Data da Publicação
> - Total de Comentários
> - Total de Likes
> - Ações
>   - Publicar/Des-Publicar
>   - Editar
>   - Deletar
>   - Visualizar
> 
> Essa região também possui um busca pelo título do Post.
> 
> Todos os Posts podem sofrer Comentários e/ou Likes apenas por Usuários cadastrados.
> 
> Comentários e Likes só podem aparecer na região vinda de Posts Públicos.
> 
> Cada Usuário cadastrado só pode fazer um Comentário e/ou um Like em cada Post e ele não pode fazer isso para os Posts
> dele.
> 
> Usuários cadastrados só podem publicar 2 Posts por dia.
> 
> O Usuário cadastrado só pode Editar e Deletar os Posts que ele criou.
> 
> Quando um Post for deletado, os Comentários e os Likes devem ser excluidos juntos com o Post.
> 
> O Usuário também tem permissão para Desfazer um Like ou um Comentário em um Post que ele criou.
> 
> O Usuário Admin possui uma região de DashBoard para ver dados gerencias no qual só ele pode acessar.
> 
> O DashBoard do Admin mostra:
> - total de Posts criados por semana, mes e dia.
> - total de Comentários criados por semana, mes e dia.
> - total de Likes criados por semana, mes e dia.
> - total de Usuários novos por semana mes, e dia.
> 
> O Admin tem um região que mostra todos os posts publicados com os seguintes colunas:
> - Id
> - Status do Post
> - Titulo do Post
> - Data da Criação
> - Data da Publicação
> - Total de Comentários
> - Total de Likes
> - Ações
>   - Des-Publicar
>   - Visualizar
>
> Essa região também possui um busca pelo título do Post.
> 
> Quando o Admin fizer uma Des-Publicação, o Post não é Deletado, mas ele deve desaparecer tanto para o Usuário que 
> criou quanto da região de Posts Públicos.


## Tarefas:

- [ ] baixe a aplicação do repositório.
- [ ] configure seu ambiente de trabalho para usar o os pre-requisitos listados acima.
- [ ] execute o dump do banco em ./db para iniciar a base de dados do projeto.
- [ ] 
- [ ]
