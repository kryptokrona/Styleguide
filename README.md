<a href="https://chat.kryptokrona.se"><img src="https://img.shields.io/discord/562673808582901793?label=Discord&logo=Discord&logoColor=white&style=plastic"></a>
<a href="https://twitter.com/kryptokrona"><img src="https://img.shields.io/twitter/follow/kryptokrona?style=social"></a>

# Styleguide

Styleguide for Kryptokrona

# Logo

#### Black symbol

![SymbolBlack](https://raw.githubusercontent.com/kryptokrona/Styleguide/66d56e5945d9f7a758d8f899f4e00bff5e97fec1/Logo/Black%20-%20logo.svg)

#### White symbol

![SymbolWhite](https://raw.githubusercontent.com/kryptokrona/Styleguide/66d56e5945d9f7a758d8f899f4e00bff5e97fec1/Logo/White%20-%20logo.svg)

#### Black with text

![LogoBlack](https://user-images.githubusercontent.com/36674091/104137639-4dc6b500-5396-11eb-9c45-03062e0f65f7.png)

#### White with text

![LogoWhite](https://user-images.githubusercontent.com/36674091/104137640-4e5f4b80-5396-11eb-9cda-5554620d2a47.png)


# Fonts

Title
[Montserrat Bold](https://github.com/kryptokrona/Styleguide/raw/main/Fonts/Montserrat-Bold.ttf) 

#### 


# Color

#### Dark theme

![Darktheme](https://user-images.githubusercontent.com/36674091/111849650-03b5fe80-8906-11eb-8f00-5355fb66efd3.png) <br>
#171416, #272527, #2E2C2E, #464346

# Gradient Background

This is the RGB gradient we use to make things pop! <br>

Add `class="rgb"` to a html element or if you already have a class then `class="example rgb"`

```css
@keyframes rgb {
  0%, 100% {
    background: #5f86f2;
  }
  12.5% {
    background: #a65ff2;
  }
  25% {
    background: #f25fd0;
  }
  37.5% {
    background: #f25f61;
  }
  50% {
    background: #f2cb5f;
  }
  62.5% {
    background: #abf25f;
  }
  75% {
    background: #5ff281;
  }
  87.5% {
    background: #5ff2f0;
  }
}
```
```css
.rgb {

  background: #5f86f2;
  -webkit-animation: rgb 30s ease infinite;
  -moz-animation: rgb 30s ease infinite;
  animation: rgb 30s ease infinite;
} 
```
# Gradient Text

Or use this to make a text pop! <br>

Add `class="rgbText"` to a html element or if you already have a class then `class="example rgbText"`

```css
@keyframes rgbText {
  0%, 100% {
    color: #5f86f2;
  }
  12.5% {
    color: #a65ff2;
  }
  25% {
    color: #f25fd0;
  }
  37.5% {
    color: #f25f61;
  }
  50% {
    color: #f2cb5f;
  }
  62.5% {
    color: #abf25f;
  }
  75% {
    color: #5ff281;
  }
  87.5% {
    color: #5ff2f0;
  }
}
```

```css
.rgbText {

  color: #5f86f2;
  -webkit-animation: rgbText 10s ease infinite;
  -moz-animation: rgbText 10s ease infinite;
  animation: rgbText 10s ease infinite;
} 
```