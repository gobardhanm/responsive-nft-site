# What we will be Learning...

    > Thinking "responsively"
    > Relative CSS unit
    > Relative Line height
    > Media queries
    > Mobile-first design
    > Responsive site nav
    > flex-wrap, flex, gap

# HTML

    

# CSS

    > Thinking responsively:
        - Responsive is not a trend, It is simply a reality.
        - Consider different screen sizes, placing a strong emphasis on the mobile experience.
        - 'Absolute units' like pixels will always appear the same size no matter where you view them.
        - To make a website responsive we have to use "Relative Units".
            Relative units:
                - Relative to another value
                - Dynamic flixibility
                - Resize & scale
     *- "Percentages" unit is one of the relative unit.
        - When using a percentage for 'width', the percentage is based on the width of its parent element.
        
     *- "The em unit": It's a relative unit-
        - 1em is equal to the parent element's font-size value. (Usually: 16px, if parent element font-size is not set) 

    > max-width : It is used to set the max width of an element.
        Ex:
            max-width: 640px;
    
    > min-width : It is used to set the min width of an element.
        Ex:
            min-width: 320px;

    > margin :
        - If we put '2' value in margin, it will be : (top,bottom) | (left,right) 
        - If we put '3' value in margin, it will be : top | (left,right) | bottom
        - If we put '4' value in margin, it will be : top | right | bottom | left

    > "Images" have a displace value of "inline" , so we can make it "block" if something is not working right.

    > "Margin" and "Padding" values in em are relative to the element's current font-size value.

  **> An "em" value can compound from one level to another.
        Ex: 
            .parent-container{
                font-size: 1.2em;
            }

            .child-item{
                font-size: 1.5em; /* Here the font size of the child item is getting compounded by ( 1.2 * 1.5 ) */
            }

            - To resolve this issue we use, "rem"

    > "rem" unit : (The root em) :

        - By default, a "rem" value will be a multiple of 16px.

        ( It will only change if the html root font-size is changed, 
        Ex:
            html{
                font-size: 20 // Now the rem will act according to this, otherwise the default 16px
            })

    > 