## Pesquisa sobre Flutter
Pesquisa realizada por Fernanda Bonfim Santos, sobre Flutter e seus beneficios no desenvolvimento de aplicações mobile nativas.

# Flutter: 
Flutter é um framework de codigo aberto (open-source) desenvolvido pela Google para criação de app's moveis.
O Flutter foi desenvolvido com o intuito da reutilização de código fonte. A principal vantagem do flutter é você poder escrever o código uma unica vez e compilar em varias plataformas diferentes, como: android, ios e web. O flutter utiliza a linguagem de programação Dart (também desenvolvida pela google).
O Flutter é conhecido pela capacidade de conseguir rodar o mesmo aplicativo em varias fontes diferentes.
Você não tem trabalho de adaptação comparado ao React Native.
Ele também possui o hot reload, uma forma de conseguir ver oque esta ocorrendo com seu aplicativo em tempo real sem ter que rebuildar o codigo ou abrir um novo app.
 
# Dart:
O Dart é uma linguagem de programação orientada a objetos de multi-paradigmas, criada pela Google.
Dart Native é utilizado para desenvolvimento de aplicações moveis e inclui a maquina virtual do Dart com compilação utilizando o JIT (Just in Time) e o AOT (ahead-of-time) para produção de código de máquina. O Dart Native compila o código para Dart em forma nativa, seja ele ARM ou em X64.
Dart Web é utilizado para desenvolvimento web, ele possui o dart2js, que converte o código em Dart para javascript que é interpratador nos navegadores web.

# Flutter vs React Native
O React Native tem uma curva de aprendizado bem menor comparado ao Flutter. É um framework de codio aberto em javascript, como o Flutter. Porém como é em javascript e hoje existe uma grande gama de desenvolvedores React.js, a migração de um para outro é bem menor, comparada ao Flutter que é desenvolvido em Dart. 
Ambos tem otimo desempenho em desenvolvido de aplicações nativas.
Além do Google utilizar o Flutter em seus aplicativos outras grandes empresas também fazem o mesmo, como o Alibaba e recentemente a Nubank revelou que irá migrar seu aplicativo em React Native para Flutter.

# Ambiente de Desenvolvimento

1° Instale o VSCode ou algum editor de código fonte de sua preferência, link: https://code.visualstudio.com
Ele servirá para escrevermos, desenvolvermos o projeto e os codigos com o Flutter.

2° Instale o Android Studio, o Flutter utiliza CLI para desenvolvimento, então é precendivel o uso do android studio e sdk.
Link: https://developer.android.com/studio

3° Instale e configure o flutter em sua máquina. A instalação do flutter é bem simples. 
- Instale o pacote em zip (caso de windows)
- Descompate o pacote na paste da sua maquina, ex: OS (C:)
- Rode o arquivo dart.bat em \flutter\bin
- Configure nas variaveis de ambiente o flutter inserindo seu path de origem na sua máquina.
- Rode flutter --version para verificar se a instalação funcionou.
Link: https://docs.flutter.dev/get-started/install/windows

# Command Lines (Criando projeto)
- flutter create nome_projeto (essa command line cria um projeto novo)
- flutter run (roda o projeto)