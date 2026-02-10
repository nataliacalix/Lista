# Atividade-2
## *Diferença entre números*
```
fun main() {
    print(primeiro número)
    val numero1 = readLine()!!.toDouble()

    print(segundo número)
    val numero2 = readLine()!!.toDouble()

    val diferenca = numero1 - numero2

    println(diferença entre os números )
}
```
## *Nome completo*
```
fun main() {
    print(nome: Pana)
    val nome = readLine()!!

    print(sobrenome: Favo de Mel)
    val sobrenome = readLine()!!

    println(Nome completo: Pana Favo de Mel)
}

```
## *Quatro operações*
```
fun main() {
    print(primeiro número)
    val a = readLine()!!.toDouble()

    print(segundo número)
    val b = readLine()!!.toDouble()

    println("Soma: ${a + b}")
    println("Subtração: ${a - b}")
    println("Multiplicação: ${a * b}")
    println("Divisão: ${a / b}")
}
```
## *Área do quadrado*
```
fun main() {
    print(lado do quadrado)
    val lado = readLine()!!.toDouble()

    val area = lado * lado
    println(Área do quadrado)
}
```
## *Área do triângulo*
```
fun main() {
    print(base)
    val base = readLine()!!.toDouble()

    print(altura)
    val altura = readLine()!!.toDouble()

    val area = (base * altura) / 2
    println(Área do triângulo)
}
```
## *IMC*
```
fun main() {
    print(peso)
    val peso = readLine()!!.toDouble()

    print(altura)
    val altura = readLine()!!.toDouble()

    val imc = peso / (altura * altura)
    println(IMC)
}

```
## *Idade em dias → anos, meses e dias*
```
fun main() {
    print(idade em dias)
    val dias = readLine()!!.toInt()

    val anos = dias / 365
    val meses = (dias % 365) / 30
    val diasRestantes = (dias % 365) % 30

    println(Anos)
    println(Meses)
    println(Dias)
}
```
## *Média de 3 notas*
```
fun main() {
    print(Nota 1)
    val n1 = readLine()!!.toDouble()

    print(Nota 2)
    val n2 = readLine()!!.toDouble()

    print(Nota 3)
    val n3 = readLine()!!.toDouble()

    val media = (n1 + n2 + n3) / 3
    println(Média final)
}
```
## *Tempo em segundos → h, min, s*
```
fun main() {
    print(tempo em segundos)
    val total = readLine()!!.toInt()

    val horas = total / 3600
    val minutos = (total % 3600) / 60
    val segundos = total % 60

    println(horas h; minutos min; segundos s)
}
```
## *Distância entre dois pontos*
```
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {
    print(x1)
    val x1 = readLine()!!.toDouble()

    print(y1)
    val y1 = readLine()!!.toDouble()

    print(x2)
    val x2 = readLine()!!.toDouble()

    print(y2)
    val y2 = readLine()!!.toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))
    println(Distância)
}
```
## *Expressão matemática (A, B, C)*
```
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {
   
    print(x1)
    val x1 = readLine()!!.toDouble()

    print(y1)
    val y1 = readLine()!!.toDouble()

    print(x2)
    val x2 = readLine()!!.toDouble()

    print(y2)
    val y2 = readLine()!!.toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))
    println(distância entre os pontos )
}
```
## *Custo do carro*
Distribuidor: 28%
 Impostos: 45%
 ```
fun main() {
    print("Custo de fábrica: ")
    val custo = readLine()!!.toDouble()

    val distribuidor = custo * 0.28
    val impostos = custo * 0.45
    val total = custo + distribuidor + impostos

    println("Custo ao consumidor: R$ $total")
}

```
## *Sistema de equações lineares*
```
fun main() {
    println(a, b e c)
    val a = readLine()!!.toDouble()
    val b = readLine()!!.toDouble()
    val c = readLine()!!.toDouble()

    println(d, e e f)
    val d = readLine()!!.toDouble()
    val e = readLine()!!.toDouble()
    val f = readLine()!!.toDouble()

    val denominador = a * e - b * d

    if (denominador == 0.0) {
        println("O sistema não possui solução única.")
    } else {
        val x = (c * e - b * f) / denominador
        val y = (a * f - c * d) / denominador

        println(Valor de x )
        println(Valor de y )
    }
}
```
## *Novo salário (+25%)*
```
fun main() {
    print(Salário atual)
    val salario = readLine()!!.toDouble()

    val novoSalario = salario * 1.25
    println(Novo salário)
}

```
## *Salário com percentual informado*
```
fun main() {
    print(Salário atual)
    val salario = readLine()!!.toDouble()

    print(Percentual de aumento)
    val percentual = readLine()!!.toDouble()

    val novoSalario = salario + (salario * percentual / 100)
    println(Novo salário)
}

```
## *Idade em anos, meses, semanas e dias*
```
fun main() {
    print(Ano de nascimento)
    val nascimento = readLine()!!.toInt()

    print(Ano atual)
    val atual = readLine()!!.toInt()

    val anos = atual - nascimento
    val meses = anos * 12
    val dias = anos * 365
    val semanas = dias / 7

    println(Anos)
    println(Meses)
    println(Semanas)
    println(Dias)
}
```
## *Ração dos gatos*
```
fun main() {
    print(Peso do saco (kg))
    val pesoKg = readLine()!!.toDouble()

    print(Ração diária por gato (g))
    val diaria = readLine()!!.toDouble()

    val totalGramas = pesoKg * 1000
    val consumo5Dias = diaria * 2 * 5
    val restante = totalGramas - consumo5Dias

    println(Ração restante (g))
}
```
## *Troca de valores*
```
fun main() {
    print(A)
    var a = readLine()!!.toInt()

    print(B)
    var b = readLine()!!.toInt()

    val temp = a
    a = b
    b = temp

    println(A)
    println(B )
}
```
## *Volume da caixa retangular*
```
fun main() {
    print(Comprimento)
    val c = readLine()!!.toDouble()

    print(Largura)
    val l = readLine()!!.toDouble()

    print(Altura)
    val a = readLine()!!.toDouble()

    val volume = c * l * a
    println(Volume)
}
```
## *Quadrado da diferença*
```
fun main() {
    print(A)
    val a = readLine()!!.toInt()

    print(B)
    val b = readLine()!!.toInt()

    val resultado = (a - b) * (a - b)
    println(Resultado)
}

```
## *Dólar → Real*
```
fun main() {
    print(Valor em dólar)
    val dolar = readLine()!!.toDouble()

    print(Cotação do dólar)
    val cotacao = readLine()!!.toDouble()

    val real = dolar * cotacao
    println(Valor em reais)
}

```
## *Quadrado da soma (A + B + C)²*
```
fun main() {
    print(A)
    val a = readLine()!!.toInt()
    print(B)
    val b = readLine()!!.toInt()
    print(C)
    val c = readLine()!!.toInt()

    val soma = a + b + c
    val resultado = soma * soma

    println(Resultado)
}

```
## *Operações com números reais*
```
fun main() {
    print(A)
    val a = readLine()!!.toDouble()

    print(B)
    val b = readLine()!!.toDouble()

    println(Soma)
    println(Subtração)
    println(Multiplicação)
    println(Divisão)
}

```
## *Volume da esfera*
```
import kotlin.math.pow

fun main() {
    print(Raio)
    val raio = readLine()!!.toDouble()

    val volume = (4.0 / 3.0) * 3.14159 * raio.pow(3)
    println(Volume da esfera)
}
```## *Volume da esfera*
```
## *Sucessor e antecessor*
```
fun main() {
    print(número)
    val n = readLine()!!.toInt()

    println(Antecessor)
    println(Sucessor)
}
```
