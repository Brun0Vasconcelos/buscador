# 📫 Buscador de Endereços com ViaCEP (Java)

Este projeto é uma aplicação simples em Java que permite consultar endereços a partir de um CEP informado pelo usuário, utilizando a API pública do ViaCEP. Os dados são exibidos no terminal e também salvos automaticamente em um arquivo `.json`.

---

## ✅ Funcionalidades

- Limpeza e validação do CEP informado
- Consulta à API do ViaCEP
- Conversão da resposta JSON em objeto Java (`Endereco`)
- Exibição formatada dos dados no terminal
- Salvamento automático dos dados em um arquivo `.json` com o nome do CEP

---

## 🛠 Tecnologias utilizadas

- Java 17 ou superior
- API pública [ViaCEP](https://viacep.com.br/)
- Biblioteca [Gson](https://github.com/google/gson) para manipulação de JSON

---

## 📁 Estrutura do projeto

```src/
├── aplicacao/           → Classe com o método main
│   └── Principal.java
├── modelo/              → Representação dos dados de endereço
│   └── Endereco.java
├── servico/             → Lógicas de negócio
│   ├── ViaCepServico.java     // Busca os dados na API
│   └── ArquivoServico.java    // Salva os dados em arquivo JSON```



---

## 🚀 Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Brun0Vasconcelos/buscador.git
