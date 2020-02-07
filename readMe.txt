1. Just like the flexbox we can make the items in the
wrapper display:grid; but unlike flex you should define columns or
rows in wrapper to change the view of page

2. we can define the columns of the page by using
grid-template-columns: 30% 20% 50%;

3. by default the first element go to the first column and
the second go to the second column and so on...

4. we can use fraction to give the size for the columns:
gird-template-columns: 1fr 1fr 2fr;

5. we can also use repeat function to say that we want the 
same column over and over again:
grid-template-columns: repeat(3, 1fr);

6. In this situation the height of the rows controlled by the 
content in each column but we can set the height for each row:
grid-auto-row: 200px;
grid-auto-row: minmax(200px, auto);

7. We also can set the number and height of the rows using:
grid-template-rows: repeat(4 1fr);

8. We can use grid-column-gap: 20px;
  or using grid-row-gap: 10px; 
  or grid-gap: 10px; (to apply to rows an columns)
  to make gap between the columns or rows

9. We can put elements in certain positions using grid lines:
  grid-column-start: 1;
  grid-column-end: 3;
  grid-column: 1 / 3;
  grid-row-start:
  grid-row-end:
  grid-row: 1 / 8;

10. We can also use nested grid (This is awesome)

11. we can use align-items or justify-items
in the parrent or using justify-self
or align-self in child element
default is stretch

12. Check the mosaic layout it is awsome

13. grid-template-columns: repeat(4, 1fr);
 use grid-area: nameofarea; in child element and 
grid-template-areas:
"nameofare nameofarea nameofarea nameofarea"
"nameofarea2 nameofarea2 nameofarea3 nameofarea3"