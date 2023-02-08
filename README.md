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
• TIPOS DE VALORES
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