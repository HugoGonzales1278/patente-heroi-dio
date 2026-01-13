# patente-heroi-dio
classificação do nível de herói

# 🦸 Classificador de Nível de Herói

Projeto desenvolvido como parte de um **desafio prático da DIO (Digital Innovation One)**, com o objetivo de aplicar conceitos fundamentais de lógica de programação utilizando **JavaScript**.

---

## 📌 Descrição do Desafio

O desafio consiste em criar um programa que classifique o **nível de um herói** com base na sua **experiência (XP)**.  
A aplicação utiliza **variáveis**, **operadores**, **estruturas de decisão** e **laços de repetição**, conforme solicitado.

Ao final da execução, o programa exibe a seguinte mensagem:

> **"O Herói de nome {nome} está no nível de {nível}"**

---

## 🧠 Conceitos Utilizados

- Variáveis
- Operadores lógicos e relacionais
- Estruturas condicionais (`if`, `else if`, `else`)
- Laço de repetição (`for`)
- Template Strings
- Lógica de programação

---

## 🏆 Regras de Classificação

| Experiência (XP) | Nível |
|------------------|-------|
| Menor que 1.000 | Ferro |
| 1.001 a 2.000 | Bronze |
| 2.001 a 5.000 | Prata |
| 5.001 a 7.000 | Ouro |
| 7.001 a 8.000 | Platina |
| 8.001 a 9.000 | Ascendente |
| 9.001 a 10.000 | Imortal |
| Maior ou igual a 10.001 | Radiante |

---

## 💻 Exemplo de Código

```javascript
let nomeHeroi = "Arthas";
let xpHeroi = 8500;
let nivel = "";

if (xpHeroi < 1000) {
    nivel = "Ferro";
} else if (xpHeroi <= 2000) {
    nivel = "Bronze";
} else if (xpHeroi <= 5000) {
    nivel = "Prata";
} else if (xpHeroi <= 7000) {
    nivel = "Ouro";
} else if (xpHeroi <= 8000) {
    nivel = "Platina";
} else if (xpHeroi <= 9000) {
    nivel = "Ascendente";
} else if (xpHeroi <= 10000) {
    nivel = "Imortal";
} else {
    nivel = "Radiante";
}

console.log(`O Herói de nome ${nomeHeroi} está no nível de ${nivel}`);
▶️ Como Executar o Projeto
Clone este repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/classificador-nivel-heroi.git
Acesse a pasta do projeto:

bash
Copiar código
cd classificador-nivel-heroi
Execute o arquivo com Node.js:

bash
Copiar código
node index.js
📁 Estrutura do Projeto
pgsql
Copiar código
📦 classificador-nivel-heroi
 ┣ 📜 index.js
 ┗ 📜 README.md
🚀 Possíveis Melhorias
Utilizar funções para tornar o código mais reutilizável

Implementar entrada de dados via terminal

Criar uma versão com interface HTML

Adaptar para outras linguagens (Python, Java, etc.)

👨‍💻 Autor
Projeto desenvolvido por Hugo Gonzales Silveira
Desafio proposto pela Digital Innovation One (DIO)

📜 Licença
Este projeto é livre para fins de estudo e aprendizado.

yaml
Copiar código

