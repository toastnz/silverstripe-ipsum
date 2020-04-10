<p align="center">
  <img style="width:100%;height:auto; max-width:1085px" src="http://pinc.nz/git/silverstripeipsum/silverstripeipsum.png">
</p>

# Silverstripe Ipsum Generator

Simple Module to add ipsum generators to your templates.

All credit here : https://github.com/joshtronic/php-loremipsum

## Installation

Get the goodness just like so:

```
 composer require toastnz/silverstripe-ipsum
```

Then use like this:

```
    Single word:   $ipsum('word') 
    Ten words:     $ipsum('words',10)
    30 paragraphs: $ipsum('paragraphs',30).RAW
    One image URL: $ipsum('image', 300,150)
    One image:     $ipsum('image', 300,150,1).RAW
```

Step 4: Profit
