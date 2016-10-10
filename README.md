# Triangle-Inequality-Violation
Triangle Inequality Violation

The [triangle inequality](https://en.wikipedia.org/wiki/Triangle_inequality) theorem states that for any triangle, the sum of the lengths of any two sides must be greater than or equal to the length of the remaining side.

**Data Set**: The [Turkish Network file](http://ie.bilkent.edu.tr/~bkara/Turkish%20network.xls) contains the data on the 81 node Turkish network. 
The file includes travel distances between 81 cities in Turkey.

Generate all possible combination of triangles C(81,3) from the 81 cities of Turkey using the [combinatorics](https://github.com/dpaukov/combinatoricslib3) library. 
Travel distances in kilometers will be the sides of the triangle. 
List all of the triangles that violate the triangle inequality. 
Your project must be a Maven project (please watch the [video](https://www.youtube.com/watch?v=IPpwekVcs_g) to create one) and following commands should be enough to run it.

* mvn clean package
* java -jar target/HW1-1.0.jar 

Your project will print out something like:

```
ESKİŞEHİR GİRESUN ARDAHAN
DİYARBAKIR KIRŞEHİR ZONGULDAK
AĞRI ERZİNCAN MUĞLA
 ```
Please click the [invitation link](https://classroom.github.com/assignment-invitations/7f3bf3c9be93a67be24fedd0e049971a) and follow the instructions to get started with the submission system.