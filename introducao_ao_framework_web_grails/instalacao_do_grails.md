## Instalação do Grails {#instala-o-do-grails}

O processo de instalação do Grails é bem simples, através da página de [download](https://grails.org/download.html) é possível encontrar o pacote de instalação para Windows e Linux/Mac OSX.

Para prosseguir com a instalação é necessário descompactar o arquivo de instalação do Grails e realizar os seguintes passos:

1.  Configure a variável de ambiente GRAILS_HOME apontando para o diretório onde o Grails foi descompactado;
2.  Adicione %GRAILS_HOME%\bin ao path do sistema operacional.

Para validar a instalação, no prompt de comando do sistema, execute a seguinte instrução:

# grails -v

O resultado deve ser algo semelhante a este:

|Grails Version: 3.0.4

|Groovy Version: 2.4.4

|JVM Version: 1.8.0_51