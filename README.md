# pythonconceitos
Conceitos da linguagem Python
<h2>História do Python</h2>
• <b>Python</b> nasceu em <b>1989</b> como um hobby do programador <b>Guido Van Rossum</b>,  matemático e programador de computadores holandês. A ideia inicial era dar continuidade a <i>linguagem ABC</i> que era desenvolvida no <b>Centro de Pesquisa Holandês(CWI).</b>
<br>
Python foi <b>influenciado</b>por ABC que era uma linguagem pensada para iniciantes devido a sua <b>facilidade</b> de aprendizagem e utilização.
<br>
• Os <b>objetivos</b> de Van Rossum para a linguagem Python era
<br>
- Ser uma linguagem fácil e intuitiva
<br>
- Código aberto para que todos possam contribuir
<br>
- Código tão inteligível quando o inglês
<br>
- Adequada para tarefas diárias e produtiva
<br>
Em 1989 é iniciado o <b>desenvolvimento</b> e só em fevereiro de 1991 é <b>lançada</b> a primeira versão pública 0.9.0
<br>
<b>Python só não é bom para aplicativos mobile</b>, mesmo sendo possível a criação, não se iguala a ferramentas próprias como Android Studio, Swift er=ntre outros
<br>
• Python é uma escolha muito <b>versátil</b>
<br>
- Tipagem dinâmica e forte
<br>
- Multiplataforma e multiparadigma
<br>
- Comunidade gigante e ativa
<br>
- Curva de aprendizado baixa
<br>
A extensão de arquivos python é <i>.py</i>
<br>
para exibir um texto no console, o comando utilizado é <b>print("texto")</b>, não é necessário utilizar ponto e vírgula
<br>
para concatenar strings em python, pode utilizar o sinal de adição, como por exemplo <i>"mensagem um" + "mensagem 2"</i>
<br>
Os tipos servem para <b>definir</b> as <b>características</b> e <b>comportamentos</b> de um valor(objeto) para um interpretador
<br>
<b>TIPOS DE VALORES</b>
<br>
texto | str
<br>
numérico | int, float, complex (complex não é muito usado)
<br>
sequência | list, tuple, range
<br>
mapa | dict
<br>
coleção | set, frozenset
<br>
booleano | bool
<br>
binário | bytes, bytearray, memoryview
<br><br>
• <b>mapa</b> é chave e valor, como <i>nome = chave</i>, por exemplo <i>leonardo = valor</i>
<br>
• <b>sequência</b> é algo como 1, 2, 3, ..., n; até mesmo textos como hakuna matata é uma sequência de letras
<br>
• <b>coleção</b> é parecido com a lista, porém, não deixa elementos repetidos
<br>
• <b>modo interativo</b> permite que escreva o código e veja o resultado na hora
<br>
existe <i>dois modos</i> de iniciar o código, pode escrever <b>python</b> no terminal ou executar o script com a tag <b>flag -i</b> (por exemplo "python -i app.py")
• <b>dir</b> sem argumentos retorna a lista de nomes no escopo local atual, com um argumento retorna uma lista de atributos válidos para o objeto, por exemplo
<br>
dir() e dir (100)
<br>
• <b>help</b> invoca o sistema de ajuda integrado. É possível fazer buscas em modo interativo ou informar por parâmetro qual o nome do módulo, função, classe, método ou variável que deseja saber, por exemplo:
<br>
help()
help(100)
<br>
caso a lista for muito grande, basta apertar a tecla "q" que levará ao final
<br>
• <b>concatenação</b>, a melhor maneira de concatenar string e int utiliza chaves e fica dentro das aspas, por exemplo
<br>
nome = "Leonardo Stella"
<br>
idade = 26
<br>
eu = {f"Olá, meu nome é {nome} e tenho {idade} anos de idade."}
<br>
Em Python, também é possível declarar <i>várias variáveis</i> em <i>apenas uma linha</i>, algo semelhante ao <b>INSERT INTO</b> do SQL, por exemplo age, name = (26, "Leonardo")
<b>NÃO</b> podemos criar uma variável sem atribuir um valor
<br>
Python não usa <i>constantes</i>, mas usa convenção para indicar que a <b>variável não pode ser alterada</b>
<br>
<b>BOAS PRÁTICAS</b>
<br>
• o padrão de nomes deve ser em <i>snakecase</i>, as palavras são separadas com underline( _ )
<br>
• escolher nomes sugestivos, nomes que você se lembrará após um tempo sem ter contato com o código
<br>
• nome de constantes tem que ficar em maiúsculo por exemplo <b>CPF: 123-456-789-00
<br>
para <b>concatenar</b> variáveis e, somente variáveis usando o <b>print</b> pode usar a <b>vírgula</b>, por exemplo print(nome, idade) #é mostrado Leonardo Stella 26
<b>CONVERTENDO TIPOS</b>
<br>
Em alguns momentos é necessário converter o tipo de uma variável para manipular de forma diferente, por exemplo:
<br>
Variáveis do tipo <i>string</i>, que armazena números e precisamos fazer alguma <b>operação matemática</b> com esse(s) valor(es)
<br>
• <b>preco = 10</b> #definindo o valor 10 à variável
<br>
• <b>print(preco)</b> #resulta 10 na tela
<br>
• <b>preco = float(preco) #convertendo para tipo float
<br>
• <b>print(preco) #agora, mostrando o valor da variável 'preco' no tipo float
<br>
• <b>preco = 10/2</b> #operação com a variável convertida
<br>
• <b>print(preco) #mostrar o resultado da operação na variável
<br>
para converter <i>número</i> para <i>string</i> é um pouco diferente, se usa o comando <b>print(str(preco)), em resumo, tanto a variável quando o str precisa de parenteses
<br>
Na <b>concatenação</b>, o uso do <b>f</b> concatena textos com variáveis, ela mais ou menos "diz" que vai ser inserido variáveis dentro dessa string criada, por exemplo:
<br>
print(f"idade {idade} preco {preco})
<br>
<b>ENTRADA E SAÍDA</b>
• <i>Lendo valores com a função input =></i> A função <b>built-in input</b> é utilizada quando queremos valores da entrada padrão (teclado). Ela recebe um argumento do tipo <i>string</i>, que é exibido para o usuário na saída de tela padrão (tela/monitor). A função lê a entrada, converte para string e retorna o valor, por exemplo:
<br>
nome = input("Informe seu nome: ")
<br>
• <i>Exibindo valores com a função print =></i> A função <b>built-in print</b> é utilizada quando queremos exibir dados na saída padrão (tela). Ela recebe um argumento do tipo <i>var args</i> de objeto e 4 argumentos opcionais(sep, end, le e flush). Todos os objetos são convertidos para string, separados por sep e terminados por end. A string final é exibida para o usuário
<br> 
<b>
nome = "Leonardo"
<br>
sobrenome = "Stella"
<br>
print(nome, sobrenome, eld="...\n")
<br>
print(nome, sobrenome, sep="#")
</b>
<br>
>Leonardo Stela
<br>
>Leonardo Stella... *aqui tem a quebra de linha representada pelo \n no final*
<br>
>Leonardo#Stella *o sep representa o separador, então toda separação de string vai ter o #*
<br>
• Em resumo, neste código é apresentado o <i>end</i> e <i>sep</i>, são colocados no final, <i>end</i> é o que vai ter quando termina e <i>sep</i> é colcoado quando separa
<br>
<b>RECEBER VALORES</b>
• bem simples, para receber valores usa o método <i>input</i>, como no exemplo abaixo
<br>
<b>
nome = input("Digite seu nome: ")
<br>
idade = input("Digite sua idade: ")
<br>
<b>OPERADORES ARITMÉTICOS</b>
<br>
• Eles executam operações matemáticas, como adição, subtração, etc com os operandos, por exemplo
<br>
<b>print(1+1)</b> >adição, resulta em 2
<b>print(10-2)</b> >subtração, resulta em 8
<b>print(4*3)</b> >multiplica~ção, resulta em 12
<br>
• Para <i>retornar divisão em inteiro</i> mesmo resultando em número real, usa <b>barra dupla (//)</b>, por exemplo
<br>
<b>print(3//2)</b> >resulta em 1
<br>
<b>exponenciação</b> é respresentado por <i>**</i>
<br>
• Na matemática existe uma <b>regra</b> que indica quais <b>operações</b> podem ser executadas primeiro. Isso é bastante útil pois ao analisar uma expressão, a depender da ordem das operações o valor pode ser diferente, por exemplo
<br>
x=10-5*2 e x=(10-5)*2
<br>
• A <b>definição</b> indica a seguinte ordem como correta:
<br>
• parentesis
<br>
• expoentes
<br>
• Multiplicações e divisões(da esquerda para a direita)
<br>
• Somas e subtrações(também da esquerda para a direita)
<br>
Os <b>operadores de comparação</b>, como o próprio nome já diz, serve para <b>comparar</b> dois valores, por exemplo
<br>
x = 450
<br>
y = 200
<br>
print(x == y)</b> >retorna False por ser diferente
<br>
Mas também existe o <b>diferente</b> representado por != como no exemplo abaixo
<br>
<b>print(x != y)</b> >retorna True por ser diferente
<br>
<b>OPERADORES DE ATRIBUIÇÃO</b>
• Eles são utilizados para definir o <i>valor</i> inicial ou sobrescrever o valor de uma variável