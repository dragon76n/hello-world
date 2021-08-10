# hello-world
Just a test

=IF(SMALL($D$2:$D$20,1)=D2,1,IF(SMALL($D$2:$D$20,2)=D2,2,IF(SMALL($D$2:$D$20,3)=D2,3,IF(SMALL($D$2:$D$20,4)=D2,4,IF(SMALL($D$2:$D$20,5)=D2,5,"")))))

=SQRT(($A$25-A2)^2+($B$25-B2)^2)

=IF(SMALL($J$2:$J$20,1)=J2,1,IF(SMALL($J$2:$J$20,2)=J2,2,IF(SMALL($J$2:$J$20,3)=J2,3,IF(SMALL($J$2:$J$20,4)=J2,4,IF(SMALL($J$2:$J$20,5)=J2,5,"")))))


$TX = Target X-Coordinates
$TY = Target Y-Coordinates
$BX = Base X-Coordinates
$BY = Base Y-Coordinates
$DIST = Euclidean Distance

$DIST = SQRT(($TX-$BX)^2+($TY-$BY)^2)
