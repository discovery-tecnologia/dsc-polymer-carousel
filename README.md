# dsc-polymer-carousel

Componente polymer para exibição de um carrossel de imagens com efeito paralax.

Comunmente utilizado no topo da página inicial de sites

## Exemplo de uso
```html
<link rel="import" href="bower_components/polymer/polymer.html">
<link rel="import" href="dsc_components/dsc-polymer-carousel/dsc-polymer-carousel.html">

<dom-module id="example-component">

  <template>

    <style>
      dsc-polymer-carousel h1 {
        color: red;
      }
    </style>

    <main>
      <dsc-polymer-carousel>
        <section background="http://localhost:8080/images/banner1.jpg">
          <div class="content">
            <h1>Banner 1</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            <a href="#">Ver mais</a>
          </div>
        </section>
        <section background="http://localhost:8080/images/banner2.jpg">
          <div class="content">
            <h1>Banner 2</h1>
            <a href="#">Ver mais</a>
          </div>
        </section>
        <section background="http://localhost:8080/images/banner3.jpg">
          <div class="content">
            <h1>Banner 3</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            <a href="#">Ver mais</a>
          </div>
        </section>
      </dsc-polymer-carousel>
    </main>

  </template>

  <script>
    Polymer({
      is: 'example-component'
    });
  </script>

</dom-module>

```

## API