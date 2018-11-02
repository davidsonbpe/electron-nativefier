

# electron-packager API



## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/davidsonbpe/electron-quick-d-master.git
# Go into the repository
cd electron-quick-d-master
# Install dependencies
npm install
# Run the app
npm start
```



**[Exemplo curto:](#Exemplo%20curto:)**


electron-packager .\pasta-arquivos-html-css-js \ nome-do-seu-app --platform=win32 --arch=ia32 --version=1.4.8

**[arch](#arch)**

String (padrão: o arco do computador host em execução Node)

**Valores permitidos:**  ia32, x64, armv7l, all


**[platform](#platform)**

String (padrão: o arco do computador host em execução Node)

**Valores permitidos:** linux, win32, darwin, mas, all

**[Version](#Version)**

String (padrão: o arco do computador host em execução Node)
**Valores:** No Electron Releases http://electron.atom.io/releases/

[**Link:**](#Link)**https://github.com/electron-userland/electron-packager/blob/master/docs/api.md

[Nativefier](#Nativefier)
----------
Você deseja criar um app nativo para a Web do WhatsApp (ou qualquer página da Web). (host em execução Node)

**[Instalação](#Instala%C3%A7%C3%A3o):**
npm install nativefier -g

nativefier --width "350" --height "650" --flash --name "APP-NAME" "http://dominio.com"

**[Link:](#link)**https://github.com/jiahaog/nativefier/blob/development/docs/api.md

**[Link:](#link)** https://github.com/jiahaog/nativefier

**VEJA ESTE VIDEO TUTORIAL** https://youtu.be/vA0sha-qiyI

