<img src="https://raw.githubusercontent.com/davidsonbpe/electron-nativefier/quick-d/icon.png" min-width="150px" max-width="150px" width="150px" align="right" alt="Coffee">

# Electron Nativefier


[Nativefier](#Nativefier)
----------
Você deseja criar um app nativo para a Web do WhatsApp (ou qualquer página da Web). (host em execução Node)

[Instalação](#Instalação)
----------

Para Executar este repositório, você precisará [Git](https://git-scm.com) e [Node.js](https://nodejs.org/en/download/) (que vem com [npm](http://npmjs.com)) instalado em seu computador e sua linha de comando:

Em seguida, instale o Nativefier globalmente com

```bash
npm install -g nativefier

```
[UsarComandos](#UsarComandos)
----------

Para criar um aplicativo de desktop nativo para medium.com, simplesmente...

```bash
nativefier "https://davidsonbpe.blogspot.com/"

```

```bash
nativefier "https://davidsonbpe.blogspot.com/" -p windows -a x64

```

Nativefier tentará determinar o nome do aplicativo e também muitas outras opções. Se desejar, essas opções podem ser substituídas. Por exemplo, para substituir o nome...

```bash
nativefier --name 'My App Davidsonbpe' 'https://davidsonbpe.blogspot.com/' -p windows -a x64

```

[Argumentos](#Argumentos)
----------

Argumento: p, Dado Escolhas: "darwin", "linux", "mac", "mas", "osx", "windows"

Argumento: a, Dado Escolhas: "ia32", "x64", "armv7l", "arm64"

----------

**[Link:](#link)** https://github.com/nativefier/nativefier

**VEJA ESTE VIDEO TUTORIAL** https://youtu.be/vA0sha-qiyI

