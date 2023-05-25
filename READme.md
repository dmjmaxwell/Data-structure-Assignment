<!-- question 1 -->
Create a set of all distinct elements from the two sets.
Calculate the sum of the distinct elements.
Find the sum of all distinct elements from two sets.
The sum of all distinct elements from the two sets.

<!-- question 2a-->

<!-- create a function  -->
function dot_product(v1, v2):
  """
Calculates the dot product of two vectors.
<!-- defining the parameters -->
parameters:
v1: The first vector.
v2: The second vector.

Returns:
The dot product of v1 and v2.
  
ps = 0
for i in range(len(v1)):
ps += v1[i] * v2[i]

output ps

<!-- question 2b -->

def are_orthogonal(v1, v2):
a. create a function taking in the two previous parameters
Determines if two vectors are orthogonal.
Args:
v1: The first vector.
v2: The second vector.

b.Create a conditional statement that return true if the result equals to 0 and returns false if not equal to 0.
Returns:
True if v1 and v2 are orthogonal, False otherwise.

ps = dot_product(v1, v2)
return ps == 0

<!-- question 2c -->

for i in range(n):
  if are_orthogonal(v1[i], v2[i]):
    print("The vectors are orthogonal")
  else:
    print("The vectors are not orthogonal")
