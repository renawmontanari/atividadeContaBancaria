# Orientação a Objetos

## Este repositório contém a atividade prática do Curso "Orientação a Objetos", que faz parte do Basecamp de Javascript que estudei pela Digital Innovation One.

Atividade: Conta Bancária
Nesta atividade, vamos testar os conceitos de Orientação a Objetos simulando a criação de diversos tipos de contas bancárias e operações disponíveis em cada uma.

<ul>
  <li>Crie a classe <code>ContaBancaria</code>, que possui os parâmetros <code>agencia</code>, <code>numero</code>, <code>tipo</code> e <code>saldo</code>;</li>
  <li>Dentro de <code>ContaBancaria</code>, construa o getter e o setter de <code>saldo</code>;</li>
  <li>Dentro de <code>ContaBancaria</code>, crie os métodos <code>sacar</code> e <code>depositar</code>;</li>
  <li>Crie uma classe-filha chamada <code>ContaCorrente</code> que herda todos esses parâmetros e ainda possua o parâmetro <code>cartaoCredito</code>;</li>
  <li>Ainda em <code>ContaCorrente</code>, construa o getter e o setter de <code>cartaoCredito</code>;</li>
  <li>Ainda em <code>ContaCorrente</code>, faça com que o <code>tipo</code> seja 'conta corrente' por padrão;</li>
  <li>Crie uma classe-filha chamada <code>ContaPoupanca</code> que herda todos os parâmetros de <code>ContaBancaria</code>;</li>
  <li>Crie uma classe-filha chamada <code>ContaUniversitaria</code> que herda todos os parâmetros de <code>ContaBancaria</code>;</li>
  <li>Faça com que o método <code>saque</code> de <code>ContaUniversitaria</code> apenas seja capaz de sacar valores menores que 500 reais.</li>
</ul>
