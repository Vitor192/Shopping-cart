# 🛒 Shopping Cart - Microservice

**Seu carrinho de compras inteligente!**  
Este microsserviço é responsável pelo **gerenciamento do carrinho de compras** dos usuários, permitindo **adicionar**, **remover** e **visualizar** itens com facilidade.  
Feito com 💛 usando **Java Spring Boot** e arquitetura limpa.

---

## ✨ Funcionalidades
- ➕ **Adicionar produtos** ao carrinho
- ➖ **Remover itens** do carrinho
- 📜 **Listar** todos os itens do carrinho
- 🧹 **Esvaziar carrinho** de compras

---

## 🛠 Tecnologias Utilizadas
| Tecnologia | Função |
|------------|--------|
| ☕ **Java 17** | Linguagem principal |
| 🚀 **Spring Boot** | Framework backend |
| ☁️ **Spring Cloud** | Integração entre microsserviços |
| 🗄 **Redis** | Armazenamento de dados do carrinho |
| 📦 **Maven** | Gerenciador de dependências |
| 🐳 **Docker** (opcional) | Containerização |


---

## 🚀 Como Executar Localmente

### 1️⃣ Clonar o Repositório
```bash
git clone https://github.com/Vitor192/Product-Catalog.git

Endpoints Principais

GET    /cart/{userId}               # 📜 Lista os itens do carrinho
POST   /cart/{userId}/items          # ➕ Adiciona item ao carrinho
DELETE /cart/{userId}/items/{itemId} # ➖ Remove item do carrinho



📂 Estrutura do Projeto
plaintext
Copiar
Editar

shopping-cart/
 ├── src/
 │   ├── main/
 │   │   ├── java/
 │   │   │    └── com.example.shoppingcart/
 │   │   │         ├── controller/
 │   │   │         ├── service/
 │   │   │         ├── model/
 │   │   │         └── repository/
 │   │   └── resources/
 │   │        ├── application.properties
 │   │        └── data.sql
 └── pom.xml



