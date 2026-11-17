# Bazzite-Login-Lock-screen-background

Extensão do Gnome Shell 51 para habilitar uma imagem de fundo nas telas de login e bloqueio do Bazzite Linux.

O Bazzite é uma distribuição linux atômica/imutável, baseada no Fedora, dentro do escopo do projeto Universalblue. Sendo assim, a raíz do sistema não autoriza aos usuários a realizarem modificações nos arquivos de sistema. Por conta disso é que resolvi criar essa extensão, tendo em vista ser algo faltante no Bazzite. Espero que gostem e façam bom uso, pois foi feito com bastante carinho e foco.

<img width="704" height="1011" alt="Captura de tela de 2026-11-17 10-25-26" src="https://github.com/user-attachments/assets/5ed0221d-c57c-4116-8cb1-324236f19d93" />

Como instalar:

    Acesse seu diretório de downloads pelo terminal com o comando: cd /Downloads
    rode o comando: gnome-extensions install --force background-login-lock@bazzite.shell-extension.zip
    Saia da sessão e entre de novo. No Wayland o Shell só enxerga uma extensão nova assim.
    Rode gnome-extensions enable background-login-lock@bazzite.
    Abra as preferências com gnome-extensions prefs background-login-lock@bazzite, ou pelo app de Extensões.

Como usar:

    Tela de bloqueio: clique em “Escolher…” e a imagem vale na hora, então basta apertar Super+L para ver. Há um botão para voltar ao padrão e um ajuste de encaixe (preencher, ajustar, esticar ou centralizar). A opção “Manter esta imagem”, ligada por padrão, impede que as Configurações do GNOME sobrescrevam a imagem quando você trocar o papel de parede. O desfoque que aparece por cima da imagem é do próprio GNOME e a extensão não o altera.
    Tela de login: na primeira vez, clique em “Escolher…” e informe a senha de administrador uma única vez. Isso instala um pequeno suporte para o GDM. Depois disso, trocar a imagem não pede mais senha, e a nova imagem aparece na próxima vez que a tela de login for exibida (saindo da sessão ou reiniciando). Também existe o botão “Usar a do bloqueio”, que copia a mesma imagem para o login.

OBS.: Quem souber revisar os códigos da extensão e puder/quiser ajudar a ver se há algo estranho no código, será muito bem-vindo e de grande valia.
