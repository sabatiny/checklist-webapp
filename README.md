
<h1>CheckList para aplicações web</h1>
Aqui estão algumas dicas para os desenvolvedores darem uma verificada antes sua aplicação ser pública.
<h2>User Experience</h2>
<h3>Home page</h3>
<ul>
<li>Os usuários sabem o que fazer. Eles entendem a proposta e propósito do site(rápido).</li>
<li>Primeira impressão. A página inicial cria uma primeira impressão positiva e suporta conversão.</li>
<li>Registrado o nome de usuário ao se logar é exibido no site ,por exemplo. "Olá , Charles ", não " Olá, senhor" .</li>
<li>As principais mudanças no site são anunciados na página inicial.</li>
<li>Localização da empresa e informações de contato é facilmente acessível a partir da página inicial.</li>
<li>Existe uma política de privacidade , caso o site reúna informações sobre os usuários .</li>
<li>URL do site URL funciona com ou sem www. Por exemplo " www.qualquercoisa.com " e " qualquercoisa.com " .</li>
<li>Meta dados foi incluído e é apropriado.</li>
<li>Favicon foi criado e exibe corretamente.</li>
<li>Rodapé inclui direitos de autor e link para o site criador.</li>
<li>Ícones de compartilhamento de mídia social estão funcionando corretamente.</li>
<li>Feeds estão funcionando corretamente (RSS, notícias, mídia social).</li>
</ul>
<h3>Navegação</h3>
<ul>
<li>Os usuários sabem onde eles estão no site . Por exemplo, com a utilização de migalhas de pão . Além disso, existe um mapa do site .</li>
<li>A navegação é consistente em todas as páginas .</li>
<li>Os links são auto-descritivo. Não há links ”clique aqui" .</li>
<li>Há uma descrição do site no título da janela , que é facilmente compreensível como um marcador.</li>
<li>URL do site é memorável. : )</li>
</ul>
<h3>Busca</h3>
<ul>
<li>Há uma barra de pesquisa , no caso de um grande site .</li>
<li>A busca está disponível em todas as páginas , não apenas na homepage.</li>
<li>A caixa de pesquisa é grande o suficiente , de modo que os usuários possam ver o que eles estão digitado.</li>
<li>Pesquisa é uma forma onde os usuários possam digitar palavras de busca imediatamente , e não um link.</li>
</ul>
<h3>Links</h3>
<ul>
<li>Comandos importantes são apresentados como botões, e não links . Por exemplo, " Comprar" ou " Pagar” é um botão , não um link.</li>
<li>Os links são facilmente reconhecíveis. Eles parecem clicáveis. Itens que não são ligações não devem parecer clicável , por exemplo, texto sublinhado deve ser evitado.</li>
<li>Cores. Links visitados são diferentes dos que não foram visitados</li>
<li>Não há links quebrados.</li>
</ul>
<h3>Layout</h3>
<ul>
<li>Conteúdos importantes são exibidos primeiro</li>
<li>Site é responsivo. Trabalha com diferentes tamanhos de tela . Não há rolagem horizontal.</li>
<li>Informações relacionadas são agrupadas de forma clara.</li>
<li>Há uma quantidade mínima de janelas pop-up .</li>
<li>Consistência. layouts de páginas são consistentes em todo o site .</li>
<li>As páginas não são desordenadas . Há espaço em branco suficiente para suportar a digitalização.</li>
</ul>
<h3>Errors</h3>
<ul>
<li>Compatibilidade do navegador . Site funciona em vários browsers.</li>
<li>Testes com usuários . Testes com público-alvo deve ser feito em diferentes fases do projeto . Pessoas que não estão envolvidos no desenvolvimento do teste local. Use , por exemplo, para começar com o teste de usuário.</li>
<li>Páginas de erros são customizadas </li>
<li>Segurança. Site tem um certificado SSL. </li>
</ul>
<h3>Forms</h3>
<ul>
<li>Simplicidade. Apenas absolutamente perguntas necessárias são solicitados em formulários.</li>
<li>Menus longos suspensas são evitados. Em vez disso os usuários podem inserir texto , que é validado no backend . Além disso, longos menus suspensos são propenso a erros para os usuários de rolagem com o mouse.</li>
<li>Os campos são rotulados com termos comuns , por exemplo, Nome, endereço (suporta preenchimento automático ) .</li>
<li>Envio de formulários é confirmado por exemplo uma página de confirmação .</li>
<li>As mensagens de erro são mostrados ao lado do campo de entrada , não apenas no topo da página </li>
</ul>
<h3>Conteúdo</h3>
<ul>
<li>Contraste. Há contraste suficiente entre o texto e o fundo.</li>
<li>O conteúdo é simples. Há parágrafos curtos , cabeçalhos descritivos , listas e imagens. conteúdo visual é usado , quando apropriado , em vez de grandes quantidades de texto .</li>
<li>O conteúdo é escrito com linguagem comum que os usuários entendam facilmente. </li>
<li>Contato e informações sobre a empresa é claramente visível . Ao clicar no link de contato não abre automaticamente um aplicativo de email .</li>
<li>O conteúdo é útil , fornecendo respostas às perguntas mais comuns feitas pelos usuários. Não há instruções longas ou "Bem-vindo ao nosso site" texto.</li>
<li>O uso de Uppercase em texto é evitado.</li>
</ul>
<h2>Segurança</h2>
<ul>
<li>Verificar se o sistema e os dados são acessados de maneira segura, apenas pelo autor das ações.</li>
<li>Use SSL / HTTPS para o login e todas as páginas em que os dados importantes são inseridos (como informações de cartão de crédito).</li>
<li>Evite ataques<a href="https://en.wikipedia.org/wiki/Cross-site_scripting"> cross site scripting</a> (XSS).</li>
<li>Evite ataques<a href="https://en.wikipedia.org/wiki/Cross-site_scripting"> cross site request forgeries</a> (CSRF).</li>
<li>Certifique-se de suas informações de conexão do banco de dados é garantido.
Mantenha-se informado sobre as últimas técnicas de ataque e vulnerabilidades que podem afetar sua plataforma.</li>
</ul>
<h2>Perfomance</h2>
<ul>
<li> Criação de simulações de uso da aplicação (tempo de resposta sobre picos e médias de carga) </li>
<li>Otimize imagens - não use uma imagem de 20 KB para um fundo de repetição.</li>
<li>Saiba como usar gzip na sua aplicação usa o gzip, você pode verificar <a href="http://gzipwtf.com/">aqui</a>.</li>
<li>Minimizar o número total de solicitações HTTP necessários para um navegador para renderizar a página.</li>
<li>Certifique-se de que há um arquivo favicon.ico na raiz do site, ou seja, /favicon.ico. Navegadores irá solicitá-lo automaticamente, mesmo se o ícone não é mencionado no HTML em tudo. Se você não tiver um /favicon.ico, isso irá resultar em um monte de 404s, drenando a largura de banda do seu servidor.</li>
</ul>
<h2>Controle de qualidade</h2>
<ul>
<li>Verificar ortografia das mensagens e dos campos.</li>
<li>Verificar se campos de radio button excludentes não podem ser marcados ao mesmo tempo.</li>
<li>Verificar layout do sistema, tentar manter a aparência mais parecida possível com o protótipo. Além disso deve-se verificar se os campos e tabelas estão alinhados com relação aos outros campos.</li>
<li>Ficar atento aos erros de javascript.</li>
<li>No exibir, deve-se ficar muito atento à consistência dos dados, poe exemplo se um dado foi inserido no cadastro ele deve obrigatoriamente aparecer no Exibir com sua respectiva máscara.</li>
<li>Deve-se estar ciente qual o valor que deve ser exibido no caso de um campo não ter sido preenchido. Às vezes deve aparecer o campo vazio outras vezes deve aparecer algum caracter.</li>
<li>Quando houver uma tabela em que seja possível inserir e remover dados dela antes de cadastrar, realizar testes de carga para ver se os dados estão sendo mantidos/removidos corretamente.</li>
<li>Ortografia: Verificar a ortografia de todo e qualquer texto do sistema, inclusive de mensagens de alerta.</li>
<li>Integridade dos dados: Verificar no banco de dados se os valores foram atualizados ou excluídos corretamente.</li>
<li>Autenticação: Quando o sistema possui autenticação do usuário, é importante criar casos de testes para não permitir que um usuário não autenticado acesse o sistema.</li>
<li>Clique duplo: Verifique o comportamento do sistema quando o usuário clica duas vezes no botão Salvar. Neste caso, o sistema não deve incluir 2 registros.</li>
<li>Tempo de processamento: Verificar o tempo de processamento para carregar uma página ou um combo box não ultrapassa o tempo máximo esperado. No caso de listas, pode ser necessário incluir paginação para melhorar o tempo de processamento.</li>
<li>Alerta de Confirmação: É importante que hajam alertas de confirmação em botões cuja ação é de excluir ou cancelar uma operação. Criar casos de teste que verifiquem se ao clicar em 'Não', o sistema realmente Não Exclui ou Não Cancela a operação.</li>
</ul>
<h3>Alterações de campos</h3>
<ul>
<li>Verificar na tela de exibição se todos os dados alterados foram exibidos corretamente na tela, inclusive ficar atento às máscaras.</li>
<li>Verificar se os campos atualizados foram realmente atualizados. Esta verificação deve ser feita tanto no exibir quanto na tela de alteração.</li>
<li>Verificar se na tela de alteração se todos os campos foram carregados corretamente.</li>
<li>Executar o fluxo de alteração mais de uma vez, para garantir que nenhum dado esteja sendo mantido na sessão.</li>
<li>Verificar a atualização de campos que fazem parte de pop-up. Pois muitas vezes as alterações que são feitas dentro do pop-up se perdem ao fechar a janela.</li>
<li>Ao confirmar a operação de atualização, verificar se apareceu uma mensagem informando que o item foi atualizado</li>
<li>Verificar se ao chamar algum pop-up se ao fechar a janela, o fluxo continua no modo de alteração.</li>
<li>Tentar excluir um registro, no alert de confirmação clicar em Cancelar e depois verificar se o registro não foi excluído.</li>
<li>Realizar uma pesquisar e verificar se a exclusão foi realizada realmente.</li>
<li>Verificar se apareceu uma mensagem informando que o item foi excluído.</li>
</ul>

<h3>Inputs</h3>
<ul>
<li>Preencher os campos de texto com caracteres especiais e/ou caracteres inválidos.</li>
<li>Caracteres especiais: É importante criar casos de teste que verifiquem o comportamento do sistema quando são inseridos em campos de texto um link ou uma imagem. Pois, se o sistema processar o código HTML inserido, o link pode ser direcionado para um vírus ou para imagem indevida.</li>
<li>Verificar se os dados cadastrados/atualizados nos pop-up estão corretos.</li>
<li>Campos obrigatórios: os campos obrigatórios estão sendo corretamente tratados. Por exemplo: Verificar se ao deixar um campo obrigatório em branco se está aparecendo a mensagem.</li>
<li>Preencher campos formulários por exemplo(login) tentar fazer cadastro com os mesmos dados(CPF)</li>
<li>Máscara: Verificar se os campos estão sendo preenchidos com suas respectivas máscaras. </li>
<li>Valores permitidos: Verificar se os campos estão sendo validados no caso de receberem valores não permitidos. Por exemplo: campos numéricos não devem aceitar caracteres especiais e/ou letras.</li>
<li>Valores nulos: Verificar se um campo que só pode aceitar valor maior que zero, se estão aceitando valor menor ou igual a zero.</li>
<li>Valores limite: Verificar qual o valor máximo e mínimo permitido para certo campo. Testar se ao inserir um valor fora do limite se está aparecendo a devida mensagem.</li>
<li>Validação de campos (Data, CPF, CNPJ): Verificar se foi digitado uma data, CPF ou CNPJ válido.</li>
<li>Espaços em branco: Num campo obrigatório, preencher com espaços em branco e verificar se o sistema detectou que o campo estava vazio.</li>
</ul>
<h3>Mailers</h3>
<ul>
<li>Receber mailers</li>
<li>Verificar mudança de senha (tem sempre que saber se ao mudar a senha o usuário pode colocar a mesma senha anterior)</li>
<li>Botão de esqueci a senha (mailers)</li>
<li>Mailers são simples e traduzidos</li>
<li>Links de mailers estão corretos</li>
</ul>
<h2>Teste Funcional</h2>
<ul>
<li>Testa os requisitos funcionais, as funções e os casos de uso. A aplicação faz o que deveria fazer ?(Aqui deve se ter mente sobre as funcionalidade da aplicação e testa-las individualmente ,por exemplo :bate-papo)</li>
</ul>
<h2>Teste de Regressão </h2>
<ul>
<li>Tem como propósito garantir que os defeitos encontrados foram corrigidos e que as correções ou inserções de novos códigos em determinados locais do software não afetaram outras partes inalteradas do produto. Trata de re-testar o teste.</li>
</ul>

