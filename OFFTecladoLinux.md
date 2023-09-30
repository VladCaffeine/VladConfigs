Para desabilitar o teclado interno no Ubuntu, é preciso incluir o parâmetro de Kernel "i8042.nokbd" para que a inicialização não utilize o teclado embutido.

"i8042.nokbd     [HW] Não cheque ou crie uma porta de teclado"

1- Abra um terminal a partir da tela de busca de programas ou com o atalho CONTRL + ALT + T

2- Digite no terminal o comando abaixo em modo administrador, vai requisitar a sua senha:

sudo gedit /etc/default/grub

3- Encontre a seguinte linha:

GRUB_CMDLINE_LINUX_DEFAULT="quiet splash"

4- Adicione o parâmetro "i8042.nokbd", na linha encontrada conforme abaixo:

GRUB_CMDLINE_LINUX_DEFAULT="quiet splash i8042.nokbd"

5- Atualiza o programa grub, com o seguinte comando:

sudo update-grub     

6- Reinicia o laptop.

FIM
