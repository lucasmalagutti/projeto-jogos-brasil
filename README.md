Projeto: Buscador de Momentos Históricos do Futebol Brasileiro
Descrição:

Este projeto web permite que os usuários busquem por momentos históricos de jogos da Seleção Brasileira. Ao digitar o nome da partida (por exemplo, "Brasil x Itália 1994"), o usuário é apresentado com uma lista de vídeos relacionados, facilitando o acesso a esses momentos marcantes.

Funcionalidades:

Busca por jogos: O usuário pode pesquisar por jogos utilizando palavras-chave como nome das equipes, ano e outros termos relevantes.
Exibição de resultados: Os resultados da pesquisa são apresentados em uma lista, com o título do jogo, uma breve descrição e um link para o vídeo completo no YouTube.
Interface simples e intuitiva: A interface do usuário foi projetada para ser fácil de usar, com um campo de pesquisa e uma seção para exibir os resultados.
Tecnologias Utilizadas:

HTML: Estrutura básica da página web.
CSS: Estilização da página, definindo a aparência visual dos elementos.
JavaScript: Lógica do aplicativo, responsável por realizar a pesquisa, manipular o DOM e exibir os resultados.
Como funciona:

Interface: O usuário interage com a página através de um campo de pesquisa e um botão.
Pesquisa: Ao clicar no botão, o JavaScript coleta o termo de pesquisa e o compara com os dados armazenados em um arquivo JavaScript externo (dados.js).
Resultados: Se houver correspondência, o JavaScript gera o HTML para exibir os resultados da pesquisa, incluindo o título do jogo, a descrição e o link para o vídeo.
Exibição: O HTML gerado é inserido na seção de resultados da página, atualizando o conteúdo dinamicamente.
Estrutura de arquivos:

index.html: Arquivo principal da página web.
style.css: Arquivo CSS para estilizar a página.
dados.js: Arquivo JavaScript contendo os dados dos jogos, como título, descrição, tags e link para o vídeo.
app.js: Arquivo JavaScript com a lógica principal do aplicativo, responsável pela pesquisa e exibição dos resultados.
