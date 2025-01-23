# Pesquisa de Produtos com Capacidade Adequada

## Objetivo
Realizar a seleção de produtos com base na capacidade desejada, levando em consideração os fatores de correção associados ao fluido e à ligação elétrica. A capacidade selecionada deve estar dentro de uma margem de diferença máxima e minima de 30% em relação à capacidade requerida.

Tabelas Disponíveis:

### Tabela de Produtos:

- Produto

- Capacidade

### Tabela de Fluidos:

- Fluido

- Fator de Correção

### Tabela de Ligação Elétrica:

- Codigo

- Voltagem

- Fator de Correção

## Procedimento:

### Identificação da Capacidade Base:

Determinar a capacidade necessária informada pelo usuário.

### Cálculo da Capacidade Corrigida:

Aplicar os fatores de correção correspondentes ao fluido e à ligação elétrica:

### Filtro de Produtos:

Selecionar produtos cuja capacidade corrigida esteja dentro de uma faixa de ±30% da capacidade necessária.

### Apresentação dos Resultados:

Listar os produtos que atendem aos critérios, indicando sua capacidade corrigida e os fatores aplicados.

### Exemplo de Fluxo:

Usuário informa capacidade desejada de 1000.

Selecionado o fluido com fator 0,9 e ligação com fator 1,1.

Capacidade corrigida = 1000 x 0,9 x 1,1 = 990.

Produtos entre 700 e 1300 são considerados.

Produtos adequados são apresentados.

## Observações:

Caso não haja produtos dentro da faixa especificada, deve-se sugerir alternativas próximas.

A seleção dos fatores de fluido e ligação deve ser feita com base nos dados disponíveis nas tabelas fornecidas.

O codigo da ligação deve ser incluido no nome do produto no lugar do underline.