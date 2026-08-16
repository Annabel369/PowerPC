# PowerPC

<img width="1517" height="688" alt="Gemini_Generated_Image_cjlivwcjlivwcjli" src="https://github.com/user-attachments/assets/c5fd6c41-b7b0-4745-8bde-9f85a59bc182" />

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
  OS 9 que montamos hoje!

  Dá até vontade de comprar um Mac G4 ou G3 só pra testar, não dá? Posso ajudar com mais alguma etapa?


