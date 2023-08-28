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
 

#### Como objetivos específicos, pode se ressaltar:   


### Justificativa   
 

### Público-alvo 

Grande parte dos usuários são pequenas empresas, estabelecimentos e pessoas com  uma faixa etária de 18 a 60 anos, que necessitam de uma economia de tempo e procuram uma facilidade em gerir o que possuem em estoque. 



### Proposta de Solução

&nbsp;&nbsp;  O objetivo fundamental de um controle de estoque é garantir que uma organização mantenha a quantidade certa de produtos ou materiais disponíveis no momento certo, de forma a atender às demandas dos clientes, minimizando custos e maximizando a eficiência operacional.


## Instruções de utilização

Assim que a primeira versão do sistema estiver disponível, deverá complementar com as instruções de utilização. Descreva como instalar eventuais dependências e como executar a aplicação.

Não deixe de informar o link onde a aplicação estiver disponível para acesso (por exemplo: https://adota-pet.herokuapp.com/src/index.html).

Se houver usuário de teste, o login e a senha também deverão ser informados aqui (por exemplo: usuário - admin / senha - admin).

O link e o usuário/senha descritos acima são apenas exemplos de como tais informações deverão ser apresentadas.


### Personas


<div>
<img align="left" src="/IMGS/persona1.png" width="480px"  />
</div>

</br>

<img align="left" src= "/IMGS/persona2.png" width="480px"/>


</br>
</br>
<div align="center"  >
</div>

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
Usuário cadastra um fornecedor, Cadastra um produto , e inclui uma movimentação utilizando o fornecedor e o produto cadastrado. Vendedor verifique o saldo em estoque e caso este produto possua saldo realiza uma venda.Gestor Verifica que os produtos possuem uma avaria, e ordena o cancelamento das movimentações.
Figura 2 – principais vilões das dívidas 
	
![Figura 3 – Diagrama de Caso de Uso](https://github.com/ICEI-PUC-Minas-PMV-ADS/gestaoDeEstoque/blob/main/img/caso_de_uso.png)





# Código

<li><a href="src/README.md"> Código Fonte</a></li>

# Apresentação

<li><a href="presentation/README.md"> Apresentação da solução</a></li>
