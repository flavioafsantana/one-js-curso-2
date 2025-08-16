# 🚀 ONE - Oracle Next Education | Lógica de Programação - Desafios JavaScript

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/br/education/oracle-next-education/)
[![Alura](https://img.shields.io/badge/Alura-0066CC?style=for-the-badge&logo=alura&logoColor=white)](https://www.alura.com.br/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 📖 Sobre o Projeto

Este repositório contém as soluções para os desafios propostos no programa **ONE - Oracle Next Education** em parceria com a **Alura**. Cada exercício foi desenvolvido para praticar conceitos fundamentais de JavaScript, incluindo:

- 🔧 Manipulação do DOM
- 💬 Interação com o usuário (alerts, prompts)
- 🧮 Operações matemáticas
- 🎯 Estruturas condicionais
- 📝 Concatenação de strings

---

## 🎯 Desafios Realizados

### 🏷️ **Desafio 1: Alterando o Título**
**Objetivo:** Alterar o conteúdo da tag h1 usando `document.querySelector`

```javascript
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';
```

### 🖱️ **Desafio 2: Função Console**
**Objetivo:** Criar uma função que exiba mensagem no console quando o botão for clicado

```javascript
function escreverConsole(){
    console.log('O botão foi clicado');
}
```

### ⚠️ **Desafio 3: Função Alert**
**Objetivo:** Criar uma função que exiba um alerta com mensagem de amor ao JavaScript

```javascript
function escreverAlert(){
    alert('Eu amo JS');
}
```

### 🌆 **Desafio 4: Prompt Interativo**
**Objetivo:** Solicitar nome de uma cidade e exibir mensagem personalizada

```javascript
function abrirPrompt(){
    let cidade = prompt('Digite uma cidade do Brasil');
    alert(`Estive em ${cidade} e lembrei de você`);
}
```

### ➕ **Desafio 5: Calculadora Simples**
**Objetivo:** Realizar soma de dois números inteiros inseridos pelo usuário

```javascript
function somar(){
    let num1 = parseInt(prompt('Digite um número'));
    let num2 = parseInt(prompt('Digite outro número'));
    let soma = num1 + num2;
    alert(`A soma dos números é ${soma}`);
}
```

---

## 🛠️ Tecnologias Utilizadas

- **JavaScript ES6+**
- **HTML5**
- **CSS3**
- **DOM Manipulation**

---

## 📁 Estrutura do Projeto

```
📦 one-desafios-javascript/
├── 📄 index.html          # Página principal com botões
├── 🎨 style.css           # Estilos da aplicação
├── ⚡ script.js           # Lógica JavaScript
└── 📋 README.md           # Documentação do projeto
```

---

## 🚀 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/one-desafios-javascript.git
   ```

2. **Navegue até o diretório:**
   ```bash
   cd one-desafios-javascript
   ```

3. **Abra o arquivo `index.html` no seu navegador preferido**

4. **Teste cada funcionalidade clicando nos botões correspondentes**

---

## 🎓 Conceitos Aprendidos

Durante o desenvolvimento destes desafios, foram praticados os seguintes conceitos:

- **Seleção de Elementos DOM**: Uso do `document.querySelector()` para acessar elementos HTML
- **Manipulação de Conteúdo**: Alteração de conteúdo com `innerHTML`
- **Funções JavaScript**: Criação e chamada de funções
- **Interação com Usuário**: Utilização de `alert()`, `prompt()` e `console.log()`
- **Conversão de Tipos**: Uso do `parseInt()` para converter strings em números
- **Template Literals**: Concatenação moderna com `${variavel}`
- **Eventos**: Associação de funções aos eventos de clique

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido com 💙 durante o programa **ONE - Oracle Next Education**

---

## 🔗 Links Úteis

- [Oracle Next Education](https://www.oracle.com/br/education/oracle-next-education/)
- [Alura](https://www.alura.com.br/)
- [Documentação JavaScript - MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Curso de Lógica de Programação](https://cursos.alura.com.br/)

---

<div align="center">
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge" alt="Made with Love">
  <img src="https://img.shields.io/badge/Powered%20by-JavaScript-yellow?style=for-the-badge&logo=javascript" alt="Powered by JavaScript">
</div>
