# Logica-JS3

# <body>
  <h1>Resolução dos Desafios do Curso de Lógica de Programação 💡</h1>

  <p>Praticar a lógica de programação, incluindo conceitos como <strong>variáveis</strong>, <strong>condicionais (if-else)</strong>, <strong>loops (while)</strong> e <strong>interações com o usuário (alert, prompt)</strong>, é essencial para sua carreira de desenvolvimento de software.</p>
  <p>Esses fundamentos fornecem a base para <em>resolver problemas de forma estruturada</em>, <em>tomar decisões no código</em>, <em>criar iterações controladas</em> e <em>interagir eficazmente com os usuários</em>.</p>
  <p>Compreender esses conceitos não apenas facilita o aprendizado de novas linguagens e tecnologias, mas também capacita você a <strong>criar soluções inovadoras</strong>, <strong>depurar eficientemente</strong> e <strong>manter a qualidade</strong> ao longo do ciclo de vida do software.</p>
  <p>Portanto, investir tempo nesses princípios desde cedo é fundamental para <strong>construir uma base sólida e bem-sucedida</strong> no campo da programação.</p>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Desafios Finais - JavaScript</title>
</head>
<body>
  <h1>🚀 Desafios Finais de JavaScript</h1>

  <script>
    // 1 - Mensagem de boas-vindas
    console.log("1 - Bem-vindo ao meu programa!");

    // 2 - Saudação com nome
    let nome = "Aline";
    console.log(`2 - Olá, ${nome}!`);

    // 3 - Saudação com alert
    let nome2 = "Aline";
    alert(`3 - Olá, ${nome2}!`);

    // 4 - Pergunta sobre linguagem favorita
    let linguagemFavorita = prompt("4 - Qual a linguagem de programação que você mais gosta?");
    console.log(`4 - Você gosta de ${linguagemFavorita}.`);

    // 5 - Soma de dois valores
    let valor1 = parseInt(prompt("5 - Digite o primeiro valor para soma:"));
    let valor2 = parseInt(prompt("5 - Digite o segundo valor para soma:"));
    let resultadoSoma = valor1 + valor2;
    console.log(`5 - A soma de ${valor1} e ${valor2} é igual a ${resultadoSoma}.`);

    // 6 - Subtração de dois valores
    let valor1Sub = parseInt(prompt("6 - Digite o primeiro valor para subtração:"));
    let valor2Sub = parseInt(prompt("6 - Digite o segundo valor para subtração:"));
    let resultadoSubtracao = valor1Sub - valor2Sub;
    console.log(`6 - A diferença entre ${valor1Sub} e ${valor2Sub} é igual a ${resultadoSubtracao}.`);

    // 7 - Verificação de maioridade
    let idade = parseInt(prompt("7 - Qual é a sua idade?"));
    if (idade >= 18) {
      console.log("7 - Você é maior de idade.");
    } else {
      console.log("7 - Você é menor de idade.");
    }

    // 8 - Verificação de número positivo, negativo ou zero
    let numero = parseInt(prompt("8 - Digite um número:"));
    if (numero > 0) {
      console.log("8 - O número é positivo.");
    } else if (numero < 0) {
      console.log("8 - O número é negativo.");
    } else {
      console.log("8 - O número é zero.");
    }

    // 9 - Contagem com loop while
    console.log("9 - Contando de 1 a 10:");
    let contador = 1;
    while (contador <= 10) {
      console.log(`9 - ${contador}`);
      contador++;
    }

    // 10 - Verificação de aprovação com nota
    let nota = parseFloat(prompt("10 - Digite sua nota:"));
    if (nota >= 7) {
      console.log("10 - Aprovado");
    } else {
      console.log("10 - Reprovado");
    }

    // 11 - Número aleatório entre 0 e 1
    let aleatorio = Math.random();
    console.log(`11 - Número aleatório entre 0 e 1: ${aleatorio}`);

    // 12 - Número inteiro entre 1 e 10
    let inteiro1a10 = Math.floor(Math.random() * 10) + 1;
    console.log(`12 - Número aleatório entre 1 e 10: ${inteiro1a10}`);

    // 13 - Número inteiro entre 1 e 1000
    let inteiro1a1000 = Math.floor(Math.random() * 1000) + 1;
    console.log(`13 - Número aleatório entre 1 e 1000: ${inteiro1a1000}`);
  </script>
</body>
</html>
