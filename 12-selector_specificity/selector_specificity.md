# Selector Specificity

## Conflicts and the Cascade
* Example 1:
  * p { color: black; }
  * p { color: red } - This rule wins
* Example 2:
  * #main-content p { color: black } - This rule wins
  * p { color: red; }
  
  ## How Specific?
  * ID's 100 points
  * Classes 10 points
  * Elements 1 point