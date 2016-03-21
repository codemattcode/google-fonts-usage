# google-fonts-usage

// merriweather Sans (thin and neat for paragraph text)
@import url(http://fonts.googleapis.com/css?family=Merriweather+Sans:300,300italic,400italic,700,700italic,800,800italic)

// Open Sans (modern and clean best on paragraphs)
@import url(http://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,80italic,400,300,600,700,800)

// Lato (pencil thin headlines and CLEAN AND READABLE SANS FOR PARAGRAPHS)(ANOREXIC HEADLINES IN $LIGHT)
@import url(http://fonts.googleapis.com/css?family=Lato:100,300,400,700,900,100italic,300italic,400italic,700italic,900italic)

// Raleway (has a 'v cross' 'W' better for paragraph text)(DELICATE IN $LIGHT)
@import url(http://fonts.googleapis.com/css?family=Raleway:100,300,900)

// specific attributes and not general purpose or goto fonts
Dosis (looks quirky spacey rounded headlines only - curly lower case 'g')
@import url(http://fonts.googleapis.com/css?family=Dosis:400,500,800)

Oswald (tall and squashed better for paragraph text)
@import url(http://fonts.googleapis.com/css?family=Oswald:300)

// Inconsolata (fidgety on headlines decorative code-ish for paragraphs)
@import url(http://fonts.googleapis.com/css?family=Inconsolata:400,700)

// Montserrat (wide and circular presents as decorative paragraph text)
@import url(http://fonts.googleapis.com/css?family=Montserrat:400,700)

mixins for unused fonts above

/* 100 300 400 700 900 + i */
=lato($fontSize, $weight, $heightValue, $color)
  font-family: "Lato", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
/* 100 300 700 900 */
=raleway($fontSize, $weight, $heightValue, $color)
  font-family: "Raleway", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
/* 300 400 700 */
=oswald($fontSize, $weight, $heightValue, $color)
  font-family: "Oswald", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
/* 400 500 800 */
=dosis($fontSize, $weight, $heightValue, $color)
  font-family: "Dosis", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
/* 400 700 */
=montserrat($fontSize, $weight, $heightValue, $color)
  font-family: "Montserrat", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
/* 300 400 600 700 800 + i */
=opensans($fontSize, $weight, $heightValue, $color)
  font-family: "Open Sans", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
/* 300 400 700 800 +i */
=merriweatherSans($fontSize, $weight, $heightValue, $color)
  font-family: "Merriweather Sans", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
  /* 400 700 */
=inconsolata($fontSize, $weight, $heightValue, $color)
  font-family: "Inconsolata", sans-serif
  font-size: $fontSize + px
  font-size: (1.5 * $fontSize) + rem
  font-weight: $weight
  line-height: $heightValue + px
  line-height: (1.5 * $heightValue) + rem
  color: $color
