# 🎮 PlayKeep API

O **PlayKeep** é uma solução moderna para gestão de locação de jogos, desenvolvida para simplificar o controle de estoque e o relacionamento com o cliente. A plataforma orquestra todo o ciclo de vida do aluguel, desde o cadastro do gamer até o fluxo de entrega e devolução.

## 🚀 Funcionalidades Principais

- **Gestão de Clientes:** Cadastro completo para contato e histórico.
- **Inventário Dinâmico:** Registro de jogos com controle de quantidade em tempo real.
- **Fluxo de Locação:** Monitoramento de entregas e devoluções pendentes.
- **Disponibilidade:** Validação inteligente de estoque antes de cada locação.

## 🛠️ Tecnologias e Ferramentas

- **Backend:** ASP.NET Core 10
- **ORM:** Entity Framework Core
- **Banco de Dados:** SQL Server
- **Documentação:** Swagger/OpenAPI

## ⚙️ Instalação e Execução

1. **Clone o projeto:**

   ```bash
   git clone https://github.com/LimaDevCod3r/playkeep-api.git
   ```

2. **Acesse o diretório:**

   ```bash
   cd PlayKeep.Api
   ```

3. **Restaure as dependências:**

   ```bash
   dotnet restore
   ```

4. **Atualize o banco de dados:**

   ```bash
   dotnet ef database update
   ```

5. **Inicie a aplicação:**
   ```bash
   dotnet run
   ```

A API estará disponível em `http://localhost:5000` (ou na porta configurada). Acesse `/swagger` para visualizar a documentação interativa.

## 📁 Estrutura da API (Principais Endpoints)

- `GET /api/clientes` -> Lista e gerencia contatos.
- `POST /api/jogos` -> Registra novos títulos e quantidades.
- `PATCH /api/alugueis/entrega` -> Registra saída de um jogo.
- `PATCH /api/alugueis/devolucao` -> Finaliza o ciclo de locação.

---

Desenvolvido com foco em performance e organização de código. 🚀
