⚔️ Desafio Classificador de Nível de Herói

🎯 Objetivo

Este projeto tem como objetivo classificar o nível de um herói com base em sua quantidade de experiência (XP). Para isso, foram utilizadas variáveis, operadores, laços de repetição (embora não sejam estritamente necessários para este desafio, a estrutura de decisão if/else cumpre o papel de forma mais direta) e estruturas de decisão.

💻 Tecnologias Utilizadas

O código foi desenvolvido em:

JavaScript

📂 Estrutura de Decisão

O nível do herói é determinado por uma estrutura de decisão if-else if-else que verifica o XP e atribui um nível correspondente.

XP do Herói	Nível
Menor que 1.000	Ferro
1.001 a 2.000	Bronze
2.001 a 5.000	Prata
5.001 a 7.000	Ouro
7.001 a 8.000	Platina
8.001 a 9.000	Ascendente
9.001 a 10.000	Imortal
Maior ou igual a 10.001	Radiante

Exportar para as Planilhas

✨ Como Rodar o Código

Você pode executar o código diretamente no seu navegador, no console, ou usando o Node.js.

Código JavaScript
JavaScript

// Variáveis para o nome e a quantidade de experiência (XP) do herói
let nomeHeroi = "Kael'thas";
let xpHeroi = 9500;
let nivelHeroi;

// Estrutura de decisão para determinar o nível com base no XP
if (xpHeroi < 1000) {
    nivelHeroi = "Ferro";
} else if (xpHeroi >= 1001 && xpHeroi <= 2000) {
    nivelHeroi = "Bronze";
} else if (xpHeroi >= 2001 && xpHeroi <= 5000) {
    nivelHeroi = "Prata";
} else if (xpHeroi >= 5001 && xpHeroi <= 7000) {
    nivelHeroi = "Ouro";
} else if (xpHeroi >= 7001 && xpHeroi <= 8000) {
    nivelHeroi = "Platina";
} else if (xpHeroi >= 8001 && xpHeroi <= 9000) {
    nivelHeroi = "Ascendente";
} else if (xpHeroi >= 9001 && xpHeroi <= 10000) {
    nivelHeroi = "Imortal";
} else { // Se o XP for 10001 ou mais
    nivelHeroi = "Radiante";
}

// Mensagem de saída
console.log(`O Herói de nome ${nomeHeroi} está no nível de ${nivelHeroi}`);

🚀 Saída

A saída final exibirá uma mensagem formatada, mostrando o nome do herói e seu nível:

"O Herói de nome **{nome}** está no nível de **{nivel}**"
