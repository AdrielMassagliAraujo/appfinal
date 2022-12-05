DUPLA: Adriel Massagli de Araujo

Ao entrar no aplicativo nos deparamos com a tela de login, onde o usuario fornece o nome de usuario e senha, 
logo embaixo ao botão de login aparecerá o nome o usuário cadastrado usando o SharedPreferences. Logo após entrar no app
no canto superior direito vemos o nome do usuário, onde futuramente será o a tela de usuário. 
Ao clicar no logo de Todo mundo odeia o Chris, aparecerá uma tela que contém uma lista dos personagens principais do seriado
nessa lista foi usado o banco de dados SQLite com os dados pré definidos na programação do app.

Contem informações sobre a historia e personagens, além disso há uma intent 
que te leva para o google maps para conhecer o estado de Nova Iorque onde vive a famosa família Rock. Nesse aplicativo encontra-se 
também uma pequena brincadeira usando o sensor de proximidade.

Conceitos:

Activity - São as telas do projetos.
Views - São os elementos gráficos do projeto (ex:botões, imagens, texto, etc).
Intents Explícitos - Direciona-nos para uma outra activity, usado na maioria dos botões encontrados no projeto.
Intents Implícitos - Direciona-nos para um outro aplicativo, usado para direcionar o google, telefone etc.
Sensores - O sensor sempre que utilizado gera um certo valor, esse valor pode ser usado para formar condições. No caso desse projeto, foi usado o sensor de proximidade, e dependendo do valor ele muda a imagem.
SharedPreferences - Informações que são gravadas no aparelho o usuário e pode ser acessada a qualquer momento na Activity. Usado na tela de login.
Banco de Dados SQlite - Usado para mostrar os persagens listados na tela. Os dados foram pré estabelecidos na programação.
