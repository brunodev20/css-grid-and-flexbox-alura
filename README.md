# Styling Guide

Toda a estilização que será usada no projeto dentro do figma. All styling that will be used in the project from Figma.

[Figma Project Link](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Font

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

## Colors

body: `#1D232A`

header: `#1D232A`

header - mobile: `#15191C`

sidebar menu: `#15191C`

card: `#2C343A`

font: `#FFFFFF`

alternate font: `#95999C`

links: `#0480DC`

button: `#0480DC`

shadows: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Icons

The icons are inside a font file called `icons.ttf`. To use them, first import the font inside the project using `@font-face` and then use the code below to show the icon.

```css
@font-face {
    font-family: 'icons';
    src: url(../font/icons.ttf);
}
```

> Beware the location of the `icons.ttf` file.

Shirts = `\e900`

Shopping cart = `\e901`

Home = `\e902`

Members = `\e903`

Menu = `\e904`

Coin = `\e905`

Notification = `\e906`

Location = `\e908`

Locations = `\e909`

Paintings = `\e90a`

Play = `\e90b`

Clock = `\e90c`

Down-arrow = `\e90d`

Videos = `\e90e`

Views = `\e90f`

## Spacing

Spacing inner button: `8px`

Spacing between button elements: `8px`

Spacing between elements: `16px/8px`

Body inner spacing: `16px`

Spacing between recent card title and its items: `24px`

## Sizes

Mobile device size: `360px`

Desktop device size: `1440px`

Main content maximum width: `1120px`

Desktop card maximum width: `256px`

Card minimum height: `320px`
