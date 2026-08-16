# PowerPC

<img width="1517" height="688" alt="Gemini_Generated_Image_cjlivwcjlivwcjli" src="https://github.com/user-attachments/assets/c5fd6c41-b7b0-4745-8bde-9f85a59bc182" />

https://drive.google.com/file/d/1BuEBzf2uvRau-ljMLVMNyh2rkMTebsRV/view?usp=sharing

  O seu novo arquivo bruto está pronto e salvo aqui:
  /home/astral/Downloads/macos9_hd.img

  Esse arquivo tem exatos 2GB, bit a bit iguais a um disco rígido físico particionado no formato Apple (HFS+).

  ### Como gravar isso no seu hardware retrô:

  No dia em que você for ligar o seu Mac antigo, você só vai precisar:

  1. Plugar o Cartão SD/CF ou o HD do Mac no seu computador Linux.
  2. Descobrir qual a letra da unidade dele (por exemplo /dev/sdX).
  3. Gravar a imagem usando um programa gráfico como o BalenaEtcher (é a forma mais segura) ou usar o comando raiz do Linux no terminal:
  sudo dd if=/home/astral/Downloads/macos9_hd.img of=/dev/sdX bs=4M status=progress

  Se o Mac de destino for um modelo PowerPC ou até mesmo um dos últimos modelos 68k compatíveis, você plugará a placa BlueSCSI/SD nele e ele dará um sorriso na tela (o clássico "Happy Mac") carregando o Mac


    ### 1. Metrowerks CodeWarrior (A IDE "Rainha" dos anos 90)

  Se você jogou Starcraft, Quake ou usou o Photoshop no Mac OS 9, as chances são quase 100% de que o código foi escrito no CodeWarrior.
  • Linguagens: C e C++ (principalmente).
  • Por que era tão incrível? Quando a Apple mudou os processadores dos antigos Motorola 68k para os novos PowerPC (em 1994), o CodeWarrior salvou a vida dos programadores. A IDE deles era super rápida e
  conseguia compilar o mesmo código para as duas arquiteturas facilmente. Ele tinha uma interface gráfica excelente, com debuggers poderosos, desbancando quase todos os concorrentes.

  ### 2. Macintosh Programmer's Workshop (MPW)

  Esta era a IDE "oficial" da própria Apple, focada nos desenvolvedores hardcore.

  • Linguagens: C, C++, Object Pascal e Assembly.
  • Por que era diferente? O MPW não era uma interface bonitinha com botões. Era uma mistura bizarra e superpoderosa de um editor de texto com um terminal de comandos do Unix. Você escrevia scripts e comandos
  de compilação no meio do próprio texto do código e mandava rodar. Era difícil de aprender, mas a Apple fornecia suas bibliotecas de sistema (o Macintosh Toolbox) em primeira mão por ele.

  ### 3. THINK C e THINK Pascal (da Symantec)

  Muito populares no final dos anos 80 e início dos 90 (antes da chegada dos PowerPC).

  • Linguagens: C e Pascal.
  • Por que eram amadas? A linguagem Pascal foi a linguagem oficial da Apple no início do Macintosh (o próprio sistema operacional original foi feito em Pascal e Assembly). O THINK Pascal era famoso por
  compilar o código incrivelmente rápido e ajudar muito estudantes e desenvolvedores iniciantes, enquanto o THINK C era para a galera mais avançada. A Symantec perdeu mercado para o CodeWarrior quando demorou
  para dar suporte aos processadores PowerPC.

  ### 4. RealBASIC (O "Visual Basic" do Mac)

  Se você quisesse criar um aplicativo com janelas, botões e menus em poucas horas sem saber C++, esta era a escolha.
  • Linguagem: BASIC (Orientado a Objetos).
  • Como funcionava: Era uma IDE visual. Você arrastava os botões para a tela do Mac com o mouse e escrevia códigos simples por trás deles. Apesar de fácil, ele compilava aplicativos nativos reais, não
  precisava de interpretadores pesados rodando por trás.

    1. Abra esse novo disco. Lá dentro estará o arquivo BattleChess1.cpt.bin.
  2. Importante: Não tente abrir ele direto de lá. Como ele está em um "Pen Drive", as permissões do Mac OS podem ficar estranhas. Arraste o arquivo para a sua Área de Trabalho (Desktop) ou para o seu HD
  principal para copiá-lo para dentro do Mac OS de verdade.
  3. Depois de copiar, dê um duplo clique nele! O programa StuffIt Expander (que já vem no Mac OS 9 Lives) deve abrir automaticamente e descompactar o jogo na sua tela!




