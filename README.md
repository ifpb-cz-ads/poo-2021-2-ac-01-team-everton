//Respota questão 1

/*A máquina virtual Java (JVM) é uma máquina imaginária que emula uma aplicação em uma máquina real. A JVM é responsável pelo gerenciamento dos aplicativos, à medida que são executados. Com isso, os programas escritos em Java podem funcionar em qualquer plataforma de hardware e software que possua uma versão da JVM, tornando assim essas aplicações independentes da plataforma onde funcionam.*/

===============================================================================================================
//Respota questão 2

/*JRE (Java Runtime Environment) - Ambiente de Execução do Java que fornece as bibliotecas padrões do Java para o JDK compilar o seu código e para a JVM executar o seu programa.
JDK O Java Development Kit é composto pelo JRE é um conjunto de ferramentas úteis ao desenvolvedor Java, ou seja, ele contém um compilador, um depurador e o próprio JRE para você executar os seus programas.*/

//Respota questão 4

Apagando o arquivo class ocasionou a falha total na execução do programa

Error: Could not find or load main class TerceiraQuestao
Caused by: java.lang.ClassNotFoundException: TerceiraQuestao
Command execution failed.

BUILD FAILURE

//Respota questão 5

o codigo apresentou falha na execução

com a mudança do main para start ocorreu o seguinte problema, uma falha no método principal.

Error: Main method not found in class TerceiraQuestao, please define the main method as:
   public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application
Command execution failed.

//Respota questão 7

 /*não executa devido a liguagem ter um diferencial entre maiúsculas de minúsculas no descrever do codigo,
aparecera ou seginte erro no copilador:
"Erro: método principal não encontrado no arquivo.*//

//Respota questão 8

//* erro pois a regra do Java é que você só pode ter uma única classe pública por arquivo, e o nome dessa classe deve corresponder ao nome do arquivo.