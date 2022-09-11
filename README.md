# Minicurso Inoa 
Olá, participante da SAEC! 
No minicurso **Construindo Aplicações com Django e Celery** vamos resolver um desafio que faz parte do processo seletivo real da INOA. Nós somos uma empresa atuante no mercado financeiro, portanto espere alguns termos bem #fariaLimer. Não se assuste, vamos destrinchar todos eles na terça-feira! 
 
## Pré-requisitos
	 
- Manjar de Python, pelo menos um pouquinho; ou 
- Manjar bem alguma outra linguagem O.O. 


## Preparando o ambiente

Pra dar tempo de concluirmos o desafio no horário estabelecido, vamos padronizar o ambiente de desenvolvimento para evitar tretas. Junto com esse README, você deve ter recebido três arquivos:
	- docker-compose.yml 
	- Dockerfile
	- requirements.txt

Não se preocupe em _entender_ estes arquivos. O Docker pode ser duro as vezes, mas vamos te explicar como deixar o ambiente prontinho. 

### No Windows 

- [ ] Instale o docker desktop https://docs.docker.com/desktop/install/windows-install/
- [ ] Copie os arquivos enviados juntos com esse readme para uma pasta de fácil acesso 
- [ ] Abra o terminal (powershell) e navegue até a pasta com os arquivos (usando o comando cd) 
- [ ] Rode o comando  
	 > docker-compose up --build
- [ ] Abra a url http://localhost:8000/ . A instalação foi bem sucedida (risos) se aparecer a mensagem	
	 > A server error occurred.  Please contact the administrator.

### No linux (debian based) 
- [ ] Instale o docker https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-pt
- [ ] Copie os arquivos enviados juntos com esse readme para uma pasta de fácil acesso 
- [ ] Abra o terminal  e navegue até a pasta com os arquivos (usando o comando cd) 
- [ ] Rode o comando  
	 > sudo docker-compose up --build
- [ ] Abra a url http://localhost:8000/ . A instalação foi bem sucedida (risos) se aparecer a mensagem	
	 > A server error occurred.  Please contact the administrator.

## O Desafio! 

O objetivo do sistema é auxiliar um investidor nas suas decisões de comprar/vender ativos. Para tal, ele deve registrar periodicamente a cotação atual de ativos da B3 e também avisar, via e-mail, caso haja oportunidade de negociação. 

## Requisitos 

- [ ] Obter periodicamente as cotações de alguma fonte pública qualquer e armazená-las, em uma periodicidade configurável para cada túnel, para consulta posterior

- [ ] Expor uma interface web para permitir consultar os preços armazenados, configurar os ativos a serem monitorados e parametrizar os túneis de preço de cada ativo e periodicidade da checagem de cada ativo

- [ ] Enviar e-mail para o investidor sugerindo Compra sempre que o preço de um ativo monitorado cruzar o seu limite inferior, e sugerindo Venda sempre que o preço de um ativo monitorado cruzar o seu limite superior

### Nos vemos na Saec!  Bora codar juntos?  
