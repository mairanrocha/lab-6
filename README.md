# Laboratório de Exploração: GitHub Copilot e Ferramentas da OpenAI

## 📌 Descrição do Desafio

Este laboratório tem como objetivo explorar as funcionalidades do GitHub Copilot e das ferramentas da OpenAI, com ênfase nos filtros de conteúdo e nos recursos de criação assistida por inteligência artificial. O entregável consiste em um repositório organizado com exemplos de uso, prompts aplicados e anotações sobre os aprendizados adquiridos.

---

## 🎯 Objetivos

- Compreender como ferramentas de IA auxiliam na geração de código e conteúdo.
- Testar os filtros de conteúdo das plataformas para identificar limitações e comportamentos.
- Registrar exemplos de uso prático, prompts utilizados e os aprendizados adquiridos.

---

## 🧪 Atividades Realizadas

### 1. Exploração do GitHub Copilot

- ✅ Geração de código automático em tempo real.
- ✅ Sugestões de completamento inteligente baseadas no contexto.
- ✅ Testes com diferentes linguagens de programação (ex: JavaScript, Python).

#### 📌 Exemplo de prompt:
```javascript
// Crie uma função que verifica se um número é primo
```

#### 💡 Resultado gerado pelo Copilot:
```javascript
function isPrime(num) {
  if (num <= 1) return false;
  for (let i = 2; i < num; i++) {
    if (num % i === 0) return false;
  }
  return true;
}
```

---

### 2. Exploração da OpenAI (ChatGPT e Playground)

- ✅ Geração de textos, resumos e explicações técnicas.
- ✅ Criação de prompts criativos para simular diferentes cenários.
- ✅ Testes de conteúdo sensível e análise dos filtros de segurança.

#### 📌 Exemplo de prompt:
```
Explique o conceito de aprendizado supervisionado em linguagem simples.
```

#### 💡 Resposta gerada:
> Aprendizado supervisionado é quando um computador aprende com exemplos. Ele recebe dados de entrada e a resposta certa, e tenta descobrir uma forma de prever a resposta certa para novos dados.

---

## 📝 Anotações e Aprendizados

- O Copilot é mais eficaz quando fornecemos contexto suficiente no código.
- A OpenAI possui filtros que bloqueiam conteúdos sensíveis, protegendo contra abusos.
- A criação de prompts claros e objetivos é essencial para obter boas respostas.
- Ferramentas de IA não substituem o conhecimento técnico, mas são ótimos assistentes.
- As respostas podem variar de acordo com o histórico de interação (memória/contexto).

---

## 📁 Estrutura do Repositório

```
📦 laboratorio-ia
 ┣ 📂 exemplos-copilot
 ┃ ┣ 📄 funcao-primo.js
 ┃ ┗ 📄 api-express.js
 ┣ 📂 exemplos-openai
 ┃ ┣ 📄 resumo-aprendizado.txt
 ┃ ┗ 📄 simulacao-dialogo.txt
 ┣ 📄 README.md
```

---

## 🚀 Conclusão

O uso de ferramentas como o Copilot e a OpenAI representa um avanço significativo na produtividade e criatividade em ambientes de desenvolvimento. Este laboratório permitiu entender seus benefícios, limitações e aplicações práticas em diferentes contextos.
