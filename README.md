**LabeX - Site de viagens espaciais**
Projeto desenvolvido no módulo 3 do curso de Desenvolvimento Web Front End da Labenu. Consiste em uma área pública, sem necessidade de login, o usuário poderá visualizar todas as viagens disponíveis e se desejar, se inscrever para alguma delas. A área privada mantem todos os dados administrativos, sendo possivel criar novas viagens e decidir se os candidatos serão ou não aprovados para a viagem.

**SURGE**: https://stimulating-map.surge.sh/

<h2>O que funciona no projeto:</h2>

<h3>Área pública:</h3>
<p>O usuário terá acesso a todas as viagem interplanetária disponíveis no momento, será possivel obter as seguintes informações:</p>
<p>a) Nome da viagem;</p>
<p>b) Planeta de destino;</p>
<p>c) Duração em dias;</p>
<p>d) Data de decolagem. </p>
<p>Caso o usuário tenha interesse, poderá se cadastrar para a viagem selecionada através do formulário (botão inscreva-se).
Ao finalizar a candidatura uma caixa de alerta irá informar se os dados foram recebidos com sucesso: </p>
<img src="https://user-images.githubusercontent.com/102433664/191648758-6fdc2b27-66ab-405d-9eab-f033346f4153.png" />
<p>Caso tenha algum erro, um alert irá aparecer informando que não foi possivel realizar o cadastro. </p>


<h3>Área privada:</h3>
<p> Para ter acesso a essa parte é necessário que o usuário tenha acesso permitido com seu e-mail e senha.<p>
<p> <strong>E-mail para acesso: brunacarvalholamarr@email.com </strong></p>
<p> <strong>Senha para acesso: 123456 </strong> </p>
Caso o usuário não tenha permissão, uma caixa de alerta irá informa-lo:
<img src= "https://user-images.githubusercontent.com/102433664/191649189-84a62e5a-7df9-466d-a603-50e89a9f843b.png" />


**Painel administrativo:**
<p>É possivel verificar todas as viagens que já foram criadas, e também exclui-las através do botão da lixeira.</p>
</p> Ao selecionar que a viagem deve ser excluida, será renderizado um modal para confirmar essa ação. </p>
<div display="flex">
  <img height="400px" src="https://user-images.githubusercontent.com/102433664/191649821-4b0b71e2-bf8f-467e-93a6-b6bde54ce42c.png" />
  <img height="400px" src="https://user-images.githubusercontent.com/102433664/191650055-681ec4fc-5438-4426-9013-acf99eea4b0a.png" />
</div>


Ao clicar no nome da viagem, o usuário será redirecionado para uma página com todas as informações atualizadas:
<p> <li> Dados da viagem </li> </p>
<p>  <li> Candidatos (decidir se o mesmo será ou não aprovado) </li></p>
<p>  <li> Lista com o nome dos candidatos já aprovados. </li> </p>
<img height="400px" src="https://user-images.githubusercontent.com/102433664/191650302-999893fc-f234-4b64-a740-6745b6baffeb.png" />


**Criar viagem:**
<p>É necessário preencher todos os dados do formulário para dar continuidade.
Um alert também será renderizado caso a viagem seja cadastrada ou não. </p>


<h2>O que não funciona:</h2>
Ao clicar em logout, o usuário não é deslogado.


