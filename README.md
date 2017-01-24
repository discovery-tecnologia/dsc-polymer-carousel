# dsc-polymer-carousel

A slideshow polymer component for cycling through elements, like a carousel. Similar to the carousel component of the bootstrap.

Commonly used at the top of the homepage of sites.

![demo](https://raw.githubusercontent.com/discovery-tecnologia/dsc-polymer-carousel/master/docs/img/carousel.jpg)

Differential:

 * Easy to use
 * Optional parallax scroll effect
 * Custom content
 * Modern style
 * Customizable style

## Demo

```
git clone https://github.com/discovery-tecnologia/dsc-polymer-carousel.git
cd dsc-polymer-carousel
bower install
node install -g polymer-cli
polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-carousel/demo/

## Usage

```html
<dsc-polymer-carousel interval="5" parallax>
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

| Property       | Description                    | Default       |
|:---------------|--------------------------------|---------------|
| interval       | Time in seconds for transition | 5             |
| parallax       | Active parallax scroll effect  | false         |

## Styling

| Custom property |	Description                                        | Default |
|:----------------|----------------------------------------------------|---------|
| --carousel-control              | Control arrows                     | {}      |
| --carousel-control-left         | Left control arrow                 | {}      |
| --carousel-control-right        | Right control arrow                | {}      |
| --carousel-indicators           | Bottom indicator container style   | {}      |
| --carousel-indicators-li        | Bottom indicator item style        | {}      |
| --carousel-indicators-li-active | Bottom indicator active item style | {}      |

The sections should be stylized in the component where they were created.

## Todo

 * test
 * internationalization
 * indicators action
 * background colors
