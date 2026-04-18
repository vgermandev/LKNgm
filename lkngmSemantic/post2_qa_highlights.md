# Can a Program "Understand" Geometry?

If a program is asked a question it wasn't explicitly told the answer to, and it deduces the correct response using logic, does it "understand"? 

In **Semantic LKN**, we believe the answer is yes. Here are a few highlights from our latest trace of Euclid’s Book 1 foundations:

**Query:** how many unequal sides does an isosceles triangle have?
**LKN:** One unequal boundary. 
*Reasoning: The engine knows a trilateral figure has 3 sides and the definition of isosceles provides 2 equal ones. It performs the arithmetic deduction automatically.*

**Query:** what angle is greater than an acute angle?
**LKN:** All obtuse angles... because they are greater than a right angle, and an acute angle is less than a right angle.
*Reasoning: This demonstrates transitive relational mapping across multiple definitions.*

**Query:** how many angles does square have?
**LKN:** 4.
*Reasoning: The engine performs deductive subtyping, recognizing that a "Right Angle" is a type of "Angle."*

The journey from Natural Language to Mathematical Truth is just beginning.