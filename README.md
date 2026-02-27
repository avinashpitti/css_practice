# css_practice
div p selects all descendants, div > p selects only direct child
div p and div > p has the same specificity,when same specificity last rule wins.
nth-child(2) 2nd child of parent(not 2nd <p>, careful!)
p:nth-child(2) {
  color: red;
}


p:nth-of-type(2) {
  color: green;
}
selects : 2nd <p> specifically



