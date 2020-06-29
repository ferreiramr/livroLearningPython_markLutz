# NOTAS DE ESTUDO DO LIVRO LEARNING PYTHON

## INFORMAÇÕES DO LIVRO

Título: Learning Python, 5th Edition

Editora:  O'Reilly Media, Inc.

[Página do livros](https://www.oreilly.com/library/view/learning-python-5th/9781449355722/)

[Baixar os códigos de exemplo](https://resources.oreilly.com/examples/0636920028154/)

## TRADUÇÃO DOS SUMÁRIOS E QUESTIONÁRIOS

### Cápitulo 01 - Uma sessão de perguntas e respostas

#### Resumo do capítulo

E isso conclui a ideia geral do livro. Neste capítulo, nós exploramos alguns das razões pelas quais as pessoas escolhem Python para programas suas tarefas. Nos também vimos como é aplicada e demos olha olhada em quem esta usando hoje. Meu objetivo é ensinar Python, sem vende-la. A melhor maneira de julgar um linguagem de programação é a vela em ação, então o restante do livro foca inteiramente nos detalhes da linguagem que explicaremos aqui.

Os próximos dois capítulos iniciam sua introdução técnica a linguagem. Nelas, vamos explorar maneiras de executar programas em Python, dar uma olhada no modelo de execução byte code, e conhecer o básico de módulos para salvar códigos. O objetivo é dar a você apenas informação suficiente para rodar exemplos e exercícios do resto do livro. Você não estará realmente programando até o Capítulo 4, mas verifique os detalhes antes de prosseguir.

#### Teste seus conhecimentos

1. Quais são as seis principais razões para as pessoas escolher Python?
    > Qualidade de software, developer productivity, programas de portabilidade, bibliotecas de suporte, integração de componentes e pelo simples prazer. Destes,  qualidade e produtividade parecem ser os principais motivos que levam as pessoas a escolherem Python.

2. Nomeie quatro empresas de destaque que utilizam Python dia a dia.
    > Google, Industrial Light & Magic, CCP Games, Jet Propulsion Labs, Maya, ESRI e outras mais. Quase todas as empresas de que desenvolver software utiliza Python utiliza Python de alguma forma, seja na estratégia de desenvolvimento de longo prazo ou tarefas intermediárias como teste e administração de sistemas.

3. Por que você não deveria utilizar Python em sua aplicação?
    > A princípal desvantagem de Python é a performance: Não executa tão rápido quanto linguagens completamente compiladas como C e C++. Por outro lado é rápido o suficiente para maioria das aplicações, um típico código em Python executa quase tão rápido quanto C, porque utiliza código em C no interpretador. Se a velocidade é crítica, extensões compiladas estão disponíveis para várias partes da sua aplicação.

4. O que vocÊ pode fazer com Python?
    > Você pode utilizar Python para praticamente qualquer coisa que utilize um computador, para desenvolver um site, jogos, robótica e para controlar uma nave espacial.

5. O que significa da declaração `import this` em Python?
    > Isto é mencionada nas notas de rodapé: `import this` inicia um *Ester egg* em Python que exibe algumas das filosofias por baixo da linguagem. Você irá aprender com iniciar esta instrução no próximo capítulo.

6. Por que "*spam*" aparece em tantos exemplos de livros de Python e na Internet?
    > "*Spam*" é um referência do famoso grupo Monty Python em que pessoas estão tentando pedir comida em uma cafeteria e são afogados em um coro de Vikings cantando sobre *spam*. Ah, e também é um nome comum de variável nos scripts Python

7. Qual é sua cor favorita?
    > Azul. Não, amarelo! (Veja a resposta anterior.)

### Capítulo 02: Como Python executa programas

#### Resumo do capítulo

Este capítulo apresentou uma introdução ao modelo de execução da Linguagem Python - Como Python executa seus programas - e exploramos algumas variações neste modelo: complicadores em tempo execução e similares. Embora você não precise se familiarizar com os componentes internos da linguagem para escrever scripts, o breve conhecimento apresentado neste capítulo ira ajuda a entender como seus programas são executados quando você escreve-los. No próximo capítulo, você irá iniciar escrever e executar códigos por si só. Mas antes, aqui está o questionário do capítulo.

#### Teste seus conhecimentos

1. O que é o interpretador Python?
    > O interpretador Python é um programa que executa os programas que você escreve.

2. O que é o código fonte?
    > O código fonte são os comando escritos para seu programa - ele consiste em um texto em códigos de texto que normalmente terminam com a extensão *.py*.

3. O que é o byte code?
    > Byte code é a forma de baixo nível de seu programa após ser compilado. Python automaticamente salva o byte code em arquivos com a extensão *.pyc*.

4. O que é a PVM?
    > A PVM é a *Python Virtual Machine* - o motor em tempo de execução que interpreta seu código compilado.

5. Dê o nome de duas ou mais variações na modelo de execução Python.
    > *Psyco*, *Shed* and *frozen binaries* são todas variações no modelo de execução. Uma alternativa adicional de implementação da Python, nomeado nas duas próximas repostas, modifica o modelo e também a forma de alguma maneira - por substituição do *byte code* e *VMs*, ou adicionando ferramentas e *JITs*.

6. Como *CPython*, *Jython* and *IronPython* são diferentes?
    > *CPython* é uma implementação padrão da linguagem. *Jython* and *IronPython* implementa programas Python para uso nos ambientes Java e .NET, respectivamente; eles d

7. O que é *Stackless* and *PyPy*?
    > *Stackless* é uma versão melhorada de Python otimizada para concorrência, e PyPy ia a reimplementação de Python focada em velocidade. PyPy também é o sucessor do *Psyco* e incorpora os conceitoss *JIT* pioneiros na *Psyco*
