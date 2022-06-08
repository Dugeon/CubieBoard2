# CubieBoard2

Tendo isso em vista, objetivo aqui nesse repositório disponibilizar um compilado de versões atualizadas de firmware para a CubieBoard2.

#Instrução

1 - Baixar todos os arquivos da pasta Images.
2 - Descopactar
3 - Gravar o arquivo .img no SD que será utilziado, para isso caso utilize o windows aconselho usar o Win32DiskImager (link a baixo):
https://sourceforge.net/projects/win32diskimager/
4 - Inserir o SD na CubieBoard2 e conectar o power.
5 - Para a primeira incialização você precisará de um teclado usb e uma tela HDMI para configurar as contas de usuário, após isso será possivel acessar o via SSH desde que conectado ao uma rede.






# Rev.2

Após muitas pesquisas indentifiquei que o armbian tem versões que funcionam corretamente na CubieBoard2, pela dificuldade de encontrar material apropriado na internet irei manter uma copia do firmware mais atualizado até o momento aqui para fim de arquivamento em caso de descontinuação do projeto https://armbian.tnahosting.net/archive/cubieboard2/archive/ , todos os direitos sobre os arquivo são deles, e estou apenas fornecendo um espelho de backup.

Buscarei disponibilizar uma imagem com algumas funcionalidades que acho importantes já pre-instaladas de forma a facilitar o acesso aqueles que tenham dificuldades.


# Rev.1

  Apesar do Kali Linux já ter suporte a dispositivos ARM, e até mesmo já ter um script de compilação próprio para a CubieBoard2, o mesmo n disponiliza o mesmo já compilado, alem de ser um processo complicado. Alem desses fatores, o atual script tem falhas a qual causam erros na hora da compilação, e impedem o dispositivo de iniciar.

Das versões já compiladas do kali disponiveis em http://old.kali.org/arm-images/ apenas obtive sucesso na execussão da versão 1.0.6 (http://old.kali.org/arm-images/kali-1.0.6/kali-linux-1.0.6-cubieboard2.img.xz), contudo a mesma apresenta um modulo dpkg antigo, não compativel com o novo padrão de emcapsulamento, e na prática impedindo a instalação de aplicativos do repositório global.
