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
Na <b>concatenação</b>, o uso do <b>f</b> concatena textos com variáveis, ela mais ou menos "diz" que vai ser inserido variáveis dentro dessa string criada
<br>
