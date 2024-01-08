# Projeto: Calculadora Simples em Kotlin

## Descrição do Projeto

Este projeto consiste em uma calculadora simples implementada em Kotlin. A calculadora suporta operações de soma, multiplicação e limpeza, permitindo ao usuário realizar cálculos básicos e visualizar os resultados.

## Funcionalidades Principais

1. **Soma de Valores:**
   - A função `somar` permite a adição de um ou mais valores à calculadora.

2. **Multiplicação por Valor:**
   - A função `multiplicar` realiza a multiplicação do resultado atual por um valor específico.

3. **Limpeza do Resultado:**
   - A função `limpar` redefine o resultado da calculadora para zero.

4. **Visualização do Resultado:**
   - A função `print` exibe o resultado atual no console.

5. **Obtenção do Resultado Atual:**
   - A função `obterResultado` retorna o valor atual armazenado na calculadora.

## Utilização do Projeto

1. **Instalação:**
   - Clone o repositório: `git clone https://github.com/lurregiabarreto/CalculadoraSimplesKotlin.git`
   - Navegue até o diretório do projeto: `cd calculadora-simples-kotlin`

2. **Execução:**
   - Execute o arquivo principal: `kotlin Calculadora.kt`

3. **Exemplo de Uso:**
   ```kotlin
   val calculadora = Calculadora()
   calculadora.somar(1, 2, 3).multiplicar(3).print()
   calculadora.somar(7, 10).print().limpar()

   println(calculadora.obterResultado())
   ```
