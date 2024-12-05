

# **Emprego App – Plataforma de Vagas de Emprego**

## 🚀 **Visão Geral do Projeto**  
O **Emprego App** é uma plataforma web desenvolvida para conectar empresas e candidatos de forma prática e moderna. O sistema foi construído para exibir vagas de emprego de maneira intuitiva e acessível, proporcionando uma experiência fluida tanto para empresas quanto para candidatos. A interface foi projetada para ser adaptável, com uma experiência diferenciada para dispositivos móveis e desktops.

---

## 🌟 **Principais Funcionalidades**

### **Para Candidatos:**
- **Visualização das vagas**: As vagas são apresentadas em cards, permitindo uma navegação clara e objetiva.
- **Feedback visual**: Caso não existam vagas disponíveis, o candidato verá uma mensagem de aviso.

### **Para Empresas:**
- **Cadastro de vagas**: Empresas podem facilmente cadastrar novas vagas diretamente da página inicial.
- **Área administrativa**: Empresas têm acesso a uma área de administração para gerenciar as vagas.

---

## 🖥️ **Tecnologias Utilizadas**

- **Flask**: Framework web para backend.
- **Bootstrap**: Framework CSS para garantir um design responsivo e funcional.
- **HTML5** e **CSS3**: Estrutura e estilos personalizados para uma experiência agradável.
- **JavaScript**: Para funcionalidades básicas de interação e validação.

---

## 🎨 **Design e Estilo**

O layout do **Emprego App** foi projetado para ser simples e elegante. Usando o **Bootstrap** como base para garantir a responsividade, ele adapta o conteúdo automaticamente para dispositivos de diferentes tamanhos, com uma interface limpa e moderna.

- **Desktops**: A interface é otimizada com um menu de navegação superior e um conteúdo bem distribuído na tela.
- **Mobile**: Para dispositivos móveis, a página se adapta, oferecendo um layout mais compacto e fácil de navegar.

---

## ⚙️ **Como Executar o Projeto**

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/usuario/emprego-app.git
   ```

2. **Instale as dependências**:
   - Crie um ambiente virtual:
     ```bash
     python -m venv venv
     ```
   - Ative o ambiente virtual:
     - No Windows:
       ```bash
       venv\Scripts\activate
       ```
     - No Linux/Mac:
       ```bash
       source venv/bin/activate
       ```
   - Instale as dependências:
     ```bash
     pip install -r requirements.txt
     ```

3. **Execute o servidor**:
   ```bash
   flask run
   ```

4. **Acesse a aplicação**:
   Abra o navegador e acesse `http://127.0.0.1:5000/`.

---

## 📚 **Estrutura do Projeto**

- **templates/**: Contém os arquivos HTML, incluindo `base.html` e as páginas específicas para a plataforma.
- **static/**: Contém os arquivos estáticos, como CSS (incluindo `lux.css`), imagens e scripts.
- **app.py**: Arquivo principal com a configuração do Flask e rotas da aplicação.

---

## 🛠️ **Personalizações e Melhorias Futuras**

- **Área de filtragem de vagas**: Implementação de filtros para melhorar a busca de vagas para os candidatos.
- **Sistema de login**: Adicionar autenticação para os usuários (empresas e candidatos).
- **Interações em tempo real**: Como notificações de novas vagas ou atualizações.

---

## 📞 **Contato**

Para dúvidas ou sugestões, entre em contato via [email](mailto:exemplo@dominio.com).