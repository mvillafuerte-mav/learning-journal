# learning-journal
In this repository, I will describe my learning journey in the field of technology, focusing on machine learning and mathematics.

# Day 1:
I watched the first three chapters of “Essence of Linear Algebra” by 3Blue1Brown. These are my notes:

In linear algebra, there are three main ways to define a vector. The first is the one used by physicists (an arrow with magnitude and direction), the second is the one used by computer scientists (an ordered list of numbers), and the last is the one used by mathematicians (a more abstract object defined by the rules of vector operations).

Any vector in the plane can be written as a linear combination of two basis vectors, scaling each of them by a scalar and then adding them together. The standard basis uses the unit vectors i and j, but in principle any two linearly independent vectors can serve as a basis. By varying the scalars, you can reach any point in the plane, unless the two basis vectors are collinear, in which case the reachable set is limited to a single line.

The set of all vectors you can reach by varying the scalars in a linear combination is called the span of those vectors.

When working with many vectors, it is often useful to think of each vector as a point rather than as an arrow.

In three-dimensional space, the span of two linearly independent vectors is a plane. The span of three linearly independent vectors is all of R3. If one of the three vectors lies in the span of the other two, the vectors are linearly dependent and the span collapses to a plane (or even a line). If none of them lies in the span of the others, they are linearly independent.

Another key topic in linear algebra is the linear transformation: a function that takes vectors to other vectors while preserving two conditions, all lines remain lines (no curving), parallel lines stay parallel and evenly spaced, and the origin remains fixed.

To describe a linear transformation, it is enough to know where the basis vectors i and j land after the transformation, because any other vector can be written as a linear combination of them and will be transformed.

If we apply two or more linear transformations to the space one after another, the result is called a composition. Compositions can be simplified by keeping track of the final coordinates of the unit vectors and treating the whole sequence as a single linear transformation, which is exactly what you get by multiplying the original transformation matrices. 

I find this very interesting because I've worked with matrices before, and now that I see the graphical representation of matrix multiplication, things make sense naturally to me.