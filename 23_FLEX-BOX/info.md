FLEX-BOX

    * fles box in not a framwork or anythink like that.its is a new box model ans no extra depadinges required
    * flex stands for flexible,adaptive

Flex box is alternative for 

    * display : block ;
    * display : inline ;
    * display : inline - block ;

Aduvantage of Flex box

    * Easy to align element in vertical centering
    * flox box can have display order reverssed or rearranged at the style layer.
    * one of the main aduantages of flexbox is the ability of fill extra space without the need to use javascript.


FLOX BOX  (flex useing frist step ):


        <html>

            <div class="container"> 
            <div>1</div>
            <div>2</div>
            <div>3</div>
            </div>

        <css>

            .container{
                display:flex;
            }


Main Axis (vs) Cross Axis

                       /|\          
                        |          
                        |(Cross Axix(Y))          
    (Main Aixs(X))      |                        
    -------------------------------------->
                        |                        
                        |                        
                        |
                        |        


01_Flex_direction
    
    flex-direction:row;             #default
    flex-direction:row-reverse;
    flex-direction:column;
    flex-direction: column-reverse

02_Flex_wrap

    flex-wrap:nowrap;               #default
    flex-wrap:wrap;
    flex-wrap:wrap-reverse;

03_Flex_justify_content
(main-axis alignment)

    justify-content:flex-start;    #default
    justify-content:flex-end;
    justify-content:space-between;
    justify-content:space-around;
    justify-content:center;

04_Flex_align_content
(cross-axis alignment)

    align-content:flex-start;       #default
    align-content:flex-end;
    align-content:center;
    align-content:baseline;
    align-content:stretch;    


05_item_order  ==> chiled postion changing in order flex

    order:<number>; 
