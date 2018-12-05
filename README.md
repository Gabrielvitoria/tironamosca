<div align="center">
  <a href="#" target="_blank">
  <img src="https://user-images.githubusercontent.com/5305599/49061716-da649680-f254-11e8-9a89-d95a7407ec6a.png" alt="NES.css: NES-style  CSS framework" style="max-width:100%;" width="600" height="315"></a>
 
</div>

Tiro na Mosca utiliza: Utiliza NES.css que é uma estrutura CSS estilo **NES-style(8bit-like)**
NES.css é uma estrutura CSS estilo Famicom **(8bit-like)** .

## Install

### CDN

```html
<!-- minify -->
<link href="https://unpkg.com/nes.css@0.0.2/css/nes.min.css" rel="stylesheet" />
<!-- latest -->
<link href="https://unpkg.com/nes.css/css/nes.min.css" rel="stylesheet" />
```

OR

```html
<!-- non-minified -->
<link href="https://unpkg.com/nes.css@0.0.2/css/nes.css" rel="stylesheet" />
<!-- latest -->
<link href="https://unpkg.com/nes.css/css/nes.css" rel="stylesheet" />
```

### npm

TODO: Escreva como usar no npm

## Usage

NES.css fornece apenas estilos de componentes. Por favor, defina o layout como você gosta.
Por padrão, Press Start 2Peu uso fontes. Por favor, leia e use a fonte separadamente quando for usada diferente do inglês (japonês etc.).
TODO: Escreva os detalhes


## CSS Only

NES.css consiste apenas em CSS. JavaScript não é necessário.

## Browser Support

Nós suportamos a versão mais recente dos seguintes navegadores.

* Chrome
* Firefox
* Safári

Não verificado

* IE / Edge


## Development

### Commands
```sh
git clone 
cd NES.css

npm i

npm run watch
npm run build
```

Com o gancho pre-commit, o Lint → format → build é executado automaticamente no tempo de consolidação csse o arquivo é enviado para o diretório. TODO: Eu quero mudar a compilação a ser feita com CI

### Directories
```
.
|- index.html: Demo page
|- style.css: Demo page style
|- css: Distribution files
|-　scss: Source
    |- base
    |   |- reboot.scss: **Don't change!** (Bootstrap Reboot)
    |   |- generic.scss: Generic style and overwrite reboot.css
    |   |- variables.scss: Common variables
    |- elements
    |- form
    |- icons: For 16x16 icon
    |- pixel-arts: For icon other than 16x16 icon.
    |- utilities
```

## Copyright and license

Código e documentação copyright 2018 [B.C.Rikko](https://github.com/BcRikko) Código liberado sob a licença MIT Docs liberados sob Creative Commons.

