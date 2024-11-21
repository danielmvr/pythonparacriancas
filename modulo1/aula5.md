## 1. Relembrando Nossa Aventura

![image](https://github.com/user-attachments/assets/0c58e379-a094-4c2d-a23a-1fe8c2ec54bf)


**História**: "Vocês já sabem tomar decisões e fazer perguntas mágicas ao computador. Mas, e se precisarmos repetir algo várias vezes? Por exemplo, desenhar cinco estrelas ou contar de 1 até 10? Hoje, aprenderemos a usar feitiços especiais chamados laços de repetição para fazer isso de forma mágica e eficiente!"

---

## 2. O Que São Laços de Repetição?

**Explicação Simples**: "Um laço de repetição é como uma roda mágica que gira até completar uma tarefa. Por exemplo:
'Conte de 1 até 10.'
'Desenhe 3 corações.'
O computador pode repetir essas ações sem que precisemos escrever o mesmo código várias vezes."

---

## 3. O Laço for

**Introdução ao for**: "Usamos o laço for quando sabemos quantas vezes queremos repetir algo."

Exemplo 1: Contar de 1 a 5

```python
for numero in range(1, 6):
    print(numero)
```

**Explicação**: "O comando range(1, 6) diz ao computador para contar de 1 até 5 (o 6 não é incluído). A cada volta do laço, a variável numero muda para o próximo número."

---

## 4. O Laço while

**Introdução ao while**: "Usamos o laço while quando queremos repetir algo enquanto uma condição for verdadeira."

Exemplo 1: Contar até 5

```python

contador = 1

while contador <= 5:
    print(contador)
    contador += 1  # Adiciona 1 ao contador
```

**Explicação**: "O laço continua girando enquanto a condição contador <= 5 for verdadeira. O comando contador += 1 faz o número aumentar a cada repetição."

---

## 5. Hora de Experimentar: Brincando com Repetições

**Atividade Prática**: "Agora vamos criar nossas próprias repetições! Aqui estão alguns desafios para vocês."

- Desafio 1: Mostrar a frase "Python é divertido!" 5 vezes.

```python
for i in range(5):
    print("Python é divertido!")
```

- Desafio 2: Contar de 10 até 1 (contagem regressiva).

```python
contador = 10

while contador >= 1:
    print(contador)
    contador -= 1
```

---

## 6. Pequeno Desafio: Um Jogo com Repetições

**Descrição do Jogo**: "Vamos criar um jogo simples onde o computador pede para o jogador adivinhar um número. O jogo só termina quando o jogador acertar!"

Exemplo Completo:

```python
import random

numero_secreto = random.randrange(1,10)
chute = 0

while chute != numero_secreto:
    chute = int(input("Adivinhe o número: "))
    if chute == numero_secreto:
        print("Parabéns, você acertou!")
    else:
        print("Tente novamente!")
```

**Desafio**: Modificar o jogo para que o computador dê dicas, como "O número é maior" ou "O número é menor".

---

## 7. Encerramento e Reflexão

**Reflexão**: "Hoje vocês aprenderam a usar laços mágicos para repetir ações. Agora, podem criar códigos que fazem tarefas repetitivas de forma muito mais fácil!"

**Tarefa para Casa** (Opcional): "Escrevam um código que mostre a tabuada de um número usando um laço de repetição. Por exemplo, a tabuada do 2: 2x1, 2x2, 2x3... até 2x10."

**Mensagem Final**: "Estamos avançando rápido pela nossa jornada! Na próxima aula, aprenderemos a criar listas mágicas para guardar vários itens de uma só vez. Preparem-se para mais aventuras!"
