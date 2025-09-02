# 🧮 Exercícios JavaScript - Funções Matemáticas e Cálculos

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/br/education/oracle-next-education/)
[![Alura](https://img.shields.io/badge/Alura-0066CC?style=for-the-badge&logo=alura&logoColor=white)](https://www.alura.com.br/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 📖 Sobre o Projeto

Este repositório contém uma coleção de **6 exercícios práticos em JavaScript** desenvolvidos durante o programa **ONE - Oracle Next Education** em parceria com a **Alura**. Os exercícios são focados no desenvolvimento de funções para cálculos matemáticos e operações básicas. Cada exercício foi desenvolvido para praticar conceitos fundamentais de JavaScript, incluindo:

- 🔧 Criação de funções
- 🧮 Operações matemáticas
- 🔄 Recursividade
- 📊 Cálculos geométricos
- 💱 Conversões de moedas
- 📐 Fórmulas matemáticas

---

## 🎯 Exercícios Realizados

### 💪 **Exercício 1: Calculadora de IMC**
**Objetivo:** Calcular o Índice de Massa Corporal (IMC) de uma pessoa

```javascript
function calcularImc(peso, altura){
    return peso / (altura * altura);
}
```

### 🔢 **Exercício 2: Calculadora de Fatorial**
**Objetivo:** Calcular o fatorial de um número usando recursividade

```javascript
function calcularFatorial(numero){
    if(numero === 0 || numero === 1){
        return 1;
    } else {
        return numero * calcularFatorial(numero - 1);
    }
}
```

### 💵 **Exercício 3: Conversor de Dólar para Real**
**Objetivo:** Converter valores de dólar americano para real brasileiro

```javascript
function converterDolarParaReal(valorEmDolar){
    const cotacaoDolar = 4.80;
    return valorEmDolar * cotacaoDolar;
}
```

### 📐 **Exercício 4: Calculadora Retangular**
**Objetivo:** Calcular área e perímetro de uma sala retangular

```javascript
function calcularAreaEPerimetroRetangular(altura, largura){
    const area = altura * largura;
    const perimetro = 2 * (altura + largura);
    console.log(`Área: ${area}`);
    console.log(`Perímetro: ${perimetro}`);
}
```

### ⭕ **Exercício 5: Calculadora Circular**
**Objetivo:** Calcular área e perímetro de uma sala circular

```javascript
function calcularAreaEPerimetroCircular(raio){
    const pi = 3.14;
    const area = pi * (raio * raio);
    const perimetro = 2 * pi * raio;
    console.log(`Área: ${area}`);
    console.log(`Perímetro: ${perimetro}`);
}
```

### 🔢 **Exercício 6: Gerador de Tabuada**
**Objetivo:** Mostrar a tabuada completa de um número

```javascript
function mostrarTabuada(numero){
    for(let i = 1; i <= 10; i++){
        const resultado = numero * i;
        console.log(`${numero} x ${i} = ${resultado}`);
    }
}
```

---

## 🛠️ Tecnologias Utilizadas

- **JavaScript ES6+**
- **Node.js** (para execução)
- **Recursividade**
- **Loops e Condicionais**

---

## 📁 Estrutura do Projeto

```
📦 exercicios-javascript/
├── 📄 exercicios.js       # Arquivo principal com as funções
├── 🧪 exemplos.js         # Exemplos de uso das funções
└── 📋 README.md           # Documentação do projeto
```

---

## 🚀 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/exercicios-javascript.git
   ```

2. **Navegue até o diretório:**
   ```bash
   cd exercicios-javascript
   ```

3. **Execute o arquivo no Node.js:**
   ```bash
   node exercicios.js
   ```

4. **Teste cada função chamando-as individualmente:**
   ```javascript
   // Exemplo de uso
   console.log(calcularImc(70, 1.75));
   console.log(calcularFatorial(5));
   calcularAreaEPerimetroRetangular(5, 8);
   ```

---

## 🎓 Conceitos Aprendidos

Durante o desenvolvimento destes exercícios, foram praticados os seguintes conceitos:

- **Declaração de Funções**: Criação de funções com `function`
- **Parâmetros e Argumentos**: Passagem de valores para funções
- **Valores de Retorno**: Uso do `return` para retornar resultados
- **Recursividade**: Funções que chamam a si mesmas
- **Estruturas de Repetição**: Uso do `for` para loops
- **Condicionais**: Implementação de `if/else`
- **Operações Matemáticas**: Cálculos diversos (potência, multiplicação, divisão)
- **Template Literals**: Interpolação de strings com `${}`
- **Constantes**: Declaração de valores fixos com `const`
- **Console.log**: Saída de dados no terminal

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcao`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova função'`)
4. Push para a branch (`git push origin feature/nova-funcao`)
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
- [Node.js](https://nodejs.org/)
- [JavaScript Info](https://javascript.info/)
- [Curso de Lógica de Programação](https://cursos.alura.com.br/)

---

<div align="center">
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge" alt="Made with Love">
  <img src="https://img.shields.io/badge/Powered%20by-JavaScript-yellow?style=for-the-badge&logo=javascript" alt="Powered by JavaScript">
</div>
