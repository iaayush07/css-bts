# 3 type of css 

(1) Author css  
(2) Browser css
(3) User css

# 3 important main factor in css

=> Importance : to override any conflicting properties that are applied to the same element.
=> Specificity : which CSS rules should be applied to an element when multiple CSS rules target the same element (Inline,ID,Class,Element)
=> Source order : last declaration code will override other declaration and will be applied

# How css values are processed?

(1) declared value : author declaration (140px, 66%)
(2) cascade value : after cascading (66%)
(3) Specified value : defaulting, if there is no cascading value(inheritance concept) (66%)
(4) Computed value : converting relative value to absolute (66%)
(5) Used value : final conclusion based on layout (184.8px)
(6) Actual value : actual value (185px)

# Render Tree

Tree structure that cotains only elements and style that will be despalyed on the screen.

# vissual formality model

algorithm that calculates the boxes(box-model) and determines the layout of these boxes, for each element in the render tree
