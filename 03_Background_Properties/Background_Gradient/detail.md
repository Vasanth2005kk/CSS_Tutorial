Background Gradient types:

    1. background: linear-gradient();
    2. background: repeating-linear-gradient();

    3. background: radial-gradient();
    4. background: repeating-radial-gradient();

    5. background: conic-gradient();
    6. background: repeating-conic-gradient();

background: linear-gradient(<position> or <degree> ,<many_colors>);

background: repeating-linear-gradient(<position> or <degree> ,<many_colors>);

==> <position> 
        to right
        to left 
        to top
        to bottom
        to bottom right
        to bottom left
        to top left
        to top right

==> <degree>
        -45deg
        45deg  

==> <color>
    color name or color_name 10 %
    
    (eg) : red 10%



background: radial-gradient(<<shape><size>at<position>>,<color>); 

background:repeating-radial-gradient(<<shape><size>at<position>>,<color>);

==> <<shape><size>at<position>>

shape

    ellipse (default)
    circle

size

    farthest-corner (default)
    closest-side
    closest-corner
    farthest-side

position 

    center or unit_values (eg) ==> 50% 50%



background: conic-gradient(<from_angle> <at_position> <color_degree>);
background: repeating-conic-gradient(<from_angle> <at_position> <color_degree>);


==> <from_angle>
    
        form 90geg

==> <at_position>

        at 40% 30%

==> color degree

        red 10geg