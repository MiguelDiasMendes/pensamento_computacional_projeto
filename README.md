# pensamento_computacional_projeto
primeiro repositório para praticas e verscionamento de github e prompts de comandos

````md
# 🍧 Sistema de Vendas - Açaiteria

Sistema desenvolvido em **Python** utilizando a biblioteca **Tkinter** para realizar o gerenciamento de produtos de uma açaiteria.

O projeto permite cadastrar produtos, consultar informações, realizar vendas, controlar o estoque e excluir produtos através de uma interface gráfica simples e intuitiva.

---

# 📋 Funcionalidades

✅ Cadastro de produtos

- Nome
- Estoque
- Preço
- Validade
- Descrição

✅ Listagem de produtos cadastrados

✅ Visualização dos detalhes de cada produto

✅ Realização de vendas

- Atualização automática do estoque
- Cálculo automático do valor total da venda

✅ Exclusão de produtos

✅ Validação dos dados informados

✅ Botão para sair do sistema

---

# 🛠 Tecnologias Utilizadas

- Python 3
- Tkinter
- MessageBox
- Listas
- Dicionários
- Condicionais (`if`, `elif`, `else`)
- Laços de repetição
- Funções

---

# 📂 Estrutura dos Produtos

Cada produto é armazenado em um dicionário contendo as seguintes informações:

```python
{
    "nome": "Açaí Comum",
    "estoque": 100,
    "preco": 8.90,
    "validade": "10/12/2026",
    "descricao": "Descrição do produto"
}
```

Todos os produtos são armazenados dentro de uma lista.

---

# ⚙️ Funcionalidades do Sistema

## 🍧 Cadastro

Permite adicionar novos produtos ao sistema.

Campos obrigatórios:

- Nome
- Estoque
- Preço
- Validade
- Descrição

O sistema valida os dados antes do cadastro.

---

## 📋 Listagem

Todos os produtos cadastrados aparecem em uma lista contendo:

- Nome
- Preço
- Estoque
- Validade

---

## 🔍 Ver Detalhes

Ao selecionar um produto, o sistema exibe:

- Nome
- Estoque
- Preço
- Validade
- Descrição

---

## 💰 Realizar Venda

O usuário informa:

- Nome do produto
- Quantidade

O sistema:

- verifica se o produto existe;
- verifica o estoque disponível;
- calcula automaticamente o valor total;
- atualiza o estoque após a venda.

---

## 🗑 Excluir Produto

Permite remover um produto da lista mediante confirmação do usuário.

---

## 🚪 Encerrar Sistema

Possui um botão para fechar o programa com confirmação.

---

# 📚 Estruturas de Dados Utilizadas

### Lista

Utilizada para armazenar todos os produtos cadastrados.

```python
produtos = []
```

---

### Dicionários

Cada produto é representado por um dicionário.

```python
produto = {
    "nome": "",
    "estoque": 0,
    "preco": 0.0,
    "validade": "",
    "descricao": ""
}
```

---

# 🖥 Interface

O sistema possui uma interface gráfica construída com Tkinter contendo:

- Área de cadastro
- Lista de produtos
- Área para vendas
- Botões de ação
- Caixa de mensagens
- Barra de rolagem

---

# ▶️ Como executar

1. Instale o Python 3.

2. Faça o download do projeto.

3. Execute o arquivo principal.

```bash
python acaiteria.py
```

---

# 📸 Funcionalidades

- Cadastro de produtos
- Controle de estoque
- Venda de produtos
- Exclusão de produtos
- Consulta de detalhes
- Interface gráfica
- Validação de entradas
- Atualização automática do estoque

---

# 👨‍💻 Autor

**Miguel Dias**

Projeto desenvolvido para a disciplina de **Pensamento Computacional**, utilizando Python e Tkinter para aplicar conceitos de programação, estruturas de dados e desenvolvimento de interfaces gráficas.
````
