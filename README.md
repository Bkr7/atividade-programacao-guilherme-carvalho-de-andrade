🟢 Atividade: Engenharia de Prompt e Aplicações em Python
1️⃣ Código base
def mensagem():
    print("Bem-vindo!")

mensagem()
🔹 Explicação passo a passo

def mensagem():
Cria uma função chamada mensagem.

print("Bem-vindo!")
Este código será executado quando a função for chamada.

mensagem()
Chama a função, ou seja, executa o que está dentro dela.

2️⃣ Prompts e versões do LLM
🟢 Versão 1 – Simples e direta

Prompt:

Explique o que são funções em Python e dê exemplos básicos com código.

Resposta do LLM:

# Função simples
def saudacao():
    print("Olá!")

saudacao()

# Função com parâmetro
def saudacao(nome):
    print("Olá,", nome)

saudacao("Maria")
🔵 Versão 2 – Mais detalhada

Prompt:

Ensine funções em Python para iniciantes, incluindo definição, parâmetros, retorno (return) e exemplos práticos.

Resposta do LLM:

# Função com retorno
def soma(a, b):
    return a + b

resultado = soma(2, 3)
print(resultado)

# Exemplo prático
def verificar_par(numero):
    if numero % 2 == 0:
        return "Par"
    else:
        return "Ímpar"

print(verificar_par(4))
🟣 Versão 3 – Focada em prática

Prompt:

Crie exercícios sobre funções em Python, com exemplos e respostas explicadas para iniciantes.

Resposta do LLM:

Exercício 1: Função que mostra "Olá, mundo!"

def ola():
    print("Olá, mundo!")

ola()

Exercício 2: Função que retorna o dobro de um número

def dobro(n):
    return n * 2

print(dobro(5))

Exercício 3: Função que verifica se um número é positivo ou negativo

def verificar(numero):
    if numero >= 0:
        return "Positivo"
    else:
        return "Negativo"

print(verificar(-3))
3️⃣ Efeito das instruções do prompt
Versão	Instrução	Efeito na resposta	Resumo
🟢 1	Explique… e dê exemplos básicos	Explicação curta, poucos exemplos, linguagem direta	Resposta rápida, foco no básico
🔵 2	Ensine… incluindo definição, parâmetros, return	Explicação mais completa, conceitos específicos, estrutura organizada	Didática, parecendo uma aula
🟣 3	Crie exercícios…	Foco em prática, exercícios comentados	Voltada para aprendizado ativo
4️⃣ Qual versão é mais útil para aprendizado

Versão 1 (simples)

Boa para introdução rápida

Limite: pouca explicação

Ideal para entender a ideia geral

Versão 2 (detalhada) ✅ mais útil

Boa para compreensão sólida

Explica parâmetros, return e exemplos práticos

Ideal para entender conceito e aplicação

Facilita passar para exercícios

Versão 3 (prática)

Boa para treinar habilidades

Dá exercícios e soluções

Limitada se você ainda não entende os conceitos básicos

5️⃣ Aplicações reais em programação
1️⃣ Aprender conceitos rapidamente

Situação: entender funções recursivas ou outro conceito novo

Prompt sugerido:

“Explique funções recursivas em Python para iniciantes, com exemplos simples.”

Benefício: o LLM gera explicação passo a passo e código de exemplo.

2️⃣ Praticar com exercícios

Situação: já entendeu o conceito

Prompt sugerido:

“Crie exercícios sobre funções recursivas em Python, com soluções explicadas.”

Benefício: você recebe exercícios prontos para treinar.

3️⃣ Refatorar ou melhorar código

Situação: código funciona, mas pode ser otimizado

Prompt sugerido:

“Melhore este código Python usando boas práticas, funções eficientes e recursos avançados como lambda ou list comprehensions.”

Benefício: o LLM sugere código mais limpo, organizado e profissional.

6️⃣ Dicas práticas para usar LLM na programação

Sempre defina o objetivo do prompt: aprender, praticar ou otimizar

Ajuste o nível de detalhe conforme seu conhecimento

Itere e refine o prompt se precisar de mais exemplos ou explicações

Combine versões detalhada + prática para máximo aprendizado
