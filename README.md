```markdown
# Calculadora API

Uma API simples de calculadora construída com Express.js, que fornece operações matemáticas básicas: soma, subtração, multiplicação e divisão. Também inclui uma rota que retorna um sorriso 😁.

## Funcionalidades

- **Soma**
- **Subtração**
- **Multiplicação**
- **Divisão**
- **Retornar um sorriso** 😁

## Tecnologias Usadas

- Node.js
- Express
- Body-parser

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Inicie a aplicação:
   ```bash
   node index.js
   ```
   (Substitua `index.js` pelo nome do seu arquivo, se diferente.)

4. Acesse a aplicação em [http://localhost:3000](http://localhost:3000).

## Rotas

### 1. Sorriso

- **Método:** GET
- **Rota:** `/sorriso`
- **Descrição:** Retorna um sorriso.
- **Exemplo de requisição:**
  ```bash
  curl http://localhost:3000/sorriso
  ```

### 2. Soma

- **Método:** POST
- **Rota:** `/soma`
- **Descrição:** Retorna a soma de dois números.
- **Corpo da Requisição:**
  ```json
  {
    "a": 5,
    "b": 3
  }
  ```
- **Exemplo de requisição:**
  ```bash
  curl -X POST http://localhost:3000/soma -H "Content-Type: application/json" -d '{"a": 5, "b": 3}'
  ```

### 3. Subtração

- **Método:** POST
- **Rota:** `/subtracao`
- **Descrição:** Retorna a subtração de dois números.
- **Corpo da Requisição:**
  ```json
  {
    "a": 5,
    "b": 3
  }
  ```
- **Exemplo de requisição:**
  ```bash
  curl -X POST http://localhost:3000/subtracao -H "Content-Type: application/json" -d '{"a": 5, "b": 3}'
  ```

### 4. Multiplicação

- **Método:** POST
- **Rota:** `/multiplicacao`
- **Descrição:** Retorna a multiplicação de dois números.
- **Corpo da Requisição:**
  ```json
  {
    "a": 5,
    "b": 3
  }
  ```
- **Exemplo de requisição:**
  ```bash
  curl -X POST http://localhost:3000/multiplicacao -H "Content-Type: application/json" -d '{"a": 5, "b": 3}'
  ```

### 5. Divisão

- **Método:** POST
- **Rota:** `/divisao`
- **Descrição:** Retorna a divisão de dois números.
- **Corpo da Requisição:**
  ```json
  {
    "a": 6,
    "b": 3
  }
  ```
- **Exemplo de requisição:**
  ```bash
  curl -X POST http://localhost:3000/divisao -H "Content-Type: application/json" -d '{"a": 6, "b": 3}'
  ```
