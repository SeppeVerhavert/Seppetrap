# Seppetrap
My own CSS framework

https://seppeverhavert.github.io/Seppetrap/

# How the grid works
  
Open a **container** so Seppetrap knows that you want to make a grid.

The grid is displayed in **rows first** and columns second.

Rows are flex-based and dispalyed inline.
Rows have no padding to fit the container.
Rows have a purple background and white text.
  
options for rows are:
  - row-wrap: flex-wrap
  - row-top: align-items: flex-start;
  - row-center: align-items: center;
  - row-bottom: align-items; flex-end;
  - row-stretch: align-items: stretch;
  - row-baseline: align-items; baseline;
  
  Rows are divided in **10 columns** and are presented in numbers.
  eg: column: column-50 will display a column with a width of half your row.
  
  Columns can be offset in **10 steps**.
  eg: column-offset-50 will make the column start at half the row width.
  
  Columns can be aligned in the rows.
  - column-top:  align-self: flex-start;
  - column-bottom: align-self: flex-end;
  - column-center: align-self: center;
  

  
