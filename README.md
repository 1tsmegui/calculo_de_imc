<h1>Documentação do Projeto</h1>
<h1>Calculadora de IMC</h1>

<h2>Objetivo:</h2>

<h3>Este projeto implementa uma calculadora de IMC utilizando HTML, CSS e JavaScript.
O usuário insere seu peso e altura para calcular o IMC e visualizar sua classificação de peso de acordo com as diretrizes da OMS.</h3>
<h2>Estrutura HTML:</h2>

<h3>Campos de Entrada: Dois campos <input> do tipo number são fornecidos para que o usuário insira seu peso em quilogramas (kg) e sua altura em metros (m).
Botão de Cálculo: Um botão "Calcular IMC" que, ao ser clicado, invoca a função JavaScript calcularIMC().
Exibição de Resultados: O resultado do cálculo do IMC é exibido dentro de um <div> com id resultado, onde também é exibida a situação correspondente de acordo com a classificação de IMC.</h3>

<h2>Estilos CSS:</h2>

<h3>A página utiliza estilos simples para centralizar o conteúdo (text-align: center) e estilizar os elementos de entrada e botão.
As classes .normal, .alerta e .perigo definem cores diferentes para indicar visualmente a classificação do IMC (normal, sobrepeso, obesidade, etc.)</h3>
<h2>Funcionalidade JavaScript:</h2>

<h3>Função calcularIMC():
Obtém os valores de peso e altura dos campos de entrada.
Verifica se os valores inseridos são números válidos maiores que zero.
Calcula o IMC usando a fórmula: IMC = peso / (altura * altura).
Exibe o resultado do IMC com duas casas decimais.
Determina a situação do usuário com base no valor do IMC calculado e aplica uma classe CSS correspondente para destacar visualmente a situação.</h3>
<h2>Validações:</h2>

<h3>O código inclui validações para garantir que apenas valores numéricos positivos sejam aceitos como entrada para peso e altura.
Utilização:</h3>

<h2>Passos do Usuário:</h2>
<h3>Insira seu peso e altura nos campos indicados.
Clique no botão "Calcular IMC".
Observe o cálculo do IMC e a classificação de peso exibida conforme as diretrizes de saúde.

  
Este projeto fornece uma maneira simples e eficaz para os usuários calcularem seu Índice de Massa Corporal e entenderem sua condição de peso de acordo com os padrões reconhecidos internacionalmente.</h3>
