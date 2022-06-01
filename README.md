# CubieBoard2

Tendo isso em vista, objetivo aqui nesse repositório disponibilizar um compilado de versões atualizadas de firmware para a CubieBoard2.



Kali: 

  Apesar do Kali Linux já ter suporte a dispositivos ARM, e até mesmo já ter um script de compilação próprio para a CubieBoard2, o mesmo n disponiliza o mesmo já compilado, alem de ser um processo complicado. Alem desses fatores, o atual script tem falhas a qual causam erros na hora da compilação, e impedem o dispositivo de iniciar.

Das versões já compiladas do kali disponiveis em http://old.kali.org/arm-images/ apenas obtive sucesso na execussão da versão 1.0.6 (http://old.kali.org/arm-images/kali-1.0.6/kali-linux-1.0.6-cubieboard2.img.xz), contudo a mesma apresenta um modulo dpkg antigo, não compativel com o novo padrão de emcapsulamento, e na prática impedindo a instalação de aplicativos do repositório global.
