# dsc-polymer-carousel

Componente polymer para exibição de um carrossel de imagens com efeito paralax.

Comunmente utilizado no topo da página inicial de sites.

![demo](https://raw.githubusercontent.com/discovery-tecnologia/dsc-polymer-carousel/master/docs/img/carousel.jpg)

## Demo
```
git clone https://github.com/discovery-tecnologia/dsc-polymer-carousel.git
cd dsc-polymer-carousel
bower install
node install -g polymer-cli
polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-carousel/demo/

## Exemplo de uso

```html
<dsc-polymer-carousel interval="5">
  <section background="http://localhost:8080/components/dsc-polymer-carousel/demo/images/slide-2.jpg">
    <div class="content">
      <h1>Banner 1</h1>
      <p>Nam mattis porta mattis. Donec et neque scelerisque, pretium arcu sed, vehicula diam. Nam a arcu eu sapien porta<br>posuere id id arcu. Fusce rhoncus erat ut nisl pharetra.</p>
      <a href="#">View more</a>
    </div>
  </section>
  <section background="http://localhost:8080/components/dsc-polymer-carousel/demo/images/slide-2.jpg">
    <div class="content">
      <h1>Banner 2</h1>
      <p>In aliquam orci ligula, nec tempus metus laoreet eget.<br>Proin ornare nibh condimentum leo elementum, at hendrerit turpis ultrices.</p>
      <a href="#">View more</a>
    </div>
  </section>
</dsc-polymer-carousel>
```



## API