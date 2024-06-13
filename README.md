UML
-------------------
 GeometricObject
-------------------
- color: String
- filled: boolean
-------------------
+ getColor()
+ setColor()
+ isFilled()
+ setFilled()
+ toString()
-------------------
  ^
  ^
  ^
  
-------------------
  Triangle
-------------------
- side1: double
- side2: double
- side3: double
-------------------
+ Triangle()
+ Triangle(side1: double, side2: double, side3: double)
+ getSide1(): double
+ getSide2(): double
+ getSide3(): double
+ getArea(): double
+ getPerimeter(): double
+ toString(): String
-------------------
