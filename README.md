# Python Conceitos
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
<br>
<b>saldo = 500</b> #atribuição simples
<br>
<b>print(saldo)</b> #exibir o valor da variável saldo
<br>
<b>saldo += 200</b> #incrementa 200 na variável saldo
<br>
<b>saldo -= 100</b> #decrementa 100 na variável saldo
<br>
<b>saldo *= 2</b> # multiplica por 2 com a variável saldo
<br>
<b>OPERADORES LÓGICOS</b>
• São operadores utilizados em conjunto com os operadores de comparação para montar uma expressão lógica. Quando um operador de comparação é utilizado, o resultado retornado é booleano <i>true ou false</i>, dessa forma podemos combinar operadores de <i>comparação</i> com <i>lógicos</i>, por exemplo:
<br>
<b>
op_comparacao + op_logico + op_comparacao ... n ...
<br>
O operador <b>and</b> representa <i>junção</i>, por exemplo
<b>saldo >= saque and saque <= limite</b> #só funciona se ambas forem verdadeiras
<br>
O operador <o>or</o> representa <i>ou</i>, resulta em true se <i> pelo menos um for verdadeiro</i>
<b>
O operador <b>not</b> representa a negação, o inverso da condição, por exemplo
<br>
<b>saldo not saque</b> #nesse código fala que o valor de saldo não é o valor de saque
<br>
• É recomendado pelas <i>boas práticas</i> no Python utilizar <b>parenteses</b> para ter uma <i>melhor visualização</i>, mesmo que não altere na operação, por exemplo
<br>
<b>saldo >= saque and saque <= limite) or (conta_especial and saldo >= saque)
<br>
<b>OPERADORES DE IDENTIDADE</b>
<br>
• Eles são utilizados para <i>comparar</i> se os dois objetos testados ocupam a mesma posição na memória, por exemplo
<br>
<b>nome_curso = curso
<br>
curso is nome_curso</b> #resulta em true por terem sido definidos iguais
<br>
<b>curso is not nome_curso</b> #resulta em false, acima foram definidos como iguais
<b>OPERADORES DE ASSOCIAÇÃO</b>
• São operadores utilizados para verificar se um objeto está presente em uma sequéncia, por exemplo
<br>
<b>
curso = "Python"
<br>
frutas = ["laranja", "uva", "limão"]
<br>
saques = [1500, 100]
<br>
"Python" in curso </b> # Retorna true por estar na variável curso
<br>
<b>"maçã" in frutas</b> # Retorna false pois maçã não está no array frutas 
<b>200 in saques</b> # Retorna false pos 200 não está em saques, os valores de saques que estão são apenas 1500
<br>
A <b>estética</b>, <i>identar o código</i> é uma forma de manter o código fonte mais <b>legível</b> e <b>manutenível</b>. Mas em Python ela exerce um <i>segundo papel</i>, através da identação o <i>intepretador consegue determinar</i> onde um bloco de comando <i>inicia</i> e onde ele <i>termina</i>.
<br>
• <b>Bloco de comando</b> = As linguagens de programação costumam <i>utilizar caracteres e palavras</i> reservadas para terminar o <i>início</i> e <i>fim</i> do bloco. Em <b>Java</b> e <b>C</b> por exemplo, utilizamos chaves ({}), segue abaixo um exemplo em Java:
<br>
<code>
		void sacar(double valor){
		if(this.saldo>=valor){
		this.saldo = valor;
		} // fim do bloco if
	} fim do bloco método
</code>
• <b>Utilizando espaços</b> = Existe uma <i>convenção</i> em Python, que define as <b>Boas Práticas</b> para escrita de código na linguagem. Nesse documento é indicado utilizar 4 espaços em branco por <i>nível de identação</i>, segue abaixo um código em Python:
<br>
<code>
	def sacar (self, valor: float) -> None: # Início do bloco método
		if self.saldo >= valor: # Início do bloco if
			self.valor = valor
		# Fim do bloco if
	# Fim do bloco método
</code>
<br>
<b>IMPORTANTE:</b> CASO NÃO <b>IDENTAR NO PYTHON, </b> O BLOCO <b> NÃO VAI FUNCIONAR</b>
<b>def</b> é a <i>palavra reservada</i> do Python para definir uma <b>função</b>, exemplo:
<br>
<code>
	def <i>nome_da_funcao(argumentos)</i>:
		# Código
</code>
<br>
A palavra <b>"def"</b> é seguida pelo nome da função, seguido, por parenteses que contém zero ou mais argumentos (o primeiro sempre é o self) separados por <b>vírgula</b>.
<br>
A definição da função é terminada com <b>dois pontos</b> (o que indica o inicio dela após os quatro espaços) e o corpo da função é escrito em uma ou mais linhas, identadas para a direita.
<br>
