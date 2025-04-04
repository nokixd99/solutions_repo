<h2>Linear Algebra</h2>

<h3>➊ Basic Operations on Matrices</h3>

<p>Given matrices:</p>

<pre>
A = [2  3]
    [1 -1]

B = [5 0]
    [2 1]

C = [-1  3]
    [ 4  2]

D = [4 -2 1]
    [3  0 2]
</pre>

<h4>1. Calculate</h4>
<pre>
A + B = [7  3]
        [3  0]

B - A = [ 3 -3]
        [ 1  2]

A + C + D (Not defined — C and D have incompatible sizes)
</pre>

<h4>2. Calculate</h4>
<pre>
i) 3A = [ 6  9]
        [ 3 -3]

ii) -2B = [-10  0]
          [-4 -2]

iii) Cᵗ = [-1  4]
          [ 3  2]
</pre>

<h4>3. Calculate the products</h4>
<pre>
i) AB = [16  3]
         [3 -1]

ii) BA = [10 15]
          [4  5]

iii) A² = [ 7  3]
           [-1  4]

iv) B² = [25  0]
           [10  1]
</pre>

<h3>➋ Determinants 2x2 and 3x3</h3>

<h4>2x2 Matrices</h4>
<pre>
|A| = (2)(-1) - (3)(1) = -2 - 3 = -5
|B| = (5)(1) - (0)(2) = 5
|C| = (-1)(2) - (3)(4) = -2 - 12 = -14
</pre>

<h4>3x3 Matrices</h4>
<pre>
|D| = 4(0×0 - 2×2) - (-2)(3×0 - 2×1) + 1(3×0 - 0×1)
    = 4(0 - 4) + 2(0 - 2) + 1(0 - 0)
    = -16 - 4 + 0 = -20
</pre>

<h3>➌ Determinants using Laplace Expansion</h3>

<pre>
A = [2  3  1]
    [0 -1  4]
    [1  2  0]

|A| = 2 × det([-1 4; 2 0]) - 3 × det([0 4; 1 0]) + 1 × det([0 -1; 1 2])
    = 2 × (-1×0 - 4×2) - 3 × (0×0 - 4×1) + 1 × (0×2 - (-1)×1)
    = 2 × (-8) - 3 × (-4) + 1 × (1)
    = -16 + 12 + 1 = -3
</pre>

<h3>➍ Determinants using Gaussian Elimination</h3>

<pre>
A = [1 2 3]
    [2 4 6]
    [3 6 9]

Bu matrisin satırları lineer bağımlı. Gaussian yöntemiyle sıfır satır oluşur. Bu yüzden:
|A| = 0

B = [1 5 3]
    [0 4 2]
    [0 0 6]

Bu matris üst üçgen halde. Determinant:
|B| = 1 × 4 × 6 = 24
</pre>

<h3>➎ Inverse of a Matrix using the Formula</h3>

<pre>
A = [1 0 0]
    [0 1 0]
    [0 0 1]

Inverse of identity matrix is itself:
A⁻¹ = A
</pre>

<h3>➏ Determine the Rank</h3>

<pre>
A = [1 -3]
    [2  4]
    [4  7]

Gaussian elimination:
R1 = [1 -3]
R2 = R2 - 2×R1 → [0 10]
R3 = R3 - 4×R1 → [0 19]

Tüm satırlar sıfır değil, hepsi lineer bağımsız → Rank = 2
</pre>

<h3>➐ Inverse using Gaussian Method</h3>

<pre>
A = [6 3]
    [3 3]

Augment with identity: [6 3 | 1 0]
                       [3 3 | 0 1]

R1 ÷ 6: [1 0.5 | 0.166 0]
R2 - 3×R1: [0 1.5 | -0.5 1]

R2 ÷ 1.5: [0 1 | -1/3 2/3]
R1 - 0.5×R2: [1 0 | 1/3 -1/3]

A⁻¹ = [1/3  -1/3]
       [-1/3  2/3]
</pre>

<h2>❼ Linear Equations (Old School)</h2>
<p>Solve the following systems of equations without using matrices.</p>

<h3>System 1</h3>
<pre>
x + 2y = 5  
2x − y = 7

Solution:
From equation 2: y = 2x − 7  
Substitute into equation 1:  
x + 2(2x − 7) = 5 → x + 4x − 14 = 5 → 5x = 19 → x = 19/5  
Then y = 2(19/5) − 7 = 38/5 − 35/5 = 3/5

Answer: x = 19/5, y = 3/5
</pre>

<h3>System 2</h3>
<pre>
4x − 5y = 3  
3x + y = 4

Solution:
From equation 2: y = 4 − 3x  
Substitute into equation 1:  
4x − 5(4 − 3x) = 3 → 4x − 20 + 15x = 3  
19x = 23 → x = 23/19  
Then y = 4 − 3(23/19) = (76 − 69)/19 = 7/19

Answer: x = 23/19, y = 7/19
</pre>

<h3>System 3</h3>
<pre>
x + y + z = 3  
2x − y + 2z = 3  
x − 2y + 3z = 11

Solution:
Use substitution or elimination:
From equation 1: x = 3 − y − z  
Substitute into equation 2:
2(3 − y − z) − y + 2z = 3 → 6 − 2y − 2z − y + 2z = 3 → −3y = −3 → y = 1  
Now x = 3 − 1 − z = 2 − z  
Substitute into equation 3:
(2 − z) − 2(1) + 3z = 11 → 2 − z − 2 + 3z = 11 → 2z = 11 → z = 5.5  
Then x = 2 − 5.5 = −3.5

Answer: x = −3.5, y = 1, z = 5.5
</pre>

<h3>System 4</h3>
<pre>
x + y − z = 2  
2x − y + z = 3  
3x + y + 2z = 1

Solution:
Eliminate z using equations 1 and 2:
Add: (x + y − z) + (2x − y + z) = 2 + 3 → 3x = 5 → x = 5/3  
Substitute x into equation 1: 5/3 + y − z = 2 → y − z = 2 − 5/3 = 1/3  
Equation 3: 3(5/3) + y + 2z = 1 → 5 + y + 2z = 1 → y + 2z = −4  
Now solve:  
y − z = 1/3  
y + 2z = −4

Subtract: (y + 2z) − (y − z) = −4 − 1/3 → 3z = −13/3 → z = −13/9  
Then y = 1/3 + z = 1/3 − 13/9 = −10/9  
x = 5/3

Answer: x = 5/3, y = −10/9, z = −13/9
</pre>

---

<h2>❽ Linear Equations by Cramer's Rule</h2>

<h3>1. Solve the system:</h3>
<pre>
2x + y = 7  
x − 3y = −1

Using Cramer’s Rule:
D = | 2  1 |
    | 1 −3 | = (2)(−3) − (1)(1) = −6 − 1 = −7  
Dx = | 7  1 |
     | −1 −3 | = (7)(−3) − (1)(−1) = −21 + 1 = −20  
Dy = | 2  7 |
     | 1 −1 | = (2)(−1) − (7)(1) = −2 − 7 = −9  

x = Dx/D = −20 / −7 = 20/7  
y = Dy/D = −9 / −7 = 9/7

Answer: x = 20/7, y = 9/7
</pre>

<h3>2. Solve the system:</h3>
<pre>
4x − 2y = 1  
3x + y = −1

D = | 4 −2 |
    | 3  1 | = 4×1 − (−2×3) = 4 + 6 = 10  
Dx = | 1 −2 |
     | −1 1 | = 1×1 − (−2×−1) = 1 − 2 = −1  
Dy = | 4 1 |
     | 3 −1 | = 4×(−1) − (1×3) = −4 − 3 = −7

x = −1 / 10  
y = −7 / 10

Answer: x = −1/10, y = −7/10
</pre>

<h3>3. Solve the system:</h3>
<pre>
2x − y + z = −1  
3x + 2y − z = 4  
x + y + z = −2

Compute determinants:

D = | 2 −1  1 |
    | 3  2 −1 |
    | 1  1  1 | = −3  

Dx = | −1 −1  1 |
     |  4  2 −1 |
     | −2  1  1 | = −9  

Dy = | 2 −1  1 |
     | 3  4 −1 |
     | 1 −2  1 | = −3  

Dz = | 2 −1 −1 |
     | 3  2  4 |
     | 1  1 −2 | = −12  

x = −9 / −3 = 3  
y = −3 / −3 = 1  
z = −12 / −3 = 4

Answer: x = 3, y = 1, z = 4
</pre>

<h3>4. Why can't the system be solved using Cramer’s Rule?</h3>
<pre>
x + 2y = 3  
2x + 4y = 6

D = | 1  2 |
    | 2  4 | = 1×4 − 2×2 = 4 − 4 = 0

Since D = 0, the system is either dependent or inconsistent.
Cramer's Rule does not apply when the determinant is 0.
</pre>

---

<h2>❾ Linear Equations by Gaussian Elimination</h2>

<h3>System 1</h3>
<pre>
x + 2y − z = 4  
2x − y + 3z = −6  
3x + y + 2z = 7

Apply Gaussian Elimination to solve.
Final solution: x = −1, y = 2, z = 0
</pre>

<h3>System 2</h3>
<pre>
2x + y − z = −3  
x − y + 2z = 4  
3x − 2y + z = −1

Solution: x = −1, y = −2, z = 0
</pre>

<h3>System 3</h3>
<pre>
x + y + z = 6  
x + 2y + 3z = 14  
2x + 3y + z = 10

Solution: x = 1, y = 2, z = 3
</pre>

---

<h2>❿ Linear Equations by Matrix Inversion</h2>

<h3>1. Solve using inverse matrix method:</h3>
<pre>
[ 2  1 ] [x] = [7]
[ 1 −3 ] [y]   [−1]

Inverse of A = (1/Det) × adj(A)

Det = −7  
A⁻¹ = (1/−7) × [−3 −1; −1 2]  
Solution: [x y] = A⁻¹ × B → x = 20/7, y = 9/7
</pre>

<h3>2. Solve using inverse matrix method:</h3>
<pre>
[ 4  −2 ] [x] = [1]
[ 3   1 ] [y]   [−1]

Det = 4×1 − (−2×3) = 4 + 6 = 10  
A⁻¹ = (1/10) × [1 2; −3 4]  
Solution: x = −1/10, y = −7/10
</pre>
