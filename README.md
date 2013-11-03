recipes
=======

Recipes for food that goes in your mouth and out the cloud


How to read the recipes
-----------------------

Recipes are written in my own flavor of Markdown I'm playing with. Steps double as ingredient lists and read in order. Ingredients begin with a plus `+`, processes begin with a dash `--` (I usually use a double dash for readbility), yields begin with an equals sign `=`. Substeps are denoted by increasing indention level. Each product becomes a heading `#`, and if a product has prerequisites, they are specified in parentheses `()`.

The goal is to have an extremely terse syntax that's also machine readable. For example, to get a shopping list, you just have to look for lines that begin with a plus sign (`grep +`).
