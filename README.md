# Gerenciamento de Estoque

`ANÁLISE E DESENVOLVIMENTO DE SISTEMAS`

`Eixo 2 - Desenvolvimento de uma Aplicação Interativa.`

`2023/7`

<p>
	Projeto desenvolvido para educar e apoiar na gestão de saldos utilizando uma aplicação interativa.
</p>

## Integrantes

* Gabriel Augusto Mendes Do Espirito Santo
* Pedro Henrique Filgueiras Couto
* Marlon Albert Rodrigues Dias
* Caio Santos Celestino da Costa
* Peterson Alves Gervazio
* Wilian Pereira de Aquino Junior.

## Orientador

* Daniela Carvalho Monteiro Ferreira


# Documentação

<ol>
<li><a href="docs/01-Documentação de Contexto.md"> Documentação de Contexto</a></li>
<li><a href="docs/02-Especificação do Projeto.md"> Especificação do Projeto</a></li>
<li><a href="docs/03-Metodologia.md"> Metodologia</a></li>
<li><a href="docs/04-Projeto de Interface.md"> Projeto de Interface</a></li>
<li><a href="docs/05-Arquitetura da Solução.md"> Arquitetura da Solução</a></li>
<li><a href="docs/06-Template Padrão da Aplicação.md"> Template Padrão da Aplicação</a></li>
<li><a href="docs/07-Programação de Funcionalidades.md"> Programação de Funcionalidades</a></li>
<li><a href="docs/08-Plano de Testes de Software.md"> Plano de Testes de Software</a></li>
<li><a href="docs/09-Registro de Testes de Software.md"> Registro de Testes de Software</a></li>
<li><a href="docs/10-Plano de Testes de Usabilidade.md"> Plano de Testes de Usabilidade</a></li>
<li><a href="docs/11-Registro de Testes de Usabilidade.md"> Registro de Testes de Usabilidade</a></li>
<li><a href="docs/12-Apresentação do Projeto.md"> Apresentação do Projeto</a></li>
<li><a href="docs/13-Referências.md"> Referências</a></li>
</ol>


### Documentação de Contexto

Este aplicativo foi desenvolvido para simplificar e aprimorar o controle e a organização do estoque de produtos, proporcionando uma visão clara das quantidades disponíveis, movimentações e necessidades de reposição. O controle correto de estoques é crucial para garantir a disponibilidade dos produtos necessários no momento certo, evitando a escassez ou excesso. Isso ajuda a reduzir custos operacionais, minimizar perdas por vencimento ou obsolescência, e aprimorar a eficiência dos processos de pedido e produção. Além disso, um controle preciso contribui para melhorar a satisfação do cliente ao garantir entregas pontuais.
Reconhecendo a importância do gerenciamento eficaz de estoque, a necessidade de ferramentas que simplifiquem e otimizem esse processo é evidente. Muitas empresas estão buscando soluções digitais para lidar com a complexidade do controle de estoque.

### Definição do Problema.

&nbsp;&nbsp; Auxiliar micro e pequenas empresas no gerenciamento de saldos de estoque.


### Objetivos 

&nbsp;&nbsp; Gerenciar saldos.

&nbsp;&nbsp; Melhorar eficiência.

&nbsp;&nbsp; Prevenir desvios de estoque.
 
Como objetivos específicos, pode se ressaltar:
Permitir que o estoquista controle entrada e sainda de produtos.

Permitir que o vendedor consulte a diponibilidade e infome a saida de produtos.

Permitir que o gerente tenha controle total do seu estoque, para que possa conferiar a confiabilidade de seu estoque.


### Justificativa   

No panorama empresarial em constante evolução, a gestão eficaz de estoque se destaca como um pilar fundamental para o sucesso e a rentabilidade das empresas. A escolha de empreender um projeto de aplicação de controle de estoque é impulsionada pela necessidade imperativa de enfrentar os desafios inerentes ao gerenciamento de recursos, minimizar perdas e maximizar a eficiência operacional.

De acordo com dados estatísticos recentes, cerca de 43% das empresas sofrem com excesso de estoque, enquanto 38% enfrentam problemas de falta de produtos, resultando em perdas financeiras significativas¹. Além disso, estima-se que empresas gastem, em média, de 20% a 35% de seus custos operacionais totais em estoque². Esses números evidenciam a urgência de um controle efetivo do estoque para mitigar riscos financeiros e melhorar os resultados.
 

### Público-alvo 

Grande parte dos usuários são pequenas empresas, estabelecimentos e pessoas com  uma faixa etária de 18 a 60 anos, que necessitam de uma economia de tempo e procuram uma facilidade em gerir o que possuem em estoque. 



### Proposta de Solução

&nbsp;&nbsp;  O objetivo fundamental de um controle de estoque é garantir que uma organização mantenha a quantidade certa de produtos ou materiais disponíveis no momento certo, de forma a atender às demandas dos clientes, minimizando custos e maximizando a eficiência operacional.

### Personas
![Persona1](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t9-gestaodeestoque/blob/main/IMGS/persona1.png)
![Persona2](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t9-gestaodeestoque/blob/main/IMGS/persona2.png)
![Persona3](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t9-gestaodeestoque/blob/main/IMGS/persona3.png)
![Persona4](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t9-gestaodeestoque/blob/main/IMGS/persona4.png)
![Persona5](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t9-gestaodeestoque/blob/main/IMGS/persona5.png)
![Persona6](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t9-gestaodeestoque/blob/main/IMGS/persona6.png)

<table>
<tr>
<td>Eu como …</br> 
	[PERSONA] 
</td>
<td>… quero/desejo … </br>
	[O QUE] 
</td>
<td>… para .... </br>
	[POR QUE] 
</td>
</tr>

<tr>
<td>Jorge Paulo</td>
<td>Entender o que possuo em Estoque.</td>
<td>Para sempre possuir produtos que mais vendem.</td>
</tr>

 

<tr>
<td>Jorge Paulo</td>
<td>Melhorar eficiência operacional aumentando a produtividade.</td>
<td>Acelerar o fluxo de vendas</td>
</tr>

 

<tr>
<td>Ayrton Santana</td>
<td>Atender à demandas exigentes.</td>
<td>Para fazer vendas em valores mais ambiciosos</td>
</tr>

 

<tr>
<td>Ayrton Santana</td>
<td>Satisfazer clientes com celeridade.</td>
<td>Aumentar a confiança dos clientes.</td>
</tr>

 

<tr>
<td>Carlos Massa</td>
<td>Evitar rupturas de Estoque</td>
<td>Com a ideia de sempre possuir os produtos corretos</td>
</tr>

 

<tr>
<td>Carlos Massa</td>
<td>Cumprir regulamentações de segurança.</td>
<td>A fim de validar se todos os produtos estão dentro  de suas validades</td>
</tr>
 
<tr>
<td>Ricardo melo</td>
<td>Redução de custos</td>
<td>diminuir os gastos totais</td>
</tr>
	
<tr>
<td>Glauber maciel </td>
<td>melhor atendimento</td>
<td>Melhorar os atendimentos da empresa</td>
</tr>
	
<tr>
<td> Luciano Hulk</td>
<td>Gerenciar equipamentos</td>
<td>Gerir os equipamentos para manutenção</td>
</tr>
	
<tr>
<td>Ricardo Melo</td>
<td>Reduzir riscos</td>
<td>Para evitar perdas e extravios</td>
</tr>
	
<tr>
<td>Glauber Maciel</td>
<td>Gestão de fornecimento</td>
<td>Gerir os produtos de fornecedores</td>
</tr>
	
<tr>
<td>Luciano Hulk</td>
<td>Gerenciar saldos</td>
<td>Gerir os saldos da equipe</td>
</tr>
</table>

### Requisitos e Restrições.
#### Requisitos Funcionais 

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

<table border="1" cellspacing="1" cellpadding="1" style="border: thin solid black;">

<tr>
	<td>ID</td>
	<td>Descrição</td>
	<td>Prioridade</td>
</tr>
	
<tr>
	<td>RF-01 &nbsp; </td>
	<td>O Sistema deve possuir uma barra de menu </td>
	<td>Alta</td>
</tr>
	
<tr>
	<td>RF-02 &nbsp; </td>
	<td>O Sistema deve permitir Criar, Visualizar, Atualizar e Deletar Fornecedores  </td>
	<td>Média</td>
</tr>
	
<tr>
	<td>RF-03 &nbsp; </td>
	<td>O Sistema deve permitir Criar Visualizar Atualizar e Deletar Produtos  </td>
	<td>Alta</td>
</tr>
	
<tr>
	<td>RF-04 &nbsp; </td>
	<td>O Sistema deve permitir o cadastro de Movimentações que aumentem ou diminuam o saldo de produtos </td>
	<td>Alta</td>
</tr>
	
<tr>
	<td>RF-05 &nbsp; </td>
	<td>O Sistema deve permitir a consulta de saldos dos produtos </td>
	<td>Alta</td>
</tr>

<tr>
	<td>RF-06 &nbsp; </td>
	<td>O Sistema deve permitir a geração de um relatório de entradas e saídas.  </td>
	<td>Média</td>
</tr>

<tr>
	<td>RF-07 &nbsp; </td>
	<td> O Menu deve ser visível a partir de qualquer tela do sistema</td>
	<td>Alta</td>
</tr>
<tr>
	<td>RF-08 &nbsp; </td>
	<td>O Sistema deve possuir um Cadastro de usuário</td>
	<td>Alta</td>
</tr>
<tr>
	<td>RF-09 &nbsp; </td>
	<td>O Sistema deve ter uma tela de login </td>
	<td>Alta</td>
</tr>
<tr>
	<td>RF-10 &nbsp; </td>
	<td> O sistema deve possuir um sistema de arredondamento de valores para até duas casas decimais.</td>
	<td>Média</td>
</tr>

</table>

#### Requisitos não funcionais 

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender. 

<table border="1" cellspacing="1" cellpadding="1" style="border: thin solid black;">

<tr>
	<td>RNF-01 &nbsp; </td>
	<td>O Sistema deve ser de fácil compreensão  </td>
	<td>Média</td>
</tr>
	
<tr>
	<td>RNF-02 &nbsp; </br> </td>
	<td>O Sistema deve utilizar um sistema de cores frias.  </td>
	<td>Média</td>
	</tr>
	
<tr>
	<td>RNF-03 &nbsp; </td>
	<td>O Sistema deverá utilizar as linguagens C# e SQL</td>
	<td>Alta </td>
</tr>
	
<tr>
	<td>RNF-04 &nbsp; </td>
	<td>O sistema deverá registrar informações de fácil acesso</td>
	<td>Média</td>
</tr>
<tr>
	<td>RNF-05 &nbsp; </td>
	<td>O Sistema não deve ser acessado sem utilização de um usuário</td>
	<td>Alta</td>
</tr>
<tr>
	<td>RNF-06 &nbsp; </td>
	<td>O sistema deve dar feedbacks a preenchimentos de registros de formas equivocadas.</td>
	<td>Baixa</td>
</tr>

</table>
	
#### Restrições 

A tabela abaixo apresenta as questões que representam obrigações claras para o desenvolvimento do projeto em questão e que limitam sua execução. 

<table border="1" cellspacing="1" cellpadding="1" style="border: thin solid black;">
<tr>
	<td>RE-01 &nbsp; </td>
	<td>O Sistema não fará compras automáticamente</td>
</tr>
	
<tr>
	<td>RE-02 &nbsp; </td>
	<td>O Sistema não irá importar arquivos</td>
</tr>
	
<tr>
	<td>RE-03 &nbsp; </td>
	<td>O Sistema não será responsivo a todas as telas</td>
</tr>
	
</table>

## Diagrama de Casos de Uso

### Caso de uso.
Usuário administrador é o único capaz de  cadastrar usuário e executar todos os outros processos do sistema.
Usuário Gestor é capaz de visualizar o estoque visando controle da empresa e cancelar movimentações que não estão conddizentes com as notas.
Usuário Estoquista é o usuário chave do sistema, este é capaz de criar os produtos e fornecedores que serão utilizados e suas respectivas movimentações de entrada e saída.
	
![Figura 3 – Diagrama de Caso de Uso]()





# Código

<li><a href="src/README.md"> Código Fonte</a></li>

# Apresentação

<li><a href="presentation/README.md"> Apresentação da solução</a></li>
