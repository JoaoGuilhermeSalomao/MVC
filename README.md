# 1. Informações do Projeto
## 1.1. Nome
Abandono Zero

## 1.2. Descrição
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O projeto "Abandono Zero", desenvolvido pelo grupo Datadogs em parceria com o Instituto Nacional de Psicologia e Saúde Animal (INSPA), concentra-se no desenvolvimento de uma plataforma web. Esta plataforma visa coletar informações cruciais sobre os motivos que levam à adoção, compra e ao abandono de animais, bem como detalhes sobre o ambiente em que esses animais vivem.

## 1.3. Arquitetura
MVC (Model-View-Controller) 

## 1.4. Ferramenta de Diagramação
<a href="https://drive.google.com/file/d/1SEJPzJZil3Yw_3gvtmUR4argtEx2WM9o/view?usp=sharing">draw.io</a> <br> 

# 2. Modelos (Models):
Responsável por representar os dados do sistema e a lógica de negócios. <br><br>
**Users** - Recebe as informações do usuário e as envia para o banco de dados <br>
**Questionário** - Seleciona o formulário escolhido pelo usuário <br>
**Respostas** - Recebe as respostas do usuário <br>
**UserAdmin** - Recebe as informações do admin e as envia para o banco de dados <br>
**RespostasAdmin** - Resgata as respostas dos usuários <br>
**Filtros** - Filtra as respostas por região (país, estado, cidade, bairro) <br>


# 3. Controladores (Controllers)
O Controlador atua como um intermediário entre o Modelo e a Visão, recebendo as solicitações do usuário, interage com o Modelo para obter os dados necessários e os envia para a Visão para exibição. <br><br>
**Gravar** - Grava os dados no Banco de Dados <br>
**Procurar** - Procura os dados inseridos no Banco de Dados <br>
**Selecionar** - Seleciona algum tópico que será exibido do View <br>
**Exibir** - Exibi a informação ao usuário <br>

 
# 4. Views (Views)
A Visão é responsável pela apresentação dos dados ao usuário.

## 4.1. Users
**Header** - Cabeçalho do site <br>
**Sign In** - Espaço destinado para criar uma conta no site<br>
**Login** - Espaço destinado para o usuário acessar a sua conta<br>
**Seleção de questionário** - Espaço para o usuário selecionar qual dos 4 questionários disponíveis se encaixa na realidade dele para responder<br>
**Perguntas** - Espaço onde aparecem as perguntas do questionário e o espaço para que o usuário as responda<br>

## 4.2. Admin
**Header** - Cabeçalho do site<br>
**Login** - Espaço destinado para o admin acessar a sua conta<br>
**Seleção de questionário** - Espaço destinado para o admin selecionar qual dos questionário ele deseja ver as respostas<br>
**Filtro** - Local onde o admin consegue filtrar as respostas do questionário selecionado por região (país, estado, cidade, bairro)<br>
**Respostas** - Local onde as respostas são exibidas para o admin de acordo com os filtros selecionados<br>

# 5. Infraestrutura 
## 5.1. Banco de Dados
O banco de dados desempenha um papel fundamental no projeto "Abandono Zero", impactando-o de várias maneiras: <br>
<br>
**Armazenamento de Dados** - O banco de dados é o local onde todas as informações coletadas através do formulário da plataforma são armazenadas. Isso inclui dados sobre os motivos de adoção, compra e abandono de animais, bem como detalhes sobre o ambiente em que esses animais estão inseridos. A escolha de um banco de dados relacional oferece uma estrutura organizada para armazenar e gerenciar esses dados de forma eficiente. <br>
**Consistência e Integridade** -  Um banco de dados relacional garante a precisão, completude e integridade dos dados, fornecendo uma base confiável para análises e conclusões. <br>
**Recuperação de Dados** - Facilita a recuperação dos dados para análises posteriores, essencial para entender tendências e desenvolver estratégias eficazes. <br>
**Segurança dos Dados** - Implementa medidas de segurança para proteger os dados contra acesso não autorizado e garantir conformidade com regulamentações de privacidade. <br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Em resumo, o banco de dados desempenha um papel de extrema importância no projeto "Abandono Zero", impactando o armazenamento, a integridade e a segurança dpos dados.


### 5.2.1. Integração com o MVC


# 6. Recursos Adicionais:<br> 
Documentação do Sails.js: https://github.com/balderdashy/sails <br> 
Tutorial do draw.io: https://m.youtube.com/watch?v=w3zm-wbmlpc <br> 
Exemplos de diagramas MVC: https://www.lucidchart.com/pages/templates
