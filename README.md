# BrailleÉcran web site

Web site estático para divulgação do projeto Braille Écran.

## Começando

Ao seguir estas instruções você poderá rodar e testar o site localmente. Para instruções de como colocar o site online veja [Implantando](#Implantando).

### Pré requisitos

Para rodar este projeto você deve ter instalado o Hugo 0.43 extended ou superior. [A última versão pode ser baixada no Github do projeto.](https://github.com/gohugoio/hugo/releases/latest)

Os comandos abaixo são um exemplo de como a instalação pode ser feita no Debian/Ubuntu. 
```bash
$ wget https://github.com/gohugoio/hugo/releases/download/v0.43/hugo_extended_0.43_Linux_64bit.deb
$ sudo dpkg -i hugo_extended_0.43_Linux_64bit.deb
$ sudo apt install -f
```

### Executando localmente

Para executar o site localmente, basta rodar o comando abaixo.

```
$ hugo -D serve
```
Você pode visitar o site no endereço [localhost:1313](http://localhost:1313). Atualizações nos arquivos serão automaticamente refletidas no site.

## Implantando

Add additional notes about how to deploy this on a live system

## Construido com

* [Hugo](https://gohugo.io/) - Gerador de site estático
* [Now UI kit](https://www.creative-tim.com/product/now-ui-kit) - Tema Bootstrap 4
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Autores

* **[Leonardo M Fleury](@leuzera)** - *Trabalho Inicial*

## Licensa

Este projeto é licenciado sobre a Licensa MIT - veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.