# 📦 Sistema de Gerenciamento de Produtos

## 📌 Descrição
Sistema simples desenvolvido em **Java** para gerenciamento de produtos em estoque.  
Permite realizar operações básicas como cadastro, listagem, atualização e remoção de produtos.

---

## ⚙️ Funcionalidades
- ✅ Cadastrar produto  
- 📋 Listar todos os produtos  
- 🔍 Buscar produto por ID  
- ✏️ Atualizar dados do produto  
- ❌ Remover produto  

---

## 🧱 Estrutura do Projeto

### 🔹 Classe `Product`
Representa um produto no sistema.

**Atributos:**
- `id` → Identificador único  
- `name` → Nome do produto  
- `price` → Preço  
- `quantity` → Quantidade em estoque  

---

### 🔹 Classe `Main`
Responsável pelo controle do sistema.

**Funções principais:**
- Gerenciar lista de produtos (`ArrayList`)
- Exibir menu interativo
- Executar operações do sistema

---

## 🔄 Funcionamento
O sistema roda em loop contínuo, exibindo um menu no terminal.  
O usuário escolhe uma opção e o sistema executa a ação correspondente.

---

## 🛠️ Tecnologias Utilizadas
- Java  
- Programação Orientada a Objetos (POO)  
- ArrayList  
- Scanner  

---

## ⚠️ Observações
- Os dados são armazenados apenas em memória  
- Não há persistência de dados  
- Não possui tratamento de erros para entradas inválidas  

---

## 🚀 Melhorias Futuras
- Implementar tratamento de exceções (`try-catch`)  
- Adicionar persistência de dados (arquivo ou banco de dados)  
- Melhorar organização do código (separação de responsabilidades)  

---

## 👨‍💻 Autor
Kauan Fernando
