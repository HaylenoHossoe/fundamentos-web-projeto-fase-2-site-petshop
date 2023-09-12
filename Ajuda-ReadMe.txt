Este arquivo de ajuda descreve as funcionalidades da página web
do petshop fictício Petnini, que foi criada em 11/09/2023 como parte de um projeto
do aluno Hayleno Santos Hossoé para a disciplina "Fundamentos de Sistemas Web",
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
	Nesta seção há um campo de pesquisa de produtos e serviços.
	Como trata-se de um site demonstrativo, não é possível comprar os produtos ou serviços,
	que são fictícios, nem pesquisá-los, pois não estão em um banco de dados.

- Seção Login e Agendamento de Serviços
	Nesta seção temos dois formulários, um para login,
	com os campos "Usuário", "Senha", "Recuperar Senha" e um botão "Enviar",
	e outro para agendar serviços, com os campos "Nome do Tutor", "Nome do Pet",
	"Serviço", "Data", "Quero tele-busca" e um botão "Enviar".
	
	Estes formuários, assim como os demais da página, são demonstrativos e,
	para que o teste de envio seja realizado, é necessário um procedimento detalhado
	ao final desta ajuda.

- Seção "Cadastro do Tutor"
	Nesta seção há um formulário de cadastro do Tutor com os campos "Nome do Tutor",
	"E-mail", "Senha", "Telefone", "Endereço" e um botão "Enviar".

- Seção "Cadastro do Pet"
	"Nesta seção há um formulário de cadastro do Pet, com os campos "Nome do Tutor",
	"Nome do Pet", "Tipo", "Temperamento", "Endereço" e um botão "Enviar".

- Seção "Depoimentos"
	Nesta seção há três depoimentos de clientes fictícios.

- Rodapé(Footer)
	Exibe informações de endereço e contatos de e-mail e WhatsApp.

>>> Como visualizar a página web e utilizá-la:

- Visualizar a página no seu navegador
	Caso você queira apenas abrir a página para visualizá-la, navegar por ela, testar seu menu,
	e preencher seus formulários, sem necessariamente enviá-los a um endereço de e-mail,
	basta você abrir o arquivo Página-Inicial.html no navegador da sua preferência.

- Teste de envio de formulários:
	Para testar o envio de formulários, você precisa utilizar um editor de códigos HTML
	para abrir o arquivo Página-Inicial.html, pesquisar pelo seguinte trecho de código:
	form action="https://formsubmit.co/your@email.com" method="POST"
	e substituir your@email.com pelo seu endereço de e-mail nas 5 ocorrências de "form action"
	que aparecem.
	Depois, você precisa instalar a extensão "Live Server" no seu VS Code e executar o arquivo
	Página-Inicial.html a partir dele.