This is the solution for grid walk problem -

Find the nos of routes from point A to B. in n * m matrix. With A being top left point and B bottom right point.
For eample 2*2 will have 6 distinguish paths. (Keeping in ming one can only go right and down but not left or up).

Mathematically it can be solved with the formula of 
n! + m! / n! * m!

Other solution can be a algorithm implimentation, my implimentation is for same reason.
I was quite inspired by Pascal's traiangle - https://en.wikipedia.org/wiki/Pascal%27s_triangle

Therefore this cde is developed on undelining idea of Pascal's Triangle.


PossibleWalkThroughMatrix.java class is the main class to start with.