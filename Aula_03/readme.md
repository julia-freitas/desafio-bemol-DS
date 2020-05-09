## Problema a ser resolvido:

----- descrever o problema proposto --------


## Nossos Dados (lista de arquivos de entrada):

### Arquivo pedidos.txt: lista de materiais em estoque na farma


<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Cod. fornecedor</th>
<th style="text-align:center">Material</th>
<th style="text-align:center">Qtd.pedido</th>
<th style="text-align:center">Texto breve</th>
<th style="text-align:center">Qtd.estoque</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
</tr>
</tbody>
</table>

### Arquivo materiais.csv: possui toda a lista de materiais da farma

### Arquivo vendas1:

### Arquivo vendas2: 

## Resultado esperado:

<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Cod Material</th>
<th style="text-align:center">Qtd. pedida</th>
<th style="text-align:center">Qtd. vendida</th>
<th style="text-align:center">Porcentagem</th>
<th style="text-align:center">Status</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">código do material</td>
<td style="text-align:center">quantidade pedida </td>
<td style="text-align:center">quantidade vendida</td>
<td style="text-align:center">(quantidade pedida)/(quantidade vendida)</td>
<td style="text-align:center">se % >= 1.2: gerar ALERTA!</td>
</tr>
</tbody>
</table>

# Pré-processamento dos dados (Data Wrangling):

* Leitura dos arquivos de entrada

* Tratamento de Dados

	* Renomeando Colunas

	* Deletar Colunas (?)

		Ao final será preciso gerar um novo arquivo com as nossas informações padronizadas e eliminar colunas desnecessárias para a análise

* Verificar os tipos de dados das colunas (em busca de dados categóricos)

* Alterar os tipos categóricos para numéricos

* Agrupar de dados (os dados de mesmo código para uma mesma linha)

* Correlação de Tabelas (Concatenação dos conjuntos de dados de entrada em 1 único dataset)

* Regras de Negócio

* Exportando Dados

