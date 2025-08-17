```markdown
# 🚀 Contêiner de Aplicação Web com Docker Compose

Este projeto é a entrega final do curso de Docker e tem como objetivo a **containerização de uma aplicação web estática**.
Utilizando o **Docker Compose**, o projeto demonstra como orquestrar um servidor web Apache (httpd) para hospedar um
site HTML de forma simples e eficiente.

A proposta do projeto permite ao usuário executar o ambiente de desenvolvimento em qualquer sistema operacional
(**Windows**, **Linux**, **macOS**) de maneira isolada e consistente.

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter:

- 🐳 [Docker](https://www.docker.com/) e [Docker Compose](https://docs.docker.com/compose/) instalados
- 🧠 Conhecimento básico em HTML
- 💻 Um computador com sistema operacional à sua escolha (Windows, Linux, macOS)

---

## 📁 Estrutura do Projeto

A estrutura de diretórios deve seguir o padrão abaixo:

meu-site-docker/
├── docker-compose.yml
└── html/
    └── index.html
```

---

## ▶️ Como Executar

Siga os passos abaixo para colocar a aplicação no ar:

1. Certifique-se de que sua estrutura de arquivos esteja organizada conforme o modelo acima.
2. Abra o terminal ou prompt de comando.
3. Navegue até o diretório raiz do meu-site-docker.
4. Execute o seguinte comando:

```bash
docker-compose up
```

5. Acesse sua aplicação no navegador:

```
http://verifique-o-ip-assinalado-pelo-docker
```

6. Para parar o contêiner, pressione `CTRL + C` no terminal.

7. Para remover o contêiner e a rede, execute:

```bash
docker-compose down
```

---

## 🎨 Créditos e Recursos do Template HTML

O conteúdo HTML foi baixado do site [freehtml5.co](https://freehtml5.co).

O template utilizado é uma demonstração completa com os seguintes recursos:

- 🧩 Bootstrap 4  
- 📱 Design Responsivo  
- 🎨 Design Exclusivo  
- 🦸‍♂️ Cabeçalho de Destaque (Hero Header)  
- 👉 Botões de Chamada para Ação (Call-to-action)  
- ⚙️ Seção de Recursos  
- 🎠 Carrosséis  
- 💬 Depoimentos  
- 💰 Tabelas de Preços  
- ✨ Animações ao Rolagem (On-scroll Reveal Animations)

---

## 📌 Observações

Este projeto é ideal para fins educacionais e demonstração de conceitos básicos de containerização com Docker. Sinta-se à vontade para personalizar o template HTML conforme suas necessidades.

---

## 🧑‍💻 Autor

Projeto desenvolvido por [**Ricardo Fagundes**](https://www.linkedin.com/in/ricardofagundes) como parte do curso de Docker.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE), exceto pelo template HTML que segue os termos do site [freehtml5.co](https://freehtml5.co).
```
