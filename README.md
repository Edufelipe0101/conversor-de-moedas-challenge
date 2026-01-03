# 💱 Conversor de Moedas em Java

Conversor de moedas desenvolvido em **Java 17** como desafio prático da **Alura**, com consumo de **API de câmbio em tempo real**, manipulação de **JSON** e interação com o usuário via **console**.

---

## 📌 Funcionalidades

- Consumo de API externa de taxas de câmbio em tempo real
- Conversão dinâmica entre moedas
- Interface textual interativa via console
- Menu com **no mínimo 6 opções de conversão**
- Manipulação de dados em formato JSON
- Código organizado seguindo boas práticas de POO

---

## 🌍 Moedas Suportadas

- **USD** – Dólar Americano  
- **BRL** – Real Brasileiro  
- **ARS** – Peso Argentino  
- **BOB** – Boliviano Boliviano  
- **CLP** – Peso Chileno  
- **COP** – Peso Colombiano  

---

## 🔌 API Utilizada -> https://www.exchangerate-api.com/

As taxas de câmbio são obtidas dinamicamente através da **ExchangeRate-API**:



## 🛠️ Tecnologias Utilizadas

- **Java 17**
- **HttpClient (java.net.http)**
- **Gson**
- **Scanner**
- **Programação Orientada a Objetos**

---

## 📂 Estrutura do Projeto

src/
└── br/com/alura/conversor/
├── Main.java
├── api/ExchangeRateClient.java
├── model/ExchangeRateResponse.java
├── service/CurrencyConverter.java
└── ui/Menu.java

## 🔄 Lógica de Conversão

As taxas são sempre atualizadas, pois são obtidas diretamente da API.

---

## ▶️ Como Executar

### Pré-requisitos
- Java **17** ou superior
- Biblioteca **Gson** configurada
- IDE (VS Code, IntelliJ ou Eclipse)

### Execução
1. Clone o repositório
2. Abra o projeto na IDE
3. Execute a classe:
4. Utilize o menu exibido no console

## 📋 Exemplo de Menu

1 - USD para BRL
2 - BRL para USD
3 - USD para ARS
4 - USD para COP
5 - USD para CLP
6 - USD para BOB
7 - Sair

## 👨‍💻 Autor

**Eduardo Felipe**  
Estudante e entusiasta de Tecnologia da Informação  
Projeto desenvolvido para fins educacionais (Alura).

---

## 📜 Licença

Uso livre para fins educacionais.
