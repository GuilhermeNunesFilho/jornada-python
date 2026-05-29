# jornada-python
Repositório central de estudos, desafios e automações em Python

# 📊 Automação de Relatórios e Comissões com Python

Este projeto simula uma demanda real de mercado: um script em Python que automatiza a criação de planilhas do Excel, realiza cálculos de comissão de vendas em lote e insere fórmulas financeiras automaticamente.

## 🚀 Novas Funcionalidades Implementadas
- **Manipulação de Planilhas:** Criação de arquivos `.xlsx` e edição de abas com a biblioteca `openpyxl`.
- **Processamento em Lote:** Uso do laço de repetição `for` integrado com a função `.append()` para inserir múltiplos registros de vendas de uma só vez.
- **Cálculo Dinâmico:** Extração do valor bruto das células via `.value` para calcular 10% de comissão em tempo real dentro do loop.
- **Fórmulas do Excel Automatizadas:** Inserção das funções nativas `=SUM()` diretamente no rodapé da planilha para gerar os totais de vendas e comissões.
- **Visualização Interna:** Implementação do método `.iter_rows(values_only=True)` para imprimir o resultado final limpo diretamente no console do Google Colab.

## 🛠️ Tecnologias e Conceitos Praticados
- Python 3
- Biblioteca `openpyxl`
- Estruturas de dados avançadas (Listas de Listas)
- Iteração e loops numéricos (`for` + índices de listas `[0]`, `[1]`, `[2]`)

## 💻 Como os dados são estruturados no Console
```text
('Vendedor', 'Produto', 'Valor do Produto', 'Comissão (10%)')
('Guilherme', 'Curso de Python', 100, 10.0)
('Ana', 'Computador', 5000, 500.0)
...
```
## 🏫 Automação de Documentos: Gerador de Boletins Escolares
Um sistema desenvolvido de forma totalmente autônoma para fixar a lógica de iteração em lote, estruturas condicionais compostas e manipulação de coordenadas em PDF.

### Conceitos Praticados:
- **Lógica Condicional (`if/elif/else`):** Validação matemática para determinar o status do aluno (Aprovado, Recuperação ou Reprovado) com base na média.
- **Tratamento de Índices:** Isolamento de inteiros dentro de listas aninhadas (`linha[1]` e `linha[2]`) para aplicação de fórmulas de média aritmética.
- **Formatação de Layout:** Uso estratégico dos eixos cartesianos X e Y para evitar sobreposição de elementos e criar uma identidade visual limpa no documento.

