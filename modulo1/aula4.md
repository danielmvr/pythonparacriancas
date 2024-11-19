# Aula 4: Decifrando Mistérios – Introdução às Decisões com Condições

![image](https://github.com/user-attachments/assets/e8388da7-fff4-4c24-9f33-ccd54ea47327)


**Objetivo da Aula**: Apresentar o conceito de estruturas condicionais em Python, ensinando os alunos a tomar decisões no código usando o comando if.

---

## 1. A Jornada Continua: Explorando a Floresta dos Códigos

**História**: "Vocês já são verdadeiros aventureiros da Floresta dos Códigos! Aprenderam a se comunicar com o computador, guardar informações, e até resolver cálculos. Mas, às vezes, encontramos caminhos misteriosos que exigem decisões. Qual porta abrir? Qual direção seguir? Hoje, aprenderemos a ensinar o computador a decidir o que fazer!"

---

## 2. O Que São Condições?

**Explicação Simples**: "Criar condições é como fazer perguntas para o computador. Por exemplo: 'Está chovendo? Se sim, pegue o guarda-chuva. Se não, aproveite o sol!'"

**Interatividade**: Pergunte às crianças: "Que tipo de perguntas vocês gostariam de ensinar ao computador? Talvez, 'Eu tenho idade suficiente para jogar um jogo?' ou 'Tenho dinheiro para comprar um doce?'"

---

## 3. Usando o Comando if

**Introdução ao if**: "O comando mágico if ajuda o computador a tomar decisões baseadas em condições. Por exemplo:

- 'Se (if) for verdade que está calor, vamos tomar sorvete.'
- 'Se (if) eu tiver feito a lição de casa, posso jogar videogame.'

Em Python, o comando if funciona assim:

**Exemplo Simples**:

```python
idade = 8

if idade >= 8:
    print("Você pode entrar na aventura!")
```

**Explicação**: "Aqui, o computador verifica se a condição idade >= 8 é verdadeira. Se for, ele mostra a mensagem: 'Você pode entrar na aventura!'"

---

## 4. Adicionando o Comando else

**Explicação**: "Às vezes, queremos que o computador tome uma ação diferente se a condição não for verdadeira. Para isso, usamos o comando else."

**Exemplo**:

```python
idade = 6

if idade >= 8:
    print("Você pode entrar na aventura!")
else:
    print("Você ainda não tem idade suficiente.")
```

**Explicação do Exemplo**: "Se a condição idade >= 8 não for verdadeira, o computador executa o que está dentro de else."

---

## 5. Hora de Experimentar: Criando Decisões

**Atividade Prática**: "Agora é a vez de vocês! Vamos criar condições que ajudem o computador a tomar decisões."

**Desafios**:

- Desafio 1: Verificar se uma pessoa tem idade suficiente para assistir a um filme:

```python
idade = 10

if idade >= 12:
    print("Você pode assistir ao filme.")
else:
    print("O filme não é permitido para sua idade.")
```

- Desafio 2: Decidir se um número é maior que 10:

```python
numero = 15

if numero > 10:
    print("O número é maior que 10.")
else:
    print("O número não é maior que 10.")
```

---

## 6. Pequeno Desafio: Criando um Jogo de Perguntas

**Explicação**: "Vamos criar um pequeno jogo onde o computador faz uma pergunta e responde baseado na resposta!"

**Exemplo Completo**:

```python
resposta = "sim"

if resposta == "sim":
    print("Que ótimo! Vamos continuar nossa aventura!")
else:
    print("Tudo bem, vamos tentar outra hora.")
```

**Desafio**: Modificar o jogo para que o computador faça perguntas diferentes, como:

- "Você gosta de pizza?"
- "Hoje é seu dia favorito da semana?"

## 7. Encerramento e Reflexão

**Reflexão**: "Hoje vocês aprenderam a ensinar o computador a pensar e tomar decisões. Com if e else, podem criar aventuras interativas, jogos e muito mais!"

**Tarefa para Casa (Opcional)**: "Crie um pequeno código onde o computador decida algo por você. Por exemplo, 'Posso brincar lá fora?' ou 'Devo comer mais um pedaço de bolo?' Use a criatividade!"

**Mensagem Final**: "Vocês são verdadeiros decifradores de mistérios! Preparem-se, pois nas próximas aulas aprenderemos ainda mais segredos da programação!"
