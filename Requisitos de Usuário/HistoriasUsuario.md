
# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white" >
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Story Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como fã de RDR2, eu quero acessar uma aba de informações gerais para conhecer ou relembrar os personagens e as mecânicas principais do jogo.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>A aba deve ser acessível a partir do menu de navegação principal do site.</li><li> A página deve conter seções distintas para Personagens Principais e Mapa/Mundo.</li><li>O conteúdo deve mesclar textos curtos e imagens oficias ou capturas de tela do jogo.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <span id="ustory-02"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como jogador ativo, eu quero visualizar um feed de notícias para me manter atualizado sobre eventos da comunidade, campeonatos e anúncios.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>A página de notícias deve exibir uma lista de artigos ordenados cronologicamente (do mais recente para o mais antigo).</li><li> Cada item da lista deve mostrar: uma imagem de capa, um título, a data de publicação e um breve resumo (linha fina).</li><li> Ao clicar no card da notícia, o usuário deve ser redirecionado para a página com o conteúdo completo. </li><li> Deve existir um sistema de paginação ou rolagem infinita após exibir 10 notícias. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">7</td>
        </tr>
        <tr>
            <span id="ustory-03"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como jogador, eu quero ler as notas de atualização (patch notes) em uma área dedicada para entender rapidamente quais bugs foram corrigidos e quais mecânicas foram alteradas no jogo.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>As atualizações devem ser categorizadas e visivelmente marcadas pelo número da versão (ex: Patch 1.32).</li><li> As notas devem vir formatadas em listas de marcadores (bullet points) para facilitar a leitura dinâmica.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">4</td>
        </tr>
        <tr>
            <span id="ustory-04"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como membro da comunidade, eu quero criar uma conta e fazer login no site para ter permissão de interagir e participar das discussões no fórum.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O formulário de cadastro deve exigir: Nome de Usuário, E-mail válido e Senha (mínimo de 8 caracteres).</li><li> O sistema deve validar se o nome de usuário ou e-mail já estão em uso e exibir um erro amigável caso estejam.</li><li> O usuário deve poder fazer login utilizando E-mail e Senha.</li><li> Após o login bem-sucedido, o cabeçalho do site deve exibir o nome do usuário e a opção de "Sair" (Logout).</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">6</td>
        </tr>
        <tr>
            <span id="ustory-05"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como visitante do site, eu quero navegar e ler os tópicos do fórum para encontrar dicas e respostas para minhas dúvidas sem precisar criar uma conta.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>A aba do fórum deve ser pública e visível para usuários não logados.</li><li> A página inicial do fórum deve listar os tópicos exibindo: Título, Autor, Data da postagem e Número de respostas.</li><li>Se um usuário não logado tentar clicar em "Responder" ou "Criar Tópico", ele deve ser redirecionado para a tela de Login com a mensagem: "Faça login para participar da discussão".</li><li> Deve existir um sistema de paginação ou rolagem infinita após exibir 20 fóruns. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">10</td>
        </tr>
        <tr>
            <span id="ustory-06"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuário logado, eu quero criar novos tópicos, responder perguntas e votar em postagens (estilo Reddit) para compartilhar minhas experiências e destacar os melhores conteúdos.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O usuário autenticado deve visualizar e conseguir usar o botão "Criar Novo Tópico" e responder tópicos.</li><li> Ao criar um tópico, deve ser obrigatório inserir um Título e o Conteúdo da mensagem.</li><li> Em cada tópico e resposta, devem existir botões de Upvote (seta para cima) e Downvote (seta para baixo).</li><li> A pontuação da postagem (Upvotes - Downvotes) deve ser atualizada em tempo real ao clicar. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF08, RF09, RF12</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <span id="ustory-07"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuário do site, eu quero acessar um formulário de report para comunicar problemas técnicos do site ou relatar bugs encontrados no jogo diretamente para a administração.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O formulário deve conter um menu suspenso (dropdown) para selecionar a categoria: "Bug no Site", "Bug no Jogo" ou "Sugestão".</li><li> O formulário deve ter um campo de texto obrigatório para a "Descrição do Problema".</li><li>Deve existir um botão para anexar uma imagem/captura de tela (tamanho máximo de 5MB).</li><li>Após o envio, o sistema deve exibir um modal de sucesso com a mensagem: "Seu report foi enviado com sucesso. Obrigado por ajudar a comunidade!".</li><li> O usuário deve estar logado para reportar um problema.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Baixa</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07, RF17</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-07"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como administrador do site, eu quero ter acesso a ferramentas para realizar moderação e manutenção do site.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Deve haver uma tela para ver os reports em ordem cronológica (do mais recente para o mais antigo).</li><li>Deve ser possível acessar um report em específico, ver seus detalhes e fechar o report quando finalizado.</li><li>Deve haver opções para criação, edição e deleção de informações ou tópicos das páginas de notícias, atualizações e informações gerais</li><li>Deve haver a possibilidade de banir ou suspender um usuário que infringir as regras.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF13, RF14, RF15, RF16, RF17</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">10</td>
        </tr>
</table>

<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>

## 5. Referências bibliográficas
