Este arquivo de ajuda descreve as funcionalidades da página web
do petshop fictício Petnini, que foi criada em 11/09 e ajustada em 24/09/2023, como parte
de um projeto do aluno Hayleno Santos Hossoé para a disciplina "Fundamentos de Sistemas Web",
do curso de Análise e Desenvolvimento de Sistemas da faculdade PUCRS.

Também há informações sobre como você pode abrir a página web para visualizá-la
em seu navegador e testar suas funcionalidades.

>>> Principais funcionalidades da página web:

- Cabeçalho da página
	Menu de navegação principal com as opções:
	Início, Sobre, Produtos/Serviços, Login, Agendar Serviço, Cadastro, Depoimentos, Contato.

- Seção de destaque do início
	Logotipo da Petnini, solgan e foto.

- Seção "Sobre Nós"
	Texto explicativo sobre o conceito da empresa.

- Seção "Produtos e Serviços"
	Exibição de 4 produtos e 4 serviços, com fotos, descrição e preços.
	Nesta seção há um campo de busca de produtos e serviços, que está funcionando
	corretamente nesta última versão do site.
	Como trata-se de um site demonstrativo, não é possível comprar os produtos ou serviços,
	que são fictícios.

- Seção Login e Agendamento de Serviços
	Nesta seção temos dois formulários, um para login,
	com os campos "Usuário", "Senha", "Recuperar Senha" e um botão "Enviar",
	e outro formulário para agendar serviços, com os campos "Nome do Tutor", "Nome do Pet",
	"Serviço", "Data", "Quero tele-busca" e um botão "Enviar".

	* IMPORTANTE *
	Estes formuários, assim como os demais da página, são enviados para o e-mail
	que o usuário informou no campo "Usuário" do Login ou no campo "E-mail" do
	Cadastro do Cliente, utilizando o serviço Formsubmit. Veja as instruções no
	final deste arquivo de ajuda para enviar os formulários corretamente para seu e-mail.

- Seção "Cadastro do Cliente"
	Nesta seção há um formulário de cadastro do cliente com os campos "Nome do Tutor do Pet",
	"E-mail", "Senha", "Telefone", "Endereço" e um botão "Enviar".

- Seção "Cadastro do Pet"
	"Nesta seção há um formulário de cadastro do Pet, com os campos "Nome do Tutor",
	"Nome do Pet", "Tipo", "Raça, "Temperamento" e um botão "Enviar".

- Seção "Depoimentos"
	Nesta seção há três depoimentos de clientes fictícios.

- Rodapé(Footer)
	Exibe informações de endereço e contatos de e-mail e WhatsApp.
	Além disso, há informações sobre o desenvolvedor do Website, Hayleno Hossoé,
	e sobre a utilização de imagens do Canva.com e template do Nicepage.com.

>>> Como visualizar a página web e utilizá-la:

- Visualizar a página no seu navegador
	Caso você queira apenas abrir a página para visualizá-la, navegar por ela, testar seu menu,
	e preencher seus formulários, sem necessariamente enviá-los a um endereço de e-mail,
	basta você abrir o arquivo Página-Inicial.html no navegador da sua preferência.

- Testar envio dos formulários:
	Para testar o envio dos formulários, recomendamos que você utilize o editor de códigos 
	VS Code com a extensão "Live Server" instalada, para simular um servidor de páginas web.
	Em seguida, abra o arquivo Página-Inicial.html no seu VS Code e, no canto inferior direito,
	clique na opção "Go Live", que abrirá a página web do petshop no seu browser de internet.
	Dessa forma, você pode utilizar todas as funcionalidades da página do petshop e enviar
	os formuláros preenchidos para o seu e-mail.

	Todos os formulários da página são enviados para o e-mail que o usuário informou
	no campo "Usuário" do Login ou no campo "E-mail" do Cadastro do Cliente.
	
	Para envio dos formulários é utilizado o serviço Formsubmit, disponível no endereço
	https://formsubmit.co/, que é acionado automaticamente pela página do petshop.
	
	Para receber o formulário, o usuário deve apenas verificar seu e-mail e,
	na mensagem enviada pelo serviço Formsubmit, clicar em "Activate Form",
	caso ainda não o tenha ativado. Se a mensagem de ativação do serviço
	ou do formulário não tiver chegado, deve verificar sua caixa de Spam.