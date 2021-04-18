# color
### Color can really bring your pages to life.
#### In this chapter we will look at:
● How to specify colors, as there are three common ways in which you can indicate your choice of colors (plus extra ways made available in CSS3)
● Color terminology, as there are some terms that are very helpful to understand when it comes to picking colors
● Contrast, and ensuring that your text is readable
● Background colors for behind either your entire page or parts of a page What you will learn about colors in this chapter will then be used in subsequent chapters when it comes to looking at colors of text and boxes in CSS.
## Foreground Color
- The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
#### hex Codes
- These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
## Color names
- There are 147 predefined color names that are recognized by browsers. For example: DarkCyan
## baCkground Color
#### CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
#### You can specify your choice ofbackground color in the samethree ways you can specifyforeground colors: RGB values,hex codes, and color names(covered on the next page).
#### If you do not specify abackground color, then thebackground is transparent.By default, most browserwindows have a whitebackground, but browser userscan set a background color fortheir windows, so if you want
##### to be sure that the backgroundis white you can use thebackground-color property onthe <body> element.We have also used the paddingproperty to separate the textfrom the edges of the boxes.This makes it easier to read andyou will learn more about thisproperty on page 313.
### RGB Values
###### Values for red, green, and blueare expressed as numbers between 0 and 255.
#### Hex Codes
###### Hex values represent valuesfor red, green, and blue in hexadecimal code.
#### ColoR Names
###### Colors are represented bypredefined names. However,they are very limited in number.MediumAquaMarineThere are 147 color namessupported by browsers (thiscolor is MediumAquaMarine).Most consider this to be alimited color palette, and it ishard to remember the name foreach of the colors so (apart fromwhite and black) they are notcommonly used.
### Hue
##### Hue is near to the colloquial idea of color. Technically speakinghowever, a color cansaturation and brightness as also havewell as hue.
### satuRatioN
##### Saturation refers to the amounof gray in a color. At maximumsaturation, there would be nogray in the color. At minimumsaturation, the color would bemostly gray. ContrastWhen picking foreground and background
- colors, it is important to ensure that there is enough contrast for the text to be legible.Text is easier to read when there is higher contrast between background anIf you want people to read a lotd foregroundcolors.then too much contrast can
### make it harder to read, too.
- low
- Contrast
- high
- Contrast
- medium
- Contrast
##### If text is reversed out (a light color on a dark background), youcan increase the height between lines and the weight of the fontto make it easier to read.For long spans of text, reducingreadability.the contrast a little bit improves
### You can reduce contrast byusing dark gray text on a whitebackground or an off-white texton a dark background.Text is harder to read whenthere is low contrast betweenbackground and foregroundcolorsA lack of contrast is particularlya problem for those with
### visual impairments and colorblindness.It also affects those with poormonitors and sunlight on theirscreens (which is increasinglycommon as people use handheld