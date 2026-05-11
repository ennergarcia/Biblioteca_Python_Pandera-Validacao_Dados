## 📚🐍 Biblioteca Python Pandera (Automação de Validação de Dados)

Os dados sendo transformados em informações relevantes são o objetivo primário de um pipeline de dados. Então dados válidos e acompanhados de forma dinâmica é fundamental para esse objetivo, afinal quem nunca se deparou com os estados brasileiros sendo escritos das mais diversas formas em uma coluna.

---

### 📚 Sobre a Biblioteca Pandera

É uma biblioteca de validação de dados leve e flexível, projetada especificamente para estruturas de dados como o Pandas, Polars e Modin. Ele permite que você defina esquemas (schemas) que verificam se os seus dados estão de acordo com o que você espera antes de processá-los.

---

### 💻 Principais Funcionalidades

#### Validação de Tipos e Colunas
Garante que colunas específicas existam e que contenham os tipos de dados corretos (ex: int, float, string).

#### Checagem de Valores
Permite definir regras lógicas, como "a coluna preço não pode ter valores negativos" ou "a coluna categoria deve conter apenas 'A', 'B' ou 'C'".

#### Tratamento de Erros Detalhado
Quando a validação falha, ele fornece relatórios precisos indicando exatamente quais linhas e colunas causaram o erro.

#### Inferência de Esquema
O Pandera pode analisar um DataFrame existente e sugerir um esquema de validação automaticamente.

---

### 💻 Principais Funcionalidades

Os notebooks Colab permitem executar o código, realizar os exercícios e salvar sua versão modificada no Google Drive.

#### Notebook de Exemplo 1: Valor Negativo
Este notebook é responsável por apresentar a validação dos dados para valores.
* [Clique aqui para executar o Notebook de Exemplo 1 no Colab](https://github.com/ennergarcia/Biblioteca_Python_Pandera-Validacao_Dados/blob/main/exemplo_pandera.ipynb)

#### Notebook de Exemplo 2: Validar UFs (Unidades da Federação) evitando que o banco de dados fique com nomes misturados (ex: "São Paulo", "SP", "S. Paulo").
Este notebook utiliza o Check.isin() do **Pandera**, que garante que os valores pertençam a uma lista pré-definida.
* [Clique aqui para executar o Notebook de Exemplo 2 no Colab](https://github.com/ennergarcia/Biblioteca_Python_Pandera-Validacao_Dados/blob/main/exemplo2_pandera.ipynb)

---

### 🚀 Funcinalidades em um ambiente profissional

#### Fail-Fast (Falha Rápida)
É melhor o código parar no início do processo por causa de um dado inválido do que gerar um relatório errado ou quebrar o modelo de ML horas depois. De toda forma em um modelo medalhão, na etapa de ingestão (bronze) o processo não precisa ser interrompido porém a Pandera lhe fornecera atributos a serem tratados na camada limpeza e transformação (silver).

#### Documentação Viva
O esquema serve como uma documentação clara do que seu sistema aceita como "dado válido".

#### Qualidade de Dados (Data Quality)
Essencial para pipelines de Engenharia de Dados e Ciência de Dados, onde a confiança nos inputs é fundamental.

---

### 📝 Licença

O projeto está licenciado sob a: [Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

### 👨‍💻 Autoria e Notas Finais

* **Por:** Enner Sebastião Garcia
* **Nota:** Todas as imagens foram produzidas por IA.
