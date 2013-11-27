PCA-PIR
=======

<h3>Principal component analysis for PIR</h3>


<strong>Description</strong>:

This repository is the principal component analysis code for the <strong>PIR</strong> (Premier Information Retrieval®)
research project and it's in addition to the GeneticAlgorithm-THL repository as well as other repositories that
will comprise the overall <strong>PIR</strong> project at hand.

For <strong>PIR</strong>, the objective of analysis is to transform the data into its principal components; the 
principal components are the eigenvectors of the covariance matrix that describe the relations among the
initial set of variables. With each eigenvector representing one new variable, the new variables become <i>orthogonal</i>,
or independent of one another. Eigenvalues, on the other hand, of the principal components correspond to the variance
(or, in this case, covariance) of each component. 

For the <strong>PIR</strong> project, I'm not just concerned with the direction of one vector because with an
eigenvector, you're not worried about <i>one</i> vector, you're dealing with <i>several</i> vectors. If there's a
complicated matrix to deal with then you want to make changes to the coordinates in order to make it simple. Think
of a diagonal matrix because you cannot always change the coordinates to revise the information in a matrix,
matrix N. Eigenvectors of a diagonal matrix are easier to find since the eigenvalues of those eigenvectors in a
diagonal matrix are just numbers on the diagonal. However, for <strong>PIR</strong>, you're dealing with more complex
matrices, therefore, in the matter of being advantageous, principal components will take a set of random vectors and
"orthogonalize" the set of vectors and "rotate" the vectors the same way you would rotate a vector by multiplying it
with a valid rotation matrix, say matrix N has a determinant of 1.

Don't take a matrix with a determinant of 1 and think that it's derived from a lower dimension. Principal components are
sorted via variance (or, covariance) in an order that decrements, so the first set of vectors will have larger
contributions in variance of the data with the last set of vectors having the smallest contribution. This seems similar
to <strong>PIR</strong> with the larger six <i>set</i> points of data being "penetrated" and the data within 
those <i>set</i> points being retrieved first, if that makes sense.



****************************************************************

<i>Permission to use, copy, modify and distribute this software and
its documentation for any purpose, and for a fee, is hereby granted 
on the condition that the above copyright notice  appear in all copies 
and that both the copyright notice and this permission notice and warranty 
disclaimer appear in supporting documentation, and that the name of 
Desmond J. Watson not be used in advertising or publicity pertaining to 
distribution of the software without specific written prior permission.</i>

<i>The owners of this software, Desmond J. Watson and The Hexagon Lavish, 
disclaims all warranties with regards to this software, including all implied
warranties of merchantability and fitness. In no event shall the owners
of this software, Desmond J. Watson or The Hexagon Lavish, be liable for 
any special, indirect or consequential damages or any damages whatsoever 
resulting from loss of use, data or profits, whether in an action of contract, 
negligence or other tortious action, arising out of or in, connection with the 
use or performance of this software.</i>

******************************************************************


<h3>© 2013 The Hexagon Lavish. All Rights Reserved.</h3>
