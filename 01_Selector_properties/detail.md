simple selectors

    1.element selector     ==>  html tage                    
    2.class selector       ==>  .<class_name>                
    3.id selector          ==>  #<id_name>
    4.univasal selector    ==>  *{..}                

combinators selectors

    1.Descendant         ==>   div p{...};      perant child is selecting in (DEscedent selecter)      
    2.Direct child       ==>   div > p {...};   div is only direct child
    3.Adjacent sibling   ==>   div + p {...};   div down the p(peragh) tag in selecting 
    4.General sibling    ==>    ~

:root pseudo selector

    syntex:

    :root {
        css declarations;
        }

    