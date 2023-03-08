# Bootstrap-4-Grids
# Boostrap 4 Grid System
Boostrap's grid system is built with flexbox and allows up to 12 columns across the page.

If you do not want to use all 12 columns individually, you can group the columns together to create  wider columns:

Note: You can check the first screenshot on the top i added

The grid system is responsive, and the columns will re-arrange automatically depending on the screen size.

Make sure that the sum adds up to 12 or fewer (it is not required that you use all 12 available columns).

# Grid Classes
The Boostrap 4 grid system has five classes:

.col- (extra small devices - screen width less than 576px)

.col-sm- (small devices - screen width equal to or greater that 576px)

.col-md- (medium devices - screen width equla to or greater than 768px)

.col-lg- (large devices - screen width equal to or greater than 992px )

.col-xl- (xlarge devices - screen width equal to or grater than 1200px)

The classes above can be combined to create more dynamic and flexible layouts. 

Tip: Each class scales up, so if you wish to set the same widths for sm and md, you only need to specify sm.

# Besic Structure of a Boostrap 4 Grid
The following is a besic structure of a Boostrap 4 grid:

    <!-- Control the column width, and how they should appear on different devices -->
    <div class="row">
        <div class="col-*_*"></div>
        <div class="col-*_*"></div>
    </div>    
    <div class="row">
        <div class="col-*_*"></div>
        <div class="col-*_*></div>
        <div class="col-*_*></idv>
    </div>    

    <!-- Or let Boostrap automatically handle the layout -->
    <div class="row">
        <div class="col"></div>
        <div class="col"></div>
        <div class="col"></div>
    </div>    

First example: Create a row (<div class="row">). Then, add the desired number of columns (tags with appropriate .col-*_* classes)> The first star (*)    
represents the responsiveness: sm, md, lg or xl, while the second star represenst a number, which should add up to 12 for each row.

Second example: instead of adding a number to each col, let boosra handle the layout, to create equla width columns: two "col" elements = 50% width to each col. Three cols = 33.33% width to each col. four cols = 25% width, etc. You can also use .col-sm|md|lg|xl to make the columns responsive.

Below we have collected some examples of besic Boostrap 4 grid layouts.

# Three Equal Columns
Note: You can see in the top i added screenshot

The following example shows how to create three equal-widht columns, on all devices and screen width:

Example

    <div class="row">
        <div class="col">.col</div>
        <div class="col">.col</div>
        <div class="col">.col</div>
    </div>    

# Responsive Columns
Note: You can see the screenshot i added on the top

The following example shows how to create four equal-width columns starting at tablets and scaling to extra large desktops. On mobile phones or screen that are less than 576px wide, the columns will automatically stack on top of each other:

Example

    <div class="row">
        <div class="col-sm-3">.col-sm-3</div>
        <div class="col-sm-3">.col-sm-3</div>
        <div class="col-sm-3">.col-sm-3</div>
        <div class="col-sm-3">.col-sm-3</div>

# Two Unequal Responsive Columns
Note: You can check the screenshot i added on the top

The following example shows how to get two various-widh columns starting at tablets and scaling to large extra desktops:

    <div class="row">
        <div class="col-sm-4">.col-sm-4</div>
        <div class="col-sm-4">.col-sm-8</div>
























