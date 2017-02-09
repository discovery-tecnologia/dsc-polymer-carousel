# &#60;dsc-polymer-carousel&#62;

[![Build Status](https://travis-ci.org/discovery-tecnologia/dsc-polymer-carousel.svg?branch=master)](http://travis-ci.org/#!/discovery-tecnologia/dsc-polymer-carousel)
![Bower version](https://img.shields.io/bower/v/dsc-polymer-carousel.svg)
![](https://img.shields.io/pypi/l/Django.svg)

A slideshow polymer component for cycling through elements, like a carousel. Similar to the carousel component of the bootstrap.

Commonly used at the top of the homepage of sites.

![demo](https://raw.githubusercontent.com/discovery-tecnologia/dsc-polymer-carousel/master/docs/img/carousel.jpg)

Differential:

 * Easy to use
 * Optional parallax scroll effect
 * Custom content
 * Modern style
 * Swipe suport
 * Customizable style

## Demo

```
$ git clone https://github.com/discovery-tecnologia/dsc-polymer-carousel.git
$ cd dsc-polymer-carousel
$ npm install
$ node install -g polymer-cli
$ polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-carousel/demo/

## Usage

Install with:

```
$ bower i dsc-polymer-carousel --save
```

Example usage:

```html
<dsc-polymer-carousel interval="5" parallax>
  <section background="http://localhost:8080/components/dsc-polymer-carousel/demo/images/slide-2.jpg">
    <h1>Banner 1</h1>
    <p>Nam mattis porta mattis. Donec et neque scelerisque, pretium arcu sed, vehicula diam. Nam a arcu eu sapien porta<br>posuere id id arcu. Fusce rhoncus erat ut nisl pharetra.</p>
    <a href="#">View more</a>
  </section>
  <section background="http://localhost:8080/components/dsc-polymer-carousel/demo/images/slide-2.jpg">
    <h1>Banner 2</h1>
    <p>In aliquam orci ligula, nec tempus metus laoreet eget.<br>Proin ornare nibh condimentum leo elementum, at hendrerit turpis ultrices.</p>
    <a href="#">View more</a>
  </section>
</dsc-polymer-carousel>
```

## API

| Property       | Description                    | Default       |
|:---------------|--------------------------------|---------------|
| interval       | Time in seconds for transition | 5             |
| parallax       | Active parallax scroll effect  | false         |

Content should be section tags. The optional "background" attribute of the section defines the background image.

## Styling

| Custom property |	Description                                        | Default |
|:----------------|----------------------------------------------------|---------|
| --carousel-height               | Carousel height                    | 600px   |
| --carousel-control              | Control arrows                     | {}      |
| --carousel-control-left         | Left control arrow                 | {}      |
| --carousel-control-right        | Right control arrow                | {}      |
| --carousel-indicators           | Bottom indicator container style   | {}      |
| --carousel-indicators-li        | Bottom indicator item style        | {}      |
| --carousel-indicators-li-active | Bottom indicator active item style | {}      |

The sections should be stylized in the component where they were created.

## Test

Check sintax and execute selenium tests.

```
$ npm test
```
