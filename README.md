# Desenvolvimento e Entrega da 3ª Sprint - Dynamic Programming 

**Nomes + RM dos integrantes:**
- Guilherme Morais - 551981
- Lorenzo Ferreira - 97318
- Luan Silveira Macea - 98290
- Gabriel Doms - 98630
- Bruno Eduardo - 558303

**Turma:** 2ESPW

**Ano:** 2024
___
## Descrição do Projeto
O Laboratório de Ensino, Pesquisa e Inovação em Cirurgia (LEPIC) em
parceria com a FIAP, busca de novas tecnologias para aprimorar o
desenvolvimento dos alunos de medicina de maneira virtual, através de
tecnologias como realidade virtual, os alunos podem simular procedimentos em
ambientes virtuais realistas, receber feedback personalizado e treinar com
simuladores robóticos, aprimorando suas habilidades de forma mais rápida,
segura e acessível, buscando otimizar o aprendizado, e preparar os futuros
profissionais para os desafios da prática médica com excelência
___
## Desenvolvimento do Projeto
O projeto foi desenvolvido utilizando Jupyter Notebook, para a estruturação do código, juntamente com
aplicação de uma base de dados Oracle SQL, e outras bibliotecas para criação de widgets e funcionalidades dos componentes.

O site do projeto é composto por:
  - Cadastro
  - Login
  - Gerenciamento
    
Todo o sistema de cadastro e login em widgets dentro das celulas do notebook, é feito para recorrer a operações de armazenamento na base de dados nomeada com o acronimo CRUD(Create, Read, Update, Delete) usando como base a tabela usuario
___
## Como executar o projeto
O codigo pode ser executado usando o site "google colab" que hospeda uma versão web de python, conjuntamente com algumas bibliotecas extras ja inclusas no "google colab" e um arquivo de driver "ojdbc8.jar"(anexado no zip) para conectar a base de dados Oracle

Alternativamente pode se executar o codigo na propria maquina do usuario caso haja extensões e bibliotecas python, jupyter, ipywidgets, IPython, jaydebeapi JPype1 e alterando a fonte para o carregamento do driver "ojdbc8.jar" para o caminho no seu computador.

Uma vez que os arquivos estão presentes na máquina, é necessário apenas executar as celular em ordem e utilizar os sistemas localiziados no fim do codigo, caso haja necessidade a função "read_user()" mostrara todas as informaçoes da base de dados(sendo todos os dados de usuarios ficticios pois na ha garantia de segurança).
_____
