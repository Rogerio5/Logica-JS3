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
  <title>Desafios Finais JS</title>
</head>
<body>
  <h1>💻 Desafios Finais de JavaScript</h1>

  <script>
    // 1
    console.log("Bem-vindo ao meu programa!");

    // 2 e 3
    let nome = "Aline";
    console.log(`Olá, ${nome}!`);
    alert(`Olá, ${nome}!`);

    // 4
    let linguagemFavorita = prompt("Qual a linguagem de programação que você mais gosta?");
    console.log(`Você gosta de ${linguagemFavorita}.`);

    // 5 e 6
    let valor1 = parseInt(prompt("Digite o primeiro valor:"));
    let valor2 = parseInt(prompt("Digite o segundo valor:"));
    let resultadoSoma = valor1 + valor2;
    let resultadoSubtracao = valor1 - valor2;
    console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultadoSoma}.`);
    console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultadoSubtracao}.`);

    // 7
    let idade = parseInt(prompt("Qual é a sua idade?"));
    if (idade >= 18) {
      console.log("Você é maior de idade.");
    } else {
      console.log("Você é menor de idade.");
    }

    // 8
    let numero = parseInt(prompt("Digite um número:"));
    if (numero > 0) {
      console.log("O número é positivo.");
    } else if (numero < 0) {
      console.log("O número é negativo.");
    } else {
      console.log("O número é zero.");
    }

    // 9
    console.log("Contagem de 1 a 10:");
    let contador = 1;
    while (contador <= 10) {
      console.log(contador);
      contador++;
    }

    // 10
    let nota = parseFloat(prompt("Digite sua nota:"));
    if (nota >= 7) {
      console.log("Aprovado");
    } else {
      console.log("Reprovado");
    }

    // 11
    let aleatorio = Math.random();
    console.log(`Número aleatório entre 0 e 1: ${aleatorio}`);

    // 12
    let inteiro1a10 = Math.floor(Math.random() * 10) + 1;
    console.log(`Número aleatório entre 1 e 10: ${inteiro1a10}`);

    // 13
    let inteiro1a1000 = Math.floor(Math.random() * 1000) + 1;
    console.log(`Número aleatório entre 1 e 1000: ${inteiro1a1000}`);
  </script>
</body>
</html>
