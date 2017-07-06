## Instalação do GDK {#instala-o-do-gdk}

O processo de instalação do GDK – Groovy Development Kit é semelhante ao do JDK – Java Development Kit. Através da página de [download](http://www.groovy-lang.org/download.html) é possível encontrar instalações para Windows e Linux/Mac OSX.

Para a instalação é necessário acessar o _command line_ do Groovy no _prompt_ de comando do sistema operacional e realizar os seguintes passos:

1.  Configure a variável de ambiente GROOVY_HOME apontando para o diretório onde o Groovy foi instalado;
2.  Adicione %GROOVY_HOME%\bin ao path do sistema operacional.

Para validar a instalação, no prompt de comando do sistema, execute a seguinte instrução:

# groovy -v

O resultado deve ser algo semelhante a este:

# Groovy Version: 2.4.4 JVM: 1.8.0_51 Vendor: Oracle Corporation OS: Windows 8.1