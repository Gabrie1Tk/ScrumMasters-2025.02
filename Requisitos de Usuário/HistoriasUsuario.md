<table>
  <thead>
    <tr style="background-color: purple; color: white">
      <th style="border-style:solid; border-width:1px; text-align:center">ID</th>
      <th style="border-style:solid; border-width:1px; text-align:center">História de Usuário</th>
      <th style="border-style:solid; border-width:1px; text-align:center">Critérios de aceitação</th>
      <th style="border-style:solid; border-width:1px; text-align:center">Prioridade</th>
      <th style="border-style:solid; border-width:1px; text-align:center">RF/RNF relacionado</th>
      <th style="border-style:solid; border-width:1px; text-align:center">Story Points</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">US01</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Eu, como Jogador, quero responder a um quiz de múltipla escolha para testar meus conhecimentos e ganhar pontos.</td>
      <td style="border-style:solid; border-width:1px; text-align:left; vertical-align:middle">
        <ol>
          <li>O sistema deve exibir uma pergunta por vez, com pelo menos 4 alternativas de resposta.</li>
          <li>O jogador deve poder selecionar apenas uma alternativa antes de submeter.</li>
          <li>Ao submeter a resposta, o sistema deve informar imediatamente se a resposta estava correta ou incorreta.</li>
          <li>Se a resposta estiver correta, a pontuação do jogador para a partida atual deve ser incrementada.</li>
          <li>O sistema deve exibir um botão "Próxima" para avançar para a próxima pergunta após o feedback.</li>
        </ol>
      </td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Alta</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">RF01</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">8</td>
    </tr>
    <tr>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">US02</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Eu, como Jogador, quero visualizar um ranking com as melhores pontuações para me situar em relação a outros jogadores.</td>
      <td style="border-style:solid; border-width:1px; text-align:left; vertical-align:middle">
        <ol>
          <li>O ranking deve ser acessível a partir de uma opção clara no menu principal.</li>
          <li>A tela de ranking deve listar os top 6 jogadores, ordenados pela pontuação mais alta.</li>
          <li>Cada entrada no ranking deve exibir o nome do jogador e sua pontuação.</li>
          <li>Se o usuário logado estiver entre os 6 primeiros, sua posição deve estar destacada visualmente.</li>
          <li>Se o usuário logado não estiver no top 6, deve haver uma seção mostrando "Sua Posição: [posição] - [pontuação]".</li>
        </ol>
      </td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Média</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">RF03</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">5</td>
    </tr>
    <tr>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">US03</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Eu, como Administrador, quero criar uma nova pergunta de múltipla escolha com sua resposta correta para expandir o banco de questões.</td>
      <td style="border-style:solid; border-width:1px; text-align:left; vertical-align:middle">
        <ol>
          <li>Deve haver uma seção administrativa segura, acessível apenas com login e senha de administrador.</li>
          <li>O formulário de criação deve conter campos para: enunciado, pelo menos 4 alternativas, e a marcação da alternativa correta.</li>
          <li>O sistema deve validar se todos os campos foram preenchidos e se uma alternativa correta foi selecionada.</li>
          <li>Após a submissão bem-sucedida, o sistema deve exibir uma mensagem de confirmação.</li>
        </ol>
      </td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Alta</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">RF04</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">8</td>
    </tr>
    <tr>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">US04</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Eu, como Administrador, quero visualizar, editar e excluir perguntas existentes para manter a qualidade do conteúdo.</td>
      <td style="border-style:solid; border-width:1px; text-align:left; vertical-align:middle">
        <ol>
          <li>A interface de gerenciamento deve listar todas as perguntas em um formato de lista ou tabela.</li>
          <li>O administrador deve poder filtrar ou buscar perguntas por palavras-chave do enunciado.</li>
          <li>Deve haver um botão "Editar" que abre um formulário pré-preenchido com os dados atuais.</li>
          <li>Deve haver um botão "Excluir" que solicita uma confirmação antes de remover a pergunta.</li>
          <li>Qualquer alteração deve ser salva e refletida imediatamente nos quizzes futuros.</li>
        </ol>
      </td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">Média</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">RF04</td>
      <td style="border-style:solid; border-width:1px; text-align:center; vertical-align:middle">8</td>
    </tr>
  </tbody>
</table>

<div style="text-align: center">
  <p>Tabela 3: Histórias de Usuário para o Aplicativo de Quiz Educacional</p>
</div>

