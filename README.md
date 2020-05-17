# Notes
some notes for myself

#Waffle package usage with FA font
#download FA ttf 4.7 verision and install in Fonts, then use extrafont in R to import fonts

library(waffle)
library(extrafont)

font_import()
parts =c("Boys"=20,"Girls"=20)

waffle(
  parts, colors = c("#0000FF","#FFC0CB"),
  use_glyph = "car", size = 8, rows = 4)
