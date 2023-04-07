# Arquitetura

Arquitetura de projeto em React JS utilizando Styled Components 
composto pelas páginas e seus caminhos:

Página inicial:
	Sobre
	Produto
		Solicitação do produto
			Solicitação
				Confirmação
	Confirmação de E-mail
	404


Arquitetura:


	src
		assets
		components
			texts
			containers
				containers
				content
		styles
			theme
		pages	
			Home
				EmailSucess
				Acess
					Generate
						GenerateSucess
				About
				404

Comando:

mkdir src; mkdir src/assets; mkdir src/components; mkdir src/components/texts; type nul > src/components/Texts.jsx; mkdir src/components/containers; type nul > src/components/containers/Containers.jsx; mkdir src/components/content; type nul > src/components/content/Grid.jsx; type nul > src/components/content/Divs.jsx; mkdir src/styles; type nul > src/styles/Theme.jsx; mkdir src/pages; mkdir src/pages/home; type nul >  src/pages/home/index.js; mkdir src/pages/Home/EmailSucess; type nul > src/pages/Home/EmailSucess/index.jsx; mkdir src/pages/Home/Acess; type nul > src/pages/Home/Acess/Acess; mkdir src/pages/Home/Acess/AcessRequest; type nul > src/pages/Home/Acess/AcessRequest/index.js; mkdir src/pages/Home/Acess/AcessRequest/RequestSucess; type nul > src/pages/Home/Acess/AcessRequest/RequestSucess/index.jsx; mkdir src/pages/Home/About; type nul > src/pages/Home/About/index.jsx; mkdir src/pages/Home/404; type nul > mkdir src/pages/Home/404; 
