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

# 🚀 Jornada Python: Automatizando o Mundo Real

[![Abrir no Colab](https://google.com)](https://google.com)

Bem-vindo ao repositório da minha jornada de desenvolvimento em Python! Este espaço foi criado para armazenar projetos práticos focados em **Automação de Processos (RPA)** e **Engenharia de Software**. O portfólio demonstra minha evolução desde os fundamentos lógicos até a criação de robôs prontos para o ambiente corporativo.

---

## 📁 Estrutura do Repositório

O projeto está organizado por módulos de aprendizado prático:

*   **`modulo_01_automacao/`**: Fundamentos de automação de sistemas e manipulação de arquivos locais.
    *   `automacao_analise_credito.ipynb`: Sistema que calcula parcelas de veículos e analisa o score de crédito do cliente de forma integrada.
    *   `automacao_triagem_rh.ipynb`: Robô de triagem que coleta notas de testes técnicos, avalia o status do candidato e gerencia pastas do sistema.

---

## 🛠️ Tecnologias e Conceitos Dominados (Módulo 1)

Durante o desenvolvimento das automações deste módulo, apliquei conceitos essenciais exigidos pelo mercado:

*   **Lógica e Estruturas de Decisão**: Aplicação de condicionais aninhadas (`if/elif/else`) e estruturas de repetição para varredura de dados.
*   **Modularização com Funções**: Criação de blocos de códigos isolados, reutilizáveis e limpos utilizando passagem de parâmetros e controle de retornos (`return`).
*   **Tratamento de Erros (`try/except`)**: Blindagem das automações contra falhas de entrada de dados do usuário (como o preenchimento de textos em campos numéricos), evitando a queda do robô em produção.
*   **Manipulação de Arquivos e Persistência**: Gravação de relatórios e registros operacionais utilizando gerenciadores de contexto dinâmicos (`with open()`).
*   **Gerenciamento de Pastas com o Sistema Operacional**: Uso das bibliotecas nativas `os` e `shutil` para verificação de diretórios, criação automática de pastas e movimentação inteligente de relatórios criados pelos robôs.

---



