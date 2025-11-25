# DeskPro Mobile 📱

> 🎓 **Projeto Acadêmico**: Este aplicativo foi desenvolvido como parte dos requisitos de avaliação da disciplina de [Nome da Disciplina] do curso de [Nome do Curso].

## 📄 Sobre o Projeto

O **DeskPro Mobile** é uma aplicação nativa Android desenvolvida em Java, focada na gestão de suporte técnico e helpdesk. O objetivo principal é facilitar a abertura e o acompanhamento de chamados de suporte, oferecendo também uma assistência automatizada via Inteligência Artificial.

## ✨ Funcionalidades Principais

* **Autenticação de Usuários**: Sistema de Login e Cadastro (SQLite) com diferenciação de cargos e empresas.
* **Gestão de Chamados**:
    * Criação de novos tickets de suporte.
    * Visualização de chamados em aberto.
    * Histórico de chamados resolvidos com parecer técnico.
* **Assistente Virtual Inteligente 🤖**: Chatbot integrado à API do **Google Gemini** para tirar dúvidas frequentes e auxiliar o usuário em tempo real.
* **Perfil do Usuário**: Personalização de foto de perfil (armazenamento local) e visualização de dados cadastrais.
* **Menu Lateral**: Navegação fluida utilizando DrawerLayout.

## 🛠 Tecnologias Utilizadas

* **Linguagem**: Java
* **IDE**: Android Studio
* **Interface**: XML (Layouts)
* **Banco de Dados**: SQLite (Nativo Android)
* **Integração API**: Google Gemini (IA Generativa)
* **Bibliotecas**:
    * OkHttp (Requisições de Rede)
    * Material Design (Componentes visuais)

## 🚀 Como Executar o Projeto

1.  **Clone o repositório**:
    ```bash
    git clone [https://github.com/seu-usuario/deskpro-mobile.git](https://github.com/seu-usuario/deskpro-mobile.git)
    ```
2.  **Abra no Android Studio**:
    * Selecione a pasta raiz do projeto.
    * Aguarde o Gradle sincronizar as dependências.
3.  **Configuração da API Key**:
    * Abra o arquivo `src/main/java/com/example/myapplication/GeminiResp.java`.
    * Insira sua chave de API do Google Gemini na variável `API_KEY`.
4.  **Execute**:
    * Conecte um dispositivo físico ou use um Emulador.
    * Clique em "Run".

## 👨‍💻 Autores

* **David Trindade** - *Desenvolvimento Full Stack Mobile*

---
*Este projeto é estritamente educacional e não possui fins comerciais.*
