**LabeX - Site de viagens espaciais**
Projeto desenvolvido no módulo 3 do curso de Desenvolvimento Web Front End da Labenu. Consiste em uma área pública, sem necessidade de login, o usuário poderá visualizar todas as viagens disponíveis e se desejar, se inscrever para alguma delas. A área privada mantem todos os dados administrativos, sendo possivel criar novas viagens e decidir se os candidatos serão ou não aprovados para a viagem.

**SURGE**: https://stimulating-map.surge.sh/

------ O que funciona ----

**Área pública:**
O usuário terá acesso a todas as viagem interplanetária disponíveis no momento, será possivel obter as seguintes informações:
a) Nome da viagem;
b) Planeta de destino;
c) Duração em dias;
d) Data de decolagem.
Caso o usuário tenha interesse, poderá se cadastrar para a viagem selecionada através do formulário (botão inscreva-se):
Ao finalizar a candidatura uma caixa de alerta irá informar se os dados foram recebidos com sucesso:
Caso tenha algum erro, um alert irá aparecer informando que não foi possivel realizar o cadastro.

**Área privada:**
Para ter acesso a essa parte é necessário que o usuário tenha acesso permitido com seu e-mail e senha.
E-mail para acesso: brunacarvalholamarr@email.com
Senha para acesso: 123456
Caso o usuário não tenha permissão, uma caixa de alerta irá informa-lo.

**Painel administrativo:**
É possivel verificar todas as viagens que já foram criadas, e também exclui-las através do botão da lixeira.
Ao selecionar que a viagem deve ser excluida, será renderizado um modal para confirmar essa ação.
Ao clicar no nome da viagem, o usuário será redirecionado para uma página com todas as informações atualizadas:
* Dados da viagem
* Candidatos (decidir se o mesmo será ou não aprovado)
* Lista com o nome dos candidatos já aprovados.

**Criar viagem**
É necessário preencher todos os dados do formulário para dar continuidade.
Um alert também será renderizado caso a viagem seja cadastrada ou não.


-------O que não funciona----------
Ao clicar em logout, o usuário não é deslogado.


