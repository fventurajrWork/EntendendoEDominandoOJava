# EntendendoEDominandoOJava
Exercita os projetos do livro Endentendo e Dominando o Java 3ed. - Editora Digerati

## Java Desktop API

Chamar o navegador, passando um endereço, via classe  Desktop

java.awt.Desktop desktop = java.awt.Desktop.getDesktop();
desktop.browse ( new Java.net.URI ( "http://www.udemy.com" ) );

public void edit( java.io.File file ) throws java.io.IOException
