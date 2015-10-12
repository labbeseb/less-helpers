# less-helpers
**Some mixins less**

## clearfix :
*Classic clearfix for clear floats elements*

## hyphenText :
*Cuting the text and adds "..." after this if it's longer than its container*

## createTriangle :
*Created a triangle according to its orientation and size*
* @or : determines the orientation of triangle
    - top
    - bottom
    - left
    - right
* @w : set width
* @h : set height
* @color : ... ;)

## absCenter :
*Centering item by translate CSS propriety*

**Think about putting the parent in relative position and item affected in absolute position**
* @or : defines centering orientation
    - vertical
    - horizontal
    - both

## absCenterCompat :
*Fix the absCenter no-compatibility*
* @or : same than absCenter
* @top : if @or is 'vertical' or 'both', set negative margin-top
* @left : if @or is 'horizontal' or 'both', set negative margin-left

**set 0 to @top if @or is 'horizontal'**

**set 0 to @left if @or is 'vertical'**

## loopByOneAddBefore :
*A loop that add a pseudo-element before to the element @n at the @i*
* @i must be greater than @n
