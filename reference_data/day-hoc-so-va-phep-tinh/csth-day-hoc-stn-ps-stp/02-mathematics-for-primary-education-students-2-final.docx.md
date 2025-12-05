

## 1.1. Sets and Operations

### 1.1.1. Bijection

**Definition 1.1.** Let X and Y be two sets. The rule that assigns each element  $x$  in set X to a unique element  $y = f(x)$  in set Y is called a mapping from set X to set Y, denoted

as:  $f: X \to Y$   
 $x \mapsto y = f(x)$ . Set X is called the domain (or source set), and set Y is called the

target set of mapping f.

For each  $x \in X$ , we call  $f(x)$  the image of element  $x$ , and  $x$  is the pre-image of  $f(x)$  under mapping f. If A is a subset of X, then we call the set:  $f(A) = \{f(x) : x \in A\}$  the image of set A under mapping f.

In special cases,  $f(X)$  is called the image set of mapping f.

**Definition 1.2.** Let f be a mapping from set X to set Y. We call:

a) f injective (or one-to-one), if for every  $x_1, x_2 \in X, x_1 \neq x_2 \to f(x_1) \neq f(x_2)$ , or equivalently, different pre-images correspond to different images.

b) f surjective (or onto), if for every  $y \in Y \exists x \in X : f(x) = y$ , or equivalently,  $f(X) = Y$ .

In this case, we say that f is a mapping from set X onto set Y.

c) f bijective, if f is both injective and surjective.

#### **Example 1.1.**

Let  $X = \{a, b, c, d, e\}$ ;  $Y = \{1, 2, 3, 4, 5\}$ . We define:  $f: X \to Y$  defined by the rule:  $f(a) = f(e) = 1$ ;  $f(b) = 2$ ;  $f(c) = 3$ ; and  $f(d) = 4$ . Then f is a mapping from X to Y, but it is not injective and not surjective.

#### **Example 1.2.**

Each function encountered in secondary school defines a mapping with the domain being the domain of the function to the set of real numbers R.

For example, the function  $y = 2^x - 1$  defines a mapping from R to R with the defining rule being the defining rule of the function.

This mapping is injective but not surjective.

The function  $y = x^3 + 1$  also defines a bijective mapping:  $\varphi: R \to R$   
 $x \mapsto \varphi(x) = x^3 + 1$  from set R to itself.

##### **Example 1.3.**

Let X be the set of points on line AB and Y be the set of points on line CD. We define:

$$g: X \to Y \quad \text{where M and N are determined}$$
$$M \mapsto g(M) = N$$

as shown in the figure. Then g is a bijective mapping from set X to set Y.

![Figure showing two parallel lines AB and CD. Points A, M, B are on line AB, and points C, N, D are on line CD. M and N are the projections of A and B onto CD, respectively.](d5fc881e4328d6a2e76c9576408ced49_img.jpg)

Figure showing two parallel lines AB and CD. Points A, M, B are on line AB, and points C, N, D are on line CD. M and N are the projections of A and B onto CD, respectively.

##### **Example 1.4.**

Let A be the set of humans living on Earth and B be the set of their names. If we define: for each a in set A, there corresponds an element b = f(a) which is the name of that person, then we have a surjective mapping from A to B, but not an injective one (assuming each person has only one name).

**Definition 1.3.** Let f be a bijective function from set X to set Y. We call

$$f^{-1}: Y \to X \quad \text{the inverse mapping of f the inverse function, if for every } x \in X \text{ we}$$
$$y \mapsto f^{-1}(y) = x$$

always have  $f^{-1}(f(x)) = x$ , or for every  $y \in Y: f(f^{-1}(y)) = y$ .

##### **Example 1.5.**

The inverse mapping  $\phi^{-1}$  of the mapping  $\phi$  in example 1.1 is defined by the rule  $\phi^{-1}(y) = \sqrt{y-1}$  for every real number y.

##### **Example 1.6.**

The mapping g in example 1.2 has an inverse mapping  $g^{-1}$  defined by the rule  $g^{-1}(N) = M$ .

**Definition 1.4.** Let:  $f: X \to Y$   $g: Y \to Z$ . We call:  $h: X \to Z$  the composition (or product) of two mappings f and g.

##### **Example 1.7.**

The concept of function composition is a special case of composition of mappings.

#### **Example 1.8.**

Let X and Y be two sets in Example 1.1, and  $Z = \{An, Cuc, Nga\}$ . We define: f is the mapping in Example 1.1 and g is the mapping from Y to Z:  $g(1) = An$ ,  $g(2) = g(5) = Cuc$ , and  $g(3) = g(4) = Nga$ . Then the composition mapping  $h: X \to Z$ : defined by the rule:  $h(a) = An$ ;  $h(b) = Cuc$ ;  $h(c) = h(d) = Nga$ ; and  $h(e) = An$ .

**Theorem 1.1.** Properties of operations on mappings:

(i) The composition of two injective mappings is an injective mapping.

(ii) The composition of two surjective mappings is a surjective mapping.

(iii) The composition of two bijective mappings is a bijective mapping.

*Proof.*

(i) Assume  $f$  is an injective mapping from  $X$  to  $Y$ ,  $g$  is an injective mapping from  $Y$  to  $Z$ , and  $x^1, x^2$  are two distinct elements in  $X$ . Since  $f$  is injective  $f(x_1) \neq f(x_2)$ , . Since  $g$  is also injective  $g(f(x_1)) \neq g(f(x_2))$  or  $h(x_1) \neq h(x_2)$  .

(ii) and (iii) Similar to (i).

### 1.1.2. Equivalent Sets

**Definition 1.5.** Let  $X$  and  $Y$  be two sets. We say that set  $X$  is equivalent to set  $Y$ , denoted as  $X \sim Y$ , if there exists a one-to-one correspondence  $f$  from  $X$  to  $Y$ .

**Example 1.10.** Sets  $X$  and  $Y$  in Example 1.1 are equivalent to each other.

**Example 1.11.** According to Example 1.2, the set of points on line  $AB$  is equivalent to the set of points on line  $CD$ .

**Example 1.12.** The set  $I$  consisting of real numbers between 0 and 1 ( $I = (0,1)$ ) is equivalent to the set of positive real numbers.

Indeed, the one-to-one correspondence  $f$  defined by the rule:  $f(x) = \frac{1}{x}$

**Example 1.13.** The set  $(a, b)$  of real numbers between  $a$  and  $b$  and the set  $(c, d)$  of real numbers between  $c$  and  $d$  are equivalent to each other.

**Theorem 1.2.** (Properties of the equivalence relation between sets)

The equivalence relation between sets satisfies the following properties:

1. Reflexive property: Every set  $A$  is equivalent to itself.
2. Symmetric property: If  $A$  is equivalent to  $B$ , then  $B$  is also equivalent to  $A$ .
3. Transitive property: If  $A$  is equivalent to  $B$  and  $B$  is equivalent to  $C$ , then  $A$  is equivalent to  $C$ .

*Proof.* Trivial.

### 1.1.3. Addition and multiplication

#### 1.1.3.1. Definition and properties

**Lemma 1.** For any natural numbers  $a$  and  $b$ , there always exist two disjoint finite sets  $A$  and  $B$  such that  $a = \text{Card } A$  and  $b = \text{Card } B$ .

*Proof.* Let  $a$  and  $b$  be two natural numbers, where  $a = \text{Card } A$  and  $b = \text{Card } B$  with  $A$  and  $B$  being finite sets.

If  $A \cap B = \emptyset$ , then the lemma is proven.

Choose two arbitrary elements  $x \neq y$ , let  $A' = A \times \{x\}; B' = B \times \{y\}$ , then  $A'$  and  $B'$  are both finite sets and  $A' \sqcup A; B' \sqcup B$ , so  $a = \text{Card } A'$  and  $b = \text{Card } B'$ . Thus,  $A'$  and  $B'$  satisfy the requirements.

**Lemma 2.** Suppose  $A$ ,  $B$ ,  $A'$ , and  $B'$  are finite sets such that

$$A \sqcup A', B \sqcup B'; A \cap B = A' \cap B = \emptyset.$$

$$(i) A \cup B \sqcup A' \cup B';$$

$$\text{Then: } (ii) A \times B \sqcup A' \times B'.$$

*Proof.* Straightforward.

**Definition 1.6.** Let  $a$  and  $b$  be two natural numbers, where  $a = \text{Card } A$  and  $b = \text{Card } B$  with  $A$  and  $B$  being two disjoint finite sets. We call:

a) The sum of the two natural numbers  $a$  and  $b$  is a natural number  $c$ , denoted as  $c = a + b$ , where  $c = \text{Card } A \cup B$ .

The rule that corresponds each pair of natural numbers  $a$ ,  $b$  with the natural number  $c$  mentioned above is called addition of natural numbers, where  $a$  and  $b$  are called addends,  $s$  is called the sum, and  $a + b$  is also called the sum.

b) The product of the two natural numbers  $a$  and  $b$  is a natural number  $p$ , denoted as  $p = a \times b$  (or  $a \cdot b$  or  $ab$ ), where  $p = \text{Card } A \times B$ .

The rule that corresponds each pair of natural numbers  $a$ ,  $b$  with the natural number  $p$  mentioned above is called multiplication of natural numbers, where  $a$  and  $b$  are called factors,  $p$  is called the product, and  $a \cdot b$  is also called the product.

**Observation.** From the definition, theorem 4.3, and lemmas 1 and 2, we can easily deduce:

a) For every pair of natural numbers  $a$  and  $b$ , there exists a unique natural number  $c$  that is their sum.

b) For every pair of natural numbers  $a$  and  $b$ , there exists a unique natural number  $p$  that is their product.

**Theorem 1.3.** (Properties of addition and multiplication)

(i) Commutative property: For any natural numbers  $a$  and  $b$ , we always have:

$$a + b = b + a; a \cdot b = b \cdot a$$

(ii) Associative property: For any natural numbers  $a$ ,  $b$ , and  $c$ , we always have:

$$a + (b + c) = (a + b) + c; a \cdot (b \cdot c) = (a \cdot b) \cdot c$$

(iii) Distributive property: For any natural numbers  $a$ ,  $b$ , and  $c$ , we always have:

$$a \cdot (b + c) = a \cdot b + a \cdot c$$

(iv) Identity element: For any natural number  $a$ , we always have:

$$a + 0 = 0 + a = a; a \cdot 1 = 1 \cdot a = a$$

(v) Successor property: For any natural number  $a$ , we always have: The successor of  $a$ , denoted as  $a' = a + 1$ .

*Proof.* (i), (ii), and (iii) directly follow from the definition of addition, multiplication, and the commutative, associative, and distributive properties of operations on sets.

(iv) It is clear that  $A \cup \emptyset = A; A \times \{x\} \sqcup A$ . From this, the proof has been completed.

(v) According to the definition, the successor of  $a' = \text{Card } A \cup \{x\} = \text{Card } A$ , which

implies  $\text{Card } A \cup \{x\} = \text{Card } A + \text{Card } \{x\} = a + 1$ .

**Note.** For simplicity, we assume:

a) Write  $a + b + c$  instead of  $a + (b + c)$  or  $(a + b) + c$ ;

b) Write  $a.b.c$  instead of  $a.(b.c)$  or  $(a.b).c$ .

#### 1.1.3.2. Monotonicity of addition and multiplication

**Theorem 1.4.** (Monotonicity of addition and multiplication)

For any natural numbers  $a$ ,  $b$ , and  $c$ , we always have:

$$(i) a \le b \rightarrow a + c \le b + c; a.c \le b.c;$$

$$(ii) a + c = b + c \rightarrow a = b: \text{ Monotonicity law of addition.}$$

$$a.c = b.c; c \neq 0 \rightarrow a = b: \text{ Monotonicity law of multiplication.}$$

$$(iii) a + c < b + c \rightarrow a < b$$

$$a.c < b.c \rightarrow a < b.$$

*Proof.*

(i) Suppose  $a = \text{Card } A$ ;  $b = \text{Card } B$ ;  $c = \text{Card } C$ , with  $A \cap C = B \cap C = \emptyset$ . If  $a = b$ , then it is clear that  $a + c = b + c$ .

If  $a < b$ , we can consider  $A \subset B$ ,  $A \neq B$ . In this case  $A \cup C \subset B \cup C$ ,  $A \cup C \neq B \cup C$ ,

From this, we deduce that  $a + c < b + c$ .

The same reasoning applies to multiplication.

(ii) Suppose  $a + c = b + c$  and  $a < b$ . From the previous proof, we deduce that  $a + c < b + c$ . This contradicts the assumption. Therefore, the proof is complete.

The same reasoning applies to multiplication.

(iii) Follows from (i).

*Observation.* From the definition, we deduce that addition and multiplication of natural numbers are always possible.

#### 1.1.3.3. Subtraction

**Theorem 1.5.** (Existence and uniqueness of the difference of two natural numbers)

Suppose  $a$  and  $b$  are two natural numbers, where  $\cdot$ . Then there exists a unique natural number  $c$  such that  $b + c = a$ .

*Proof.* Suppose  $a = \text{Card } A$ ;  $b = \text{Card } B$ ;  $B \subset A$ . Let  $C = A \setminus B$  and  $c = \text{Card } C$ . It is clear that  $A = B \cup C$ ;  $B \cap C = \emptyset$  and  $a = b + c$ .

**Definition 1.7.** Let  $a$  and  $b$  be two natural numbers, with  $b \le a$ . We call the natural number  $c$  in theorem 1.5 the difference of  $a$  and  $b$ , denoted as  $c = a - b$ .

The rule that corresponds each pair of natural numbers  $a$ ,  $b$  with the natural number  $c$  mentioned above is called subtraction of natural numbers.

**Theorem 1.6.** (Properties of subtraction)

For any natural numbers  $a$ ,  $b$ , and  $c$ , we always have:  $a.(b - c) = a.b - a.c$  if either side is meaningful.

*Proof.*

Suppose  $b - c = d$ . Then  $b = c + d$ . We have:

$$a.b = a.(c + d) = a.c + a.d.$$

From this, we deduce that  $a.(b - c) = a.b - a.c$ .

*Observation.* From the definition, we deduce that subtraction of natural numbers is not always possible.

#### 1.1.3.4. Divisibility and Division in the Set of Natural Numbers

**Definition 1.8.** Let  $a$  and  $b$  be two natural numbers, where  $b$  is not equal to 0. We say that  $a$  is divisible by  $b$ , denoted as  $a \mid b$  (or  $b$  divides  $a$ , denoted as  $b \mid a$ ), if there exists a natural number  $q$  such that:  $a = bq$ .

In this case, we call a the dividend, b the divisor, and q the quotient of the division of a by b, and we write:  $a : b = q$  or  $q = \frac{a}{b}$ . The rule corresponding to each pair of natural numbers a, b with a natural number q as mentioned above is called the division of natural numbers.

**Example 1.19.**

15 is divisible by 3 (or 3 divides 15), because  $15 = 3 \cdot 5$ . We write:  $15 : 3 = 5$ .  
132 is divisible by 12 (or 12 divides 132), because  $132 = 12 \cdot 11$ . We write:  $132 : 12 = 11$ .

**Theorem 1.7.** (Properties of Divisibility)

1. For every non-zero natural number a, we always have  $a | a$ .
2. If  $a : b$  and  $b : a$ , then  $a = b$ .
3. If  $a : b$  and  $b : c$ , then  $a : c$ .
4. The number 0 is divisible by every non-zero natural number.
5. Every natural number is divisible by 1.

*Proof.*

1. Clearly,  $a = a \cdot 1$ .
2. Suppose  $a : b$  and  $b : a$ . Then there exist  $q, q' \in N$  such that  $a = b \cdot q$  and  $b = a \cdot q'$ . Substituting, we get  $a = a \cdot q \cdot q'$ . Therefore,  $q \cdot q' = 1$ , which implies  $q = q' = 1$ . Substituting, we get  $a = b$ .
3. Suppose  $a : b$  and  $b : c$ . Then there exist  $q, q' \in N$  such that  $a = b \cdot q$  and  $b = c \cdot q'$ . Substituting, we get  $a = c \cdot q \cdot q'$ . Therefore, the theorem holds.
4. Clearly,  $0 = b \cdot 0$ .
5. Clearly,  $a = 1 \cdot a$ .

*Observation.* Each division of two natural numbers has at most one quotient.

Indeed, suppose a and b are two natural numbers and  $a : b = q$ ,  $a : b = q'$ . According to the definition, we have  $a = b \cdot q$  and  $a = b \cdot q'$ . Therefore,  $b \cdot q = b \cdot q'$ . Since b is not equal to 0, we have  $q = q'$ .

#### 1.1.3.5. Division with Remainder

**Theorem 1.8.** (Division with Remainder in the Set of Natural Numbers)

Suppose a and b are two natural numbers, where  $b \neq 0$ . In this case, there exists a unique pair of natural numbers q and r such that:  $a = bq + r$ , where  $0 \le r < b$ .

*Proof.*

1. Existence: Suppose a and b are two natural numbers, where  $b \neq 0$ . Let  $A = \{m : bm \le a\}$  It is clear that A is not empty and bounded above, so it has a greatest element. We call the greatest element q and let  $r = a - bq$ . It is clear that  $a = bq + r$ ;  $0 \le r < b$

1. Uniqueness: Suppose there exist  $q_1, q_2, r_1, r_2 \in N : a = bq_1 + r_1 = bq_2 + r_2$ ,  $0 \le r_1, r_2 < b$ .

Suppose  $q_1 \le q_2$ . We assume  $q_2 = q_1 + m$ , where m is a natural number. We have:

$$bq_2 + r_2 = b(q_1 + m) + r_2 = bq_1 + bm + r_2 = bq_1 + r_1.$$

Therefore,  $bm + r_2 = r_1$ . Since  $r_1 < b$ , this can only happen when  $m = 0$ .

Hence,  $q_1 = q_2$  and  $r_1 = r_2$ . This completes the proof.

**Definition 1.9.** Let a and b be two natural numbers, where  $b \neq 0$ , and q and r be the two numbers mentioned in the above theorem. We call q the approximate quotient (or quotient) and r the remainder in the division of a by b.

The rule corresponding to each pair of natural numbers  $a$ ,  $b$  with a pair of natural numbers  $q$  and  $r$  as mentioned above is called the division with remainder in the set of natural numbers.

**Note.** From the definition, we see that divisibility is a special case of division with remainder (when the remainder is 0).

Example 1.20.

$$17 : 5 = 3 \text{ (remainder 2)}$$

$$67 : 4 = 16 \text{ (remainder 3)}$$

$$31 : 12 = 11 \text{ (remainder 11)}$$

## 1.2. Binary Relations

**Definition 1.10.** Given two sets  $X, Y$ . Set  $R$  is a binary relationship between two terms  $X$  and  $Y$  if  $R \subseteq X \times Y$ .

If  $(x, y) \in R$  then we say  $x$  has a relationship (Binary) with  $y$  and  $R = \{(a, b) \in A \text{ is symbolize } b\}$ .

Then,  $R = \{(1,1), (1,2), (1,3), (1,4), (2,2), (2,4), (3,3), (4,4)\}$

## 1.3. Mapping

**Definition 1.11.** Given two sets  $X, Y$ .  $f: X \to Y$  is a mapping called a function if for every element  $x \in X$ , there exists a unique corresponding element  $y \in Y$  such that  $y = f(x)$ .

![Diagram illustrating a mapping (function) from set X to set Y. Set X contains four elements (a red triangle, a yellow rectangle, a green arrow, and a purple square). Set Y contains five elements (a red circle, a blue circle, a green circle, a purple circle, and a yellow circle). Arrows connect each element in X to exactly one element in Y, representing a function.](dc5460bda0c59ba9317dd5ba9b416b0b_img.jpg)

Diagram illustrating a mapping (function) from set X to set Y. Set X contains four elements (a red triangle, a yellow rectangle, a green arrow, and a purple square). Set Y contains five elements (a red circle, a blue circle, a green circle, a purple circle, and a yellow circle). Arrows connect each element in X to exactly one element in Y, representing a function.

**Note.** The given definition can be understood simply as for each  $x \in X$ , there is only one corresponding value  $y \in Y$ , if there are multiple values  $y \in Y$  associated with  $f$  then it is no longer a function.

**Example 1.20.**

(i)

![](c3c305cefbac2e7b13be34ab87054d1e_img.jpg)

Diagram illustrating the mapping  $f(x) = 5x$ . The domain set  $X$  (blue oval) contains elements 1, 2, 3, 4, 5. The codomain set  $Y$  (yellow oval) contains elements 5, 10, 15, 20, 25. Arrows show the mapping: 1 maps to 5, 2 maps to 10, 3 maps to 15, 4 maps to 20, and 5 maps to 25.

$f: \square \to \square$  is a mapping because for every element  $x \in \square$ , there exists a corresponding value  $y \in \square$ . Considering the diagram above, it is an  $y = 5x$ .

(ii)  $X = \{10; 20; 30; 40\}$ ,  $Y = \{15; 25; 35; 45\}$

![](ecb25d766719ce041cf4cc390791a098_img.jpg)

Diagram illustrating a non-mapping. The domain set  $X$  (red oval) contains elements 10, 20, 30, 40. The codomain set  $Y$  (red oval) contains elements 15, 25, 35, 45. Arrows show 10 mapping to 15, 20 mapping to 25, 30 mapping to 35, and 40 mapping to 45. This is a 1-1 correspondence, which is a mapping.

Consider the diagram above  $f: X \to Y$ , which represents a mapping  $x \in X$ . For each element, there exists a unique corresponding element  $y \in Y$ .

(iii)  $f: \square \to \square$  is not a mapping. For example, let  $x = 2 \Rightarrow y^2 = 2 \Rightarrow y = \pm\sqrt{2}$ ,  $x \mapsto y: y^2 = x$

this means that for  $x = 2$ , there are multiple 2 corresponding values  $y$ , which contradicts the definition of a mapping.

## 1.4. Applications in Elementary Education

**Mapping.** Counting is taught to elementary school students as the establishment of a 1-1 correspondence between the elements of a set and the linked elements in a sequence (starting from 1).

The concept of mapping is applied in elementary school problems to find the image of an element through a mapping when evaluating the value of an expression.

**Example 1.21.** Given a mapping  $f: \square \to \square$   $n \mapsto f(n) = 7n + 2$

The content of finding  $f(1)$ ,  $f(2)$ ,  $f(3)$  can be expressed in elementary school as the following problem: Calculate the value of the expression  $7 \times n + 2$  with  $n = 1, 2, 3$ .

The content of finding the image of an element, for example finding  $f^{-1}(9)$  can be expressed in elementary school as the following problem: Find  $x$ :  $7 \times x + 2 = 9$

# Chapter 3. Number Systems

## 3.1. Cardinality - Finite Set

### 3.1.1. Equivalent Set

**Definition 3.1.** Let X and Y be two sets. Two sets X and Y are said to be equivalent (or equinumerous) if there exists a bijection f from X to Y. This is denoted as  $X \sim Y$ .

**Example 3.1.** Let  $X = \{a, b, c, d, e\}$ ;  $Y = \{1, 2, 3, 4, 5\}$ . Sets X and Y are equivalent to each other.

**Example 3.2.** The set of points belonging to line segment AB is equivalent to the set of points belonging to line segment CD.

**Example 3.3.** The set I consisting of real numbers between 0 and 1 ( $I = (0;1)$ ) is equivalent to the set of positive real numbers  $R^+$ . Indeed, the bijection f defined by the rule:  $f(x) = \frac{1}{x}$ .

**Example 3.4.** The set (a; b) of real numbers between a and b and the set (c; d) of real numbers between c and d are equivalent to each other.

**Theorem 3.1.** (Properties of the equivalence relation between sets)

The equivalence relation between sets satisfies the following properties:

(i) **Reflexivity:** Every set A is equivalent to itself.

(ii) **Symmetry:** If A is equivalent to B then B is also equivalent to A.

(iii) **Transitivity:** If A is equivalent to B and B is equivalent to C then A is equivalent to C.

### 3.1.2. Finite and Infinite Sets – Cardinality

**Definition 3.2.** Let A be a set.

a) A is said to be an infinite set if there exists a proper subset B of A such that A and B are equivalent sets.

b) A is said to be a finite set if either A is not an infinite set, or there does not exist any proper subset B of A such that A and B are equivalent sets.

**Example 3.5.** Sets X and Y in Example 3.1 are finite.

**Example 3.6.** The set of points belonging to a line segment is an infinite set.

**Theorem 3.2.** (Properties of a finite set)

(i) Every subset of a finite set is finite.

(ii) The union of two finite sets is a finite set.

(iii) The Cartesian product of two finite sets is a finite set.

*Proof*

(i) Assume A is a finite set and B is a subset of A. Suppose B is an infinite set. Then there exists a proper subset  $B' \subset B$  which is equivalent to B. By definition, there exists a bijection:  $f: B \to B'$ .

Let  $A' = (A \setminus B) \cup B'$ . It is easy to see that  $A'$  is a proper subset of  $A$  and is equivalent to  $A$ . This implies  $A$  is an infinite set. This contradicts the assumption. Hence, we have the statement to prove.

(ii) Assume  $A$  and  $B$  are two finite sets. We will show  $A \cup B$  is also a finite set. First, we consider the case where  $A$  and  $B$  are disjoint.

Suppose  $A \cup B$  is an infinite set. Then there exists an injection  $f$  from  $A \cup B$  into itself but not surjective, i.e.,  $\exists a \in A \cup B, \forall x \in A \cup B: f(x) \neq a$ . We can assume  $a \in A$ .

Let  $A_1 = f(A); B_1 = f(B)$  then  $A \sim A_1, B \sim B_1, A_1 \cap B_1 = \emptyset$ .

Let  $A_2 = A_1 \cap B$  then  $A_2 \subset B \setminus B_1; B_2$

By induction we can easily deduce: the union of a finite collection of finite sets is a finite set.

(iii) Assume  $A$  and  $B$  are two finite sets. We will show  $A \times B$  is also a finite set. We consider the following cases:

a)  $B$  is the empty set. Clearly  $A \times B$  is a finite set.

b)  $B = \{b\}$  then  $A \times B = A \times \{b\}$ . From here it is easy to see  $A \times B$  is a finite set.

c)  $B = \{b_1, b_2, \dots, b_n\}$  then  $A \times B = \bigcup_{i=1}^{n} A_i; A_i = A \times \{b_i\}, i = 1, \dots, n$ .

From here we deduce the statement to prove.

**Definition 3.3.** Two sets  $A$  and  $B$  are said to be equivalent if they have the same cardinality. The cardinality of a set  $A$  is denoted by  $|A|$  or  $\text{Card}A$ .

*Note:*

1. The term "cardinality" describes the concept of "size" or "quantity" for classes of equivalent sets.

2. If  $A=B$  then  $|A|=|B|$ .

**Example 3.7.**

1. $|\{\emptyset\}| = |\{x\}|$ , where  $x$  is any element.
2. The two sets  $X$  and  $Y$  in Example 3.1 have the same cardinality.
3. The set of points belonging to any two line segments has the same cardinality.
4. The interval  $((a, b))$ , consisting of real numbers between  $a$  and  $b$ , and the interval  $(c, d)$ , consisting of real numbers between  $c$  and  $d$ , have the same cardinality.

**Example 3.8.** The set of points on a semicircle with diameter  $AB$  has the same cardinality as the set of points on the diameter  $AB$ .

Indeed, each point  $M$  on segment  $AB$  corresponds to a point  $N$  on the semicircle, as illustrated in the figure below:

![Diagram showing a semicircle with diameter AB. A point N is on the arc, and a perpendicular line segment is dropped from N to the diameter AB, intersecting at M. A small square is drawn at M, indicating a right angle.](967c30813761a8952ecc5e16bf42ea45_img.jpg)

Diagram showing a semicircle with diameter AB. A point N is on the arc, and a perpendicular line segment is dropped from N to the diameter AB, intersecting at M. A small square is drawn at M, indicating a right angle.

## 3.2. Natural Numbers

### 3.2.1. Mathematical Foundations of the Concept of Natural Numbers

#### 3.2.1.1. Concept of Natural Numbers

**Definition 3.4.** The cardinality of a finite set is termed a natural number. We typically use the letters  $a, b, c, \dots$  to represent natural numbers. Thus, if  $A$  is a finite set, its cardinality defines a natural number, represented by  $a=|A|$ .

The set of all natural numbers is denoted by  $\mathbb{N}$ .

##### Example 3.9.

1. $|\emptyset|$  is a natural number, denoted by 0.
2. $|\{\emptyset\}|$  is a natural number, denoted by 1.
3. $|\{\emptyset, \{\emptyset\}\}|$  is a natural number, denoted by 2.

#### 3.2.1.2. The formation of the concept of natural number in elementary mathematics

Natural numbers are taught continuously from Grade 1 to the first semester of Grade 4 in a "concentric and expanding" spiral manner through number ranges: numbers up to 10, up to 100, up to 1000, up to 10,000, up to 100,000, up to numbers with many digits.

The concept of natural number in elementary mathematics is formed based on the cardinality approach combined with Peano's axiomatic inductive method. However, when forming the concept of natural numbers with many digits, the decimal representation of natural numbers is used. In addition, teaching the formation of the concept of natural number is always associated with teaching how to read and write numbers (or the decimal representation of natural numbers), considering it as a "scaffold" for the formation of those numbers. Specifically, as follows:

##### ❖ Formation of the concept of natural numbers within 100

Teaching numbers within 100 in Grade 1 is carried out in the following order:

Numbers 1, 2, 3, 4, 5, 6, 7, 8, 9.

Number 0.

Number 10.

One ten.

Eleven, twelve, thirteen, fourteen, ..., nineteen, twenty.

Round tens.

Two-digit numbers.

Number 100.

Numbers 1, 2, 3, 4, 5, 6, 7, 8, and 9 are formed intuitively based on the cardinality approach. Students observe different groups of objects, count, say the number of those groups according to the teacher, and comment that the groups all have the same number of elements. From there, the teacher introduces the number and the numeral that represents that number, instructing how to write the number.

*Example:* When forming the number 3, the steps are as follows:

- The teacher lets the students observe different groups of objects that have the same number of elements (3 elements), count and say the number of those groups according to the teacher. Students will discover that those groups have special characteristics. The common point is that they all have a quantity of three.

- The teacher introduces: We use the number three to indicate the quantity of each of those object groups.

- The teacher further introduces: the number three is written using the digit 3. Guides on how to write the number 3.

The number "zero" is formed as the cardinality of the empty set based on the "subtract 1" approach. Starting from a group of objects, e.g., a fish tank, we gradually subtract one fish at a time; the quantity of fish decreases until there are no fish left. We say the tank has zero fish, or the number of fish in the tank is 0. Note that in the Grade 1 math curriculum, the number 0 is introduced before learning addition and subtraction operations.

The "zero" number does not appear in the counting operation so it cannot be deduced from the counting operation for its position relative to the learned numbers. The most appropriate method is for the teacher to guide students to understand its common semantic meaning and introduce its symbol as well as its position in the sequence of learned numbers: It is the least natural number and is placed right before the number 1.

##### ❖ *Formation of the concept of two-digit numbers*

Two-digit numbers are formed through the following stages:

- Number 10, one ten:

Number 10 is the first two-digit number students become familiar with. Number 10 is formed based on the cardinality approach. Writing number 10 using two digits 1 and 0 is imposed, not explained at the beginning. Note that when writing ten as 10, the teacher only introduces how to write it but does not yet have to explain the meaning of digits 1 and 0. However, the teacher must clarify the similarities and differences between ten and one ten. Saying "having ten" counting sticks, it can be understood that

these are separate counting sticks; saying "having one ten" counting sticks, students will associate it with the image of 1 bundle of 10 sticks.

Next, students become familiar with the term "one ten", understand that bundling ten sticks into 1 bundle yields one ten, in students' minds a "new unit" called ten appears, visually, students have a bundle of sticks corresponding to ten.

- Numbers from 11 to 19:

Through the visual model of 1 bundle of sticks and separate sticks, students will clearly understand the structure, formation and meaning of digits in writing numbers from 11 to 19. For example, to form number 13: take 1 bundle of sticks (1 ten) and 3 separate sticks, determine that there are "thirteen" sticks; record it using two digits 1 and 3 (digit 1 is written first, then digit 3 is written to the right of digit 1). At this point, students are initially introduced to the decimal structure of two-digit numbers, recognizing the positional value of digits thanks to analyzing tens and ones while forming the writing and reading of numbers.

- Number 20:

Taking 2 bundles (2 tens) yields "twenty" sticks. Record it as 20 (comprising digit 2 and digit 0).

- Similarly to number 20, round tens (less than 100) are formed based on considering bundles of sticks (tens):

Having 3 bundles of sticks (3 tens) yields "thirty", written as 30 (comprising digit 3 and digit 0).

Having 4 bundles of sticks (4 tens) yields "forty", written as 40 (comprising digit 4 and digit 0)...

- Two-digit numbers: The formation is similar when forming numbers from 11 to 19: provide a visual model of bundles of sticks and separate sticks, students will figure out how to write these numbers and become familiar with reading numbers.

For example: To form number 23, the teacher requires students to take 2 bundles of sticks and 3 separate sticks, determine that there are "twenty three" sticks. The teacher guides students to record the number of sticks: write digit 2 and digit 3, digit 2 is written in the tens column and digit 3 is written in the ones column. Read as "twenty three".

For Grade 1 students, only require students at the following levels:

- Students grasp what "one ten" is, through bundling ten sticks into 1 bundle, know that every 10 units make up 1 ten, 10 units = 1 ten.

- When learning two-digit numbers, students work with visual aids: take 6 bundles and 2 separate counting sticks, get 62 counting sticks. At this point students are introduced to the "number of tens" and "number of ones" (having 6 tens and 2 ones).

- Know how to break down a two-digit number into a number of tens and a number of ones: 62 comprises 6 tens and 2 ones.

- Know how to write a two-digit number as the sum of tens and ones:  $62 = 60 + 2$ .

- Know how to write the sum of tens and ones as a two-digit number:  $60 + 2 = 62$ .

The number one hundred (number 100) is formed using the method of applying the Peano axiomatic system to construct the set of natural numbers. Number 100 is formed as the next number of 99: 99 plus 1 is 100.

The number one hundred is written by writing digit 1 first, then writing two digits 0 next to digit 1 (the writing instruction is imposed, does not explain the meaning).

Teachers should understand 100 can also be formed by bundling 10 tens into 1: there are counting sticks, every 10 sticks are bundled into 1 small bundle, there are 10 small bundles, we bundle them into 1 large bundle. At this point, 1 hundred corresponds to this 1 large bundle obtained from 10 small bundles, or in other words, bundling 10 tens into 1 hundred.

In the writing of number one hundred (100) the digit 1 indicates there is 1 hundred, the first digit 0 indicates there are 0 tens, and the last digit 0 indicates there are 0 ones. Number 100 comprises 1 hundred, 0 tens, 0 ones. However, this separate understanding is not necessarily required for elementary students to know.

##### ❖ *Formation of the concept of natural numbers within 1,000*

The concept of natural numbers within 1,000 is formed based on initially becoming familiar with the decimal structure of numbers.

The formation of three-digit numbers in Grade 2 is carried out in a process similar to the formation of two-digit numbers in Grade 1, that is, essentially still determining the cardinality. More specifically: Starting from counting the quantity of groups of objects (here counting small cubes according to the number of hundreds, tens and ones), students form symbols for the corresponding numbers. From there students know how to read numbers, write numbers representing those counted quantities.

To appropriately form the concept of numbers from 100 to 1,000 according to students' comprehension ability, the Grade 2 math textbook has divided it into 5 "small stages" as follows:

- Forming round hundreds.
- Forming round tens from 110 to 200.
- Forming numbers from 101 to 110.
- Forming numbers from 111 to 200.
- Forming three-digit numbers (from 200 to 1,000).

In Grade 2, students are initially introduced to the "decimal structure of numbers" and at the level of knowing how to "write a three-digit number as the sum of hundreds, tens, and ones and vice versa". For example:

$$842 = 800 + 40 + 2$$

$$300 + 60 + 9 = 369$$

**Note:** Students do not yet use the terminology "decimal structure of numbers", but mainly require students to state. For example:

357 comprises 3 hundreds, 5 tens, 7 ones, written as:  $357 = 300 + 50 + 7$ .

307 comprises 3 hundreds, 0 tens, 7 ones, written as:  $307 = 300 + 7$ ...

Or vice versa: The number comprising 6 hundreds, 7 tens, 5 ones is number 675; the number comprising 2 hundreds, 3 ones is number 203...

Through becoming familiar with the "decimal structure" of numbers, students clearly see the difference between number and digit, know the "value" of each digit in a three-digit number. For example: The number 666 comprises 6 hundreds, 6 tens, 6 ones; this number has 3 digits all 6s, but each digit 6 in the position of hundreds, tens, and ones has a different value corresponding to that position:

![](1145fc59efdc7dacc8d3c715d7ff3248_img.jpg)

$666 = 600 + 60 + 6$

6 hundred 6 dozen 6 units

##### ❖ *Formation of the concept of natural numbers within 100,000*

The concept of natural numbers within 100,000 is formed based on the cardinality approach and relying on the decimal representation of numbers as a "scaffold" for forming the number concept.

Teachers can guide students to form the concept of natural numbers within 100,000 through the following steps:

- Students observe, count the quantity of groups of objects (for example, counting cubes according to the number of ten-thousands, thousands, hundreds, tens, and ones) with the support of visual aids.

- Students write and read numbers following the teacher's prompts.

- Students harness symbols about quantity and knowledge of "positional value of digits" learned in Grades 1 and 2 to form symbols about numbers within 100,000.

In the decimal system's way of writing and reading numbers, from right to left, every 3 digits make up a class, starting with the ones class (including ones, tens, and hundreds), then the thousands class (including thousands, ten-thousands, hundred-thousands), and so on.

In Grade 3 Math, students are only taught to write and read numbers with up to 5 digits; thus, from right to left, the first 3 digits belong to the ones class, the remaining digits belong to the thousands class. When teaching, teachers do not introduce classes, do not name classes, but must guide students to write and read numbers consistently with the decimal system's writing and reading.

For writing numbers: At the elementary level, students are not required to write numbers separating digits by class. This is consistent with Vietnam's elementary mathematics teaching tradition and convenient when performing calculations. In Grade 3, when students first become familiar with 5-digit numbers, especially when learning to know and read those numbers, to reduce difficulty for students, the Grade 3 math textbook wrote numbers separating digits by class. For example, number 42,316 is written as: 42 316. When performing calculations or checking students on writing numbers, students are not required to write numbers separated like that.

For reading numbers: Students should be trained to automatically separate digits by class (initially can separate on draft paper, later can separate mentally by sight) then read groups of digits in each class, from left to right.

For example: For number 42316, before reading need to "mentally separate" into 42, 316 then read as: forty-two thousand three hundred

Note:

- Teaching Roman numerals in Grade 3 Math aims to introduce students to other digit forms besides the known digits (0, 1, 2, 3, ..., 9) and only introduces a few commonly used numbers written in Roman numerals such as:

- The numbers marking each hour on the clock face (from I to XII), also the numbers commonly used in major sections of a document (I, II, III, IV, ...).

- Number 20, number 21 for reading or writing about "the 20th century", "the 21st century". No other content should be taught. The level should be just that, do not teach anything more.

Forming the concept of natural numbers with many digits The content of teaching the concept of natural number in Grade 4 includes:

- Reading, writing numbers with six digits, numbers in the millions class.
- Officially naming natural numbers.
- Introducing place value to provide a basis for reading, writing natural numbers with many digits.

- Introducing the characteristics of writing natural numbers in the decimal system: with 10 digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9) we can write all natural numbers; the same digit but written in different positions (in a number) has different values; every ten units in one place value together make up one unit in the immediate higher place value. The concept of natural numbers with six digits, millions is formed in a way similar to numbers with four, five digits in Grade 3.

### 3.2.2. *Mathematical foundations of order relations in the set of natural numbers in elementary school*

#### 3.2.2.1. *Order relations in the set of natural numbers*

**Definition 3.5.** Let  $a$  and  $b$  be two natural numbers, where  $a = |A|$  and  $b = |B|$  Then:

(i) The natural number  $a$  is said to be less than or equal to the natural number  $b$ , denoted by  $a \le b$ , if  $A$  is equivalent to a subset of  $B$ .

(ii)  $a$  is said to be less than  $b$ , denoted by  $a < b$ , if  $a \le b$  and  $a \ne b$ .

(iii)  $a$  is said to be greater than or equal to  $b$ , denoted by  $a \ge b$ , if  $b \le a$ .

(iv)  $a$  is said to be greater than  $b$ , denoted by  $a > b$ , if  $b < a$ .

The relations  $a \le b$  and  $a \ge b$  are termed inequalities, whereas  $a < b$  and  $a > b$  are termed strict inequalities.

We adopt the following lemma by Cantor, without providing a proof:

**Cantor's Lemma:** For any two sets  $A$  and  $B$ , one and only one of the following holds:

(i)  $A$  can be put into a one-to-one correspondence with a subset of  $B$ .

(ii)  $B$  can be put into a one-to-one correspondence with a subset of  $A$ .

If both of the above situations hold simultaneously, then  $A$  is equivalent to  $B$ .

**Theorem 3.3.** (Properties of the order relation on the set of natural numbers)

The order relation  $\le$  on the set  $N$  of natural numbers satisfies the following properties:

(i) **Reflexivity:**  $\forall a \in N$ ,  $a \le a$ .

(ii) **Antisymmetry:**  $\forall a, b \in N$ , if  $a \le b$  and  $b \le a$  then  $a = b$ .

(iii) **Transitivity:**  $\forall a, b, c \in N$ , if  $a \le b$  and  $b \le c$  then  $a \le c$ .

(iv) *There does not exist a natural number  $a$  less than 0, or 0 is the least natural number.*

(v) *There does not exist a greatest natural number, or for every natural number  $a$  there exists a natural number  $b$  greater than  $a$ .*

*Proof.*

(i) This property stems from Theorem 3.2 (i).

(ii) (iii) These derive from the definitions and Cantor's Theorem.

(iv) Suppose there exists a natural number  $a$  such that  $a = |A|$  and  $a < 0 = |0|$ . This would imply that  $A$  is a proper subset of  $\emptyset$ , which is a contradiction.

(v) Let  $a$  be any natural number. It's evident that  $b = a+1$  is greater than  $a$ .

**Corollary.** The set of natural numbers is infinite.

*Proof:* This conclusion is a direct consequence of property (v).

**3.2.2.2. The natural number immediately before, immediately after and consecutive natural numbers**

**Definition 3.6.** Let  $a$  be a natural number,  $a = \text{Card } A$  and  $x$  be an element not belonging to the set  $A$ . We call the natural number  $b = \text{Card } (A \cup \{x\})$  the successor number of  $a$  and denote it by  $a' = b$ .

If  $b$  is the successor of  $a$ , then we call  $a$  the predecessor of  $b$  and denote it as  $'b = a$ .

The two natural numbers  $a$  and  $b$  mentioned above are called two consecutive natural numbers.

**Theorem 3.4.** (Properties of the successor number)

(i) Every natural number  $a$  has a unique successor number.

(ii)  $0$  does not have a predecessor number.

(iii) If  $a$  and  $b$  are two natural numbers such that  $a < b$  then  $a' \le b$ .

*Proof:*

(i) *Existence:* Suppose  $a$  is a natural number,  $a = \text{Card } A$ . By definition: the successor number  $a' = \text{Card } (A \cup \{x\})$  with  $x \notin A$ . Clearly  $\text{Card } (A \cup \{x\})$  is also a natural number.

*Uniqueness:* Suppose  $b$  and  $c$  are two successor numbers of  $a$ , where  $b = \text{Card } (A \cup \{x\})$  and  $c = \text{Card } (A \cup \{y\})$  with  $x, y \notin A$ . Clearly  $A \cup \{x\} \sim A \cup \{y\}$ . Hence  $b = c$ .

(ii) Deduce from Theorem 3.3.

(iii) Suppose  $a$  and  $b$  are two natural numbers such that  $a < b$ , where  $a = \text{Card } A$  and  $b = \text{Card } B$  with  $A \subsetneq B$ . Since  $a < b$  there exists  $x \in B \setminus A$ . Let  $A' = A \cup \{x\}$ . We have:  $a' = \text{Card } A'$  and  $A \subsetneq A' \subseteq B$ , so  $a' \le b$ .

**Consequence** (Discrete property of the set of natural numbers)

Between two natural numbers  $a$  and its successor  $a'$ , there does not exist any other natural number.

*Proof:*

Indeed, suppose there exists a natural number  $b$  such that  $a < b < a'$ . Then  $a' \le b < a'$ . This is absurd. Hence, we have the statement to prove.

*Note:* Let  $0 = \text{Card}\emptyset; 1 = \text{Card}\{\emptyset\}; 2 = 1'; 3 = 2'; 4 = 3'; \dots$  C Continuing this way we obtain the sequence of natural numbers:  $1, 2, 3, 4, \dots, 10, 11, \dots, 100, 101, \dots$

**Definition 3.7:** Let  $A$  be a subset of the set  $N$  of natural numbers. We say that:

a)  $A$  is bounded above (or below) if there exists a natural number  $M$  (or  $m$ ) such that:

$$a \le M \quad (a \ge m), \quad \forall a \in A$$

If  $A$  is simultaneously bounded above and below then we call  $A$  a bounded set.

b) The natural number  $M$  (or  $m$ ) is called the greatest (or least) number of  $A$ , if  $M \in A$  ( $m \in A$ ) and  $a \le M \quad (a \ge m), \quad \forall a \in A$ .

We accept the following property of the set of natural numbers:

*Every upper bounded non-empty subset of the set of natural numbers has the greatest number.*

*Every non-empty subset of the set of natural numbers has a least number.*

#### 3.2.2.3. Formation of order relations in the system of natural numbers in elementary school

The content of teaching order relations in the system of natural numbers in elementary school includes:

- The relations "less than", "equal to", "more than" between the quantities of two finite sets of elements.

- The relations "less than", "equal to", "greater than" between two natural numbers. - Properties of the relations "less than", "equal to", "greater than" between two natural numbers.

- Methods of comparing natural numbers based on establishing 1-to-1 correspondence, number lines, counting; comparison algorithm according to dictionary order.

- Predecessor, successor; properties of predecessor, successor.

- The greatest and least number of a finite group of natural numbers.

- Arrange the natural numbers from least to greatest (from greatest to least).

- Introduce the sequence of natural numbers and characteristics of the sequence of natural numbers.

The ordering relationship in the set of natural numbers in elementary school is built on the basis of comparing two numbers, that is, comparing the cardinality of two sets. To compare two natural numbers  $a$  and  $b$ , students will compare the cardinality of two sets  $A$  and  $B$ , where  $a = \text{Card } A$ ,  $b = \text{Card } B$  (by placing  $1 - 1$  between the parts respectively). elements of set  $A$  with elements of set  $B$ . If set  $A$  has less quantity than set  $B$  then  $a < b$ ; If set  $A$  has the same quantity as set  $B$ , then  $a = b$ ; If set  $A$  has more quantity than set  $B$  then  $a > b$ . However, the above method mainly only applies to one-digit natural numbers. For natural numbers with many digits, the following methods can be used to compare two natural numbers:

- Comparison based on the number line: the previous number on the number line is the smaller number;

- Comparison is based on counting: while counting, whichever number is counted first is smaller.

- Comparison is based on the lexicographical comparison algorithm. This is the method mainly used to compare two multi-digit natural numbers:

"Step 1. Compare the number of digits of the two numbers: the number with fewer digits is smaller; the number with more digits is larger. Step 2. If the two numbers have an equal number of digits, compare each pair of digits in the same position, starting from the left to the right, until there is a pair of digits that differ. The number with the smaller digit is smaller, and the number with the larger digit is larger. If the two numbers have the same number of digits and every pair of digits in the same position are identical, then the two numbers are equal."

*Teaching comparison of natural numbers is divided into the following steps:*

*Step 1: Compare numbers from 1 to 10.*

Before comparing numbers, students become familiar with the "more, less" relationship (this relationship is determined by placing a 1-1 correspondence between two groups of objects without using letters). number. Next, compare the numbers, using the words "greater than", "equal", and using the comparison symbols  $>$ ,  $<$  and  $=$ . *Example:* The drawing on the right has 2 triangles.

![Diagram illustrating the comparison of two groups of objects. On the left, there are two triangles (one shaded, one unshaded). On the right, there are four triangles (two shaded, two unshaded). Lines connect the corresponding triangles, showing that the group on the left has fewer elements than the group on the right.](e7ca609b5cf25af4feb977a951796348_img.jpg)

Diagram illustrating the comparison of two groups of objects. On the left, there are two triangles (one shaded, one unshaded). On the right, there are four triangles (two shaded, two unshaded). Lines connect the corresponding triangles, showing that the group on the left has fewer elements than the group on the right.

The drawing on the left has 3 triangles, number of shapes

The number of triangles on the left is less than the number

of triangles on the right; So we have 2 less than 3, written as  $2 < 3$ .

The drawing on the right has 4 squares,

The picture on the left has 4 squares,

The number of squares on the left is equal to the number square on the right; so we have 4 equals 4, written as  $4 = 4$ .

Note that any two different numbers can be compared together.

*Step 2:* So compare two-digit numbers.

*Example:* Compare 62 with 65.

- The teacher asks students to take 62 sticks (6 bundles and 2 loose sticks), take 65 sticks (6 bundles and 5 loose sticks).

- Teacher has students compare the numbers of two groups of sticks (students will comment: both groups have the same 6 tens, there are  $2 < 5$  so the first group is less than the second group. So  $62 < 65$  or  $65 > 62$ ).

*Example:* Compare 63 and 58.

- The teacher also lets students use counting sticks to represent the numbers 63 and 58.

- Comment and compare the numbers of groups of rods as in step 1, from there draw the conclusion  $63 > 58$  or  $58 < 63$ .

The teacher does not state general comparison rules for students (because the concepts of tens and units are not introduced, and the introduction of general and complex rules is not appropriate for the age of 1st grade students). )

*Step 3:* So Compare multi-digit numbers based on the lexicographical comparison algorithm.

*Example:* Compare numbers 234 and 235.

- First represent the numbers in squares:

![Diagram showing a 10x10 grid (representing 100) and 3 vertical rods (representing 30). The grid is tilted, and the rods are upright. This represents the number 234.](fb7418caf56a81764ec7e3a8969661d1_img.jpg)

Diagram showing a 10x10 grid (representing 100) and 3 vertical rods (representing 30). The grid is tilted, and the rods are upright. This represents the number 234.

234

![Diagram showing a 10x10 grid (representing 100) and 5 vertical rods (representing 50). The grid is tilted, and the rods are upright. This represents the number 235.](3eca3a6c8f06cf3f6dc28be22545475c_img.jpg)

Diagram showing a 10x10 grid (representing 100) and 5 vertical rods (representing 50). The grid is tilted, and the rods are upright. This represents the number 235.

235

- Compare the number of squares in the two pictures (according to 1-1 correspondence):

Each picture has 2 hundred squares, 3 dozen squares. The picture on the left has 4 more squares, the picture on the right has 5 more squares, but  $4 < 5$ . Thus, the number of squares in the left picture is less than the number of squares in the right picture. From there:  $234 < 235$ .

- Finally, we can comment: the two numbers 234 and 235 have: in the hundreds place the same digit 2; in the tens place there is the same digit 3; In the units place we have  $4 < 5$ . So  $234 < 235$ .

### 3.2.3. *Mathematical foundations of arithmetic operations in the set of natural numbers in elementary school*

#### 3.2.3.1. *Addition and multiplication*

**Lemma 1:** For any two natural numbers  $a$  and  $b$  there always exist two finite disjoint sets  $A$  and  $B$  such that  $a = \text{Card } A$  and  $b = \text{Card } B$ .

*Proof.* Suppose  $a$  and  $b$  are two natural numbers, where  $a = \text{Card } A$  and  $b = \text{Card } B$  with  $A$  and  $B$  finite sets.

If  $A \cap B = \emptyset$  then we have the statement to prove.

Choose two arbitrary distinct elements  $x \neq y$ , let  $A' = A \times \{x\}$ ;  $B' = B \times \{y\}$  then  $A'$  and  $B'$  are both finite sets and  $A' \sim A$ ;  $B' \sim B$  so  $a = \text{Card } A'$  and  $b = \text{Card } B'$ . Thus, two sets  $A'$  and  $B'$  satisfy the requirement.

**Lemma 2:** Suppose  $A$ ,  $B$ ,  $A'$  and  $B'$  are finite sets such that

$$A \sim A', B \sim B'; A \cap B = A' \cap B' = \emptyset.$$

Then:

(i)  $A \cup B \sim A' \cup B'$ ;  
(ii)  $A \times B \sim A' \times B'$ .

*Proof.* Simple.

**Definition 3.8:** Let  $a$  and  $b$  be two natural numbers, where  $a = \text{Card } A$  and  $b = \text{Card } B$  with  $A$  and  $B$  being two disjoint finite sets. We call:

a) The sum of two natural numbers  $a$  and  $b$  is a natural number  $c$ , denoted  $c = a + b$ , in which  $c = \text{Card } A \cup B$ .

The rule for corresponding each pair of natural numbers  $a$ ,  $b$  with a natural number  $c$  mentioned above is called addition of natural numbers, in which  $a$  and  $b$  are called terms,  $s$  is called the sum and  $a + b$  also called total.

b) The product of two natural numbers  $a$  and  $b$  is a natural number  $p$ , denoted  $p = axb$  (or  $ab$  or  $ab$ ), in which  $p = \text{Card } A \times B$ .

The rule for corresponding each pair of natural numbers  $a$ ,  $b$  with a natural number  $p$  mentioned above is called *multiplication of natural numbers*, in which  $a$ ,  $b$  are called factors,  $p$  is called product and  $ab$  is also called product.

**Remark:** From the definition, Theorem 3.2 and Lemmas 1, 2 we can easily deduce:

(i) For each pair of natural numbers  $a$ ,  $b$  there exists a unique natural number  $c$  that is their sum.

(ii) For each pair of natural numbers  $a$ ,  $b$  there exists a unique natural number  $p$  that is their product.

**Theorem 3.5:** (Properties of addition and multiplication)

(i) The Commutative property: For any natural numbers  $a$  and  $b$ ,  $a + b = b + a$ ;  $a \cdot b = b \cdot a$ .

(ii) Associative property: For any natural numbers  $a$ ,  $b$  and  $c$ , we have:

$$a + (b + c) = (a + b) + c; a \cdot (b \cdot c) = (a \cdot b) \cdot c$$

(iii) Distributive property: For any natural numbers  $a$ ,  $b$ ,  $c$  we have:

$$\begin{aligned}a \cdot (b + c) &= a \cdot b + a \cdot c \\(b + c) \cdot a &= b \cdot a + c \cdot a\end{aligned}$$

(iv) Neutral element: For any natural number  $a$ ,  $a + 0 = 0 + a = a$ ;  $a \cdot 1 = 1 \cdot a = a$ .

(v) Property of the successor: For any natural number  $a$ ,  $a' = a + 1$ .

*Proof:* (i); (ii) and (iii) follow directly from the definition of addition, multiplication and the commutative, associative, distributive properties of operations on sets.

(i) Clearly:  $A \cup \emptyset \sim A$ ;  $A \times \{x\} \sim A$ . From here the statement follows.

(ii) By definition the successor  $a' = A \cup \{x\}$  where  $x \notin A$ . Hence  $a + 1 = \text{Card}(A \cup \{x\}) = a'$ .

*Note:* For simplicity, we assume:

(i) Write  $a + b + c$  instead of  $a + (b + c)$  or  $(a + b) + c$ ;

(ii) Write  $a \cdot b \cdot c$  instead of  $a \cdot (b \cdot c)$  or  $(a \cdot b) \cdot c$ .

**Theorem 3.6:** (Monotonicity of addition and multiplication)

For any natural numbers  $a$ ,  $b$ ,  $c$ , we have:

$$(i) a \le b \rightarrow a + c \le b + c; a \cdot c \le b \cdot c;$$

(ii)  $a + c = b + c \rightarrow a = b$ : Law of simplicity of addition.

$a \cdot c = b \cdot c$ ;  $c \neq 0 \rightarrow a = b$ : Law of simplification of multiplication.

(iii)  $a + c < b + c \rightarrow a < b$ ;  $a \cdot c < b \cdot c \rightarrow a < b$ .

*Proof:*

(i) Let  $a = \text{Card } A$ ;  $b = \text{Card } B$ ;  $c = \text{Card } C$ , where  $A$ ,  $B$ ,  $C$  are disjoint finite sets. If  $a = b$  then clearly  $a + c = b + c$ .

If  $a < b$ , we can consider  $A \subset B$ ,  $A \neq B$ . Then  $A \cup C \subset B \cup C$ ,  $A \cup C \neq B \cup C$ . From here  $a + c < b + c$  follows.

Similarly for multiplication.

(ii) Assume  $a + c = b + c$  and  $a < b$ . By the Proof above,  $a + c < b + c$ . This contradicts the assumption. Hence  $a = b$ .

Similarly for multiplication.

(iii) Deduce from (i).

**Remark:** From the definition it follows that addition and multiplication of natural numbers are always possible.

#### 3.2.3.2. Subtraction

**Theorem 3.7:** (On existence and uniqueness of difference of two natural numbers)

Suppose  $a$  and  $b$  be two natural numbers,  $b \le a$ . Then there exists a unique natural number  $c$  such that  $b + c = a$ .

*Proof*

Let  $A$ ,  $B$  be disjoint finite sets with  $a = \text{Card}A$ ;  $b = \text{Card}B$ ;  $B \subset A$ . Let  $C = A \setminus B$  and  $c = \text{Card} C$ . Clearly  $A = B \cup C$ ;  $B \cap C = \emptyset$  và  $a = b + c$ .

**Definition 3.9:** Let  $a$  and  $b$  be two natural numbers,  $b \le a$ . We call the natural number  $c$  in Theorem 3.7 the difference of  $a$  and  $b$ , denoted  $c = a - b$ .

The rule that associates each pair of natural numbers  $a$ ,  $b$  with a natural number  $c$  as above is called subtraction of natural numbers.

**Theorem 3.8:** (Properties of subtraction)

For any natural numbers  $a$ ,  $b$ ,  $c$  we have:  $a \cdot (b - c) = a \cdot b - a \cdot c$  if either side is significant.

*Proof:*

Suppose  $b - c = d$ . It follows that  $b = c + d$ . We have:

$$ab = a(c + d) = ac + ad$$

From here, deduce  $a \cdot (b - c) = ad = ab - ac$

**Remark:** From the definition it follows that subtraction of natural numbers is not always possible.

#### 3.2.3.3. Division

**Definition 3.10:** (Divisibility relation and division in the set of natural numbers)

Let  $a$  and  $b$  be two natural numbers, where  $b \neq 0$ . We say that  $a$  is divisible by  $b$ , denoted by  $a:b$  (or  $b$  divides  $a$ , denoted by  $b|a$ ) if there exists a natural number  $q$  such that:  $a = bq$ .

In this case we will call  $a$  is the dividend,  $b$  is the divisor and  $q$  is the quotient of dividing  $a$  by  $b$  and written as:  $a : b = q$  or  $q = \frac{a}{b}$ .

The rule for corresponding each pair of natural numbers  $a$ ,  $b$  with a natural number  $q$  mentioned above is called *division of natural numbers*.

The rule that associates each pair of natural numbers  $a$ ,  $b$  with a natural number  $q$  as above is called division of natural numbers.

**Example 3.10.**

15 divides 3 (or 3 divides 15), because  $15 = 3 \cdot 5$ . We write:  $15 : 3 = 5$

132 divides 12 (or 12 divides 132), because  $132 = 12 \cdot 11$ . We write:  $132 : 12 = 11$ .

**Theorem 3.9.** (Properties of divisibility)

(i) For any natural number  $a \neq 0$ ,  $a|a$ .

(ii) If  $a|b$  and  $b|a$  then  $a = b$ .

(iii) If  $a|b$  and  $b|c$  then  $a|c$ .

(iv) 0 divides every natural number khác 0.

(v) Every natural number is divisible by 1.

*Proof*

(i) Clearly, because  $a = a \cdot 1$ .

(ii) Assume  $a|b$  and  $b|a$ . Then there exist  $q, q' \in \mathbb{N}$  such that  $a = b \cdot q$  and  $b = a \cdot q'$ . Substituting we get  $a = a \cdot q \cdot q'$ . Hence  $q \cdot q' = 1$  or  $q = q' = 1$ . Substituting we get  $a = b$ .

(iii) Assume  $a|b$  and  $b|c$ . Then there exist  $q, q' \in \mathbb{N}$  such that  $a = b \cdot q$  and  $b = c \cdot q'$ . Substituting we get  $a = c \cdot q \cdot q'$ . Hence the statement follows.

(iv) Clearly,  $0 = b \cdot 0$ .

(v) Clearly,  $a = 1 \cdot a$ .

**Remark:** Each division of two natural numbers has at most one quotient.

Indeed, assume  $a$  and  $b$  are two natural numbers and  $a : b = q$ ,  $a : b = q'$ . By definition we have:  $a = b \cdot q$  and  $a = b \cdot q'$ . Hence  $b \cdot q = b \cdot q'$ . Since  $b \neq 0$ ,  $q = q'$ .

**Theorem 3.10:** (On division with remainder in the set of natural numbers)

Let  $a$  and  $b$  be two natural numbers, where  $b \neq 0$ . Then there exists a unique pair of natural numbers  $q$  and  $r$  such that:  $a = bq + r$ ;  $0 \le r < b$ .

*Proof*

a) Existence: Let  $a$  and  $b$  be two natural numbers,  $b \neq 0$ .

Let  $A = \{m : bm \le a\}$ . Clearly the set  $A$  is non-empty and bounded above so it has a greatest element. Call this greatest element  $q$  and let  $r = a - bq$ . Clearly:  $a = bq + r$ ;  $0 \le r < b$ .

b) Uniqueness: Assume there exist  $q_1, q_2, r_1, r_2 \in \mathbb{N}$ :  $a = bq_1 + r_1 = bq_2 + r_2$ ,  $0 \le r_1, r_2 < b$ . Assume  $q_1 \le q_2$ . Then there exists a natural number  $m$  such that  $q_2 = q_1 + m$ .

We have:  $bq_2 + r_2 = b(q_1 + m) + r_2 = bq_1 + bm + r_2 = bq_1 + r_1$ .

Hence  $bm + r_2 = r_1$ . Since  $r_1 < b$  this happens if and only if  $m = 0$

So  $q_1 = q_2$  and  $r_1 = r_2$ . We have the statement to prove.

**Definition 3.11:** (Division with remainder)

Let  $a$  and  $b$  be two natural numbers, where  $b \neq 0$ ,  $q$  and  $r$  be the two numbers stated in the theorem above. We will call  $q$  the approximate quotient (or incomplete quotient) and  $r$  the remainder in dividing  $a$  by  $b$ .

The rule that associates each pair of natural numbers  $a$ ,  $b$  with a pair of natural numbers  $q$  and  $r$  as above is called division with remainder in the set of natural numbers. *Note.* From the definition we see that division is a special case of division with remainder (when the remainder is 0).

**Example 3.11.**

17 : 5 = 3 (remainder 2); 67 : 4 = 16 (remainder 3); 131 : 12 = 11 (remainder 11).

#### 3.2.3.4. Formation of arithmetic operations in elementary school

There are four core contents of teaching arithmetic operations on the set of natural numbers in elementary school:

Form operations according to the language of set theory.

- “Everyday” languages that indicate those operations in word problems and in everyday human life.

- Algorithms to perform operations and dividing algorithms into practical manipulations.

- Properties of operations to form basic algebraic structures of number sets.

- To clarify those contents, we will present them according to each operation.

##### a) Forming addition

###### ❖ Forming addition according to the language of set theory

Addition of two natural numbers is formed based on the union of two sets. Specifically, the sum of two numbers  $a$  and  $b$  is considered as the cardinality of the union of two disjoint sets  $A$  and  $B$ , where the cardinalities of  $A$  and  $B$  are  $a$  and  $b$  respectively. With this understanding, textbooks have formed for students the concept of addition as follows:

Students perform the manipulation of “combining” two groups of objects then count the total number of objects in the two groups. For example, combining 3 counting sticks with 1 counting stick, obtaining 4 counting sticks. Recording this activity with the addition  $3 + 1 = 4$ . Then, to reinforce students’ cognition, having them observe in a drawing: each group of objects is separated by a horizontal line, then the two groups are surrounded by a closed curve (image of a Venn diagram).

###### ❖ Language describing addition operation in word problems

- Addition with the meaning of “combining”.

Example: Ha has 24 counting sticks, Lan has 14 counting sticks. How many counting sticks do the two friends have in total?

- Addition with the meaning of “adding to”.

Example: Initially the class had 6 students, then 3 more students joined. How many students are in the class now?

Example: An had 3 candies. Her dad gave her 2 more candies. How many candies does An have now?

- Addition with the meaning of “more than, less than”.

Example: An has 8 candies, Binh has 2 more candies than An. How many candies does Binh have?

Example: An has 12 candies, An has 2 less candies than Binh. How many candies does Binh have?

As mentioned above, when building the set of natural numbers, elementary math textbooks combined forming natural number as the cardinal number of sets with the axiom “counting plus 1”. Therefore, essentially students have been preliminarily prepared for learning addition.

###### ❖ *Algorithm for performing addition*

Regardless of whether the operation is written horizontally or vertically, the basic technique is still applying the addition table within 10 (addition without carrying) or the addition table within 20 (addition with carrying) to find the result.

Teaching addition algorithm is usually demonstrated through 3 “stages”:

- Stage 1: Introducing the operation and basic principles leading to the algorithm, to help students initially understand why there is such an algorithm or “calculation rule”. In textbooks, the “basis of the algorithm” is expressed through illustrative manipulations of visual aids.

- Stage 2: Forming the algorithm comprising 2 steps: Placing digits and calculating.

Example:

$$\begin{array}{r} 49 \\ + 25 \\ \hline 74 \end{array}$$

- 9 plus 5 equals 14, write 4, remember 1.
- 4 plus 2 equals 6, add 1 equals 7, write 7.

- Stage 3: Practicing applying the algorithm in problems of direct calculation and slightly more advanced is solving word problems involving the operation.

###### ❖ *Properties of addition to form basic algebraic structures of number sets.*

The set of natural numbers together with addition is a commutative monoid.

(i) Commutative property:  $a + b = b + a$ , for all natural numbers  $a$  and  $b$ .

(ii) Associative property:  $(a + b) + c = a + (b + c)$ , for all natural numbers  $a$ ,  $b$  and  $c$ .

(iii) Existence of neutral element 0:  $a + 0 = 0 + a = a$ , for all natural numbers  $a$ .

(iv) Since elementary students have not learned negative numbers yet, the elementary math curriculum does not mention the opposite of an element in the set of natural numbers.

(v) In addition, students are also introduced to the distributive property between addition and multiplication:  $(a+b) \cdot c = ab + ac$ . This aims to prepare for forming the ring of integers later.

These properties have been officially taught and used during the systematization and summary of natural numbers and operations on natural numbers in Semester I of Grade 4 Math. In the elementary math curriculum, from Grade 1, when teaching each operation, we pay attention to introducing the properties of that operation (commutativity, associativity, properties of 0, properties of 1...) as separate phenomena, so that in Grade 4 the textbook can summarize each property into rules: commutative property, associative property, rule of multiplying a number by a sum or

difference, rule of dividing a sum (or difference or product or quotient) by a number, properties of 0, 1, ... For example:

- When teaching addition in tables, have students observe:

$$2 + 3 = 3 + 2 (= 5); 3 + 6 = 6 + 3 (= 9)$$

- When teaching addition of numbers with 2, 3 or more digits, have students observe:

| a     | 20             | 350               | 1208                 |
|-------|----------------|-------------------|----------------------|
| b     | 30             | 250               | 2764                 |
| a + b | $20 + 30 = 50$ | $350 + 250 = 600$ | $1208 + 2764 = 3972$ |
| b + a | $30 + 20 = 50$ | $250 + 350 = 600$ | $2764 + 1208 = 3972$ |

From there derive the commutative property of addition: **The sum does not change when the addends are switched.**

Similarly, we introduce the associative property of addition by having students observe:

| a  | b  | c  | $(a + b) + c$          | $a + (b + c)$          |
|----|----|----|------------------------|------------------------|
| 5  | 4  | 6  | $(5 + 4) + 6 = 15$     | $5 + (4 + 6) = 15$     |
| 35 | 15 | 20 | $(35 + 15) + 20 = 70$  | $35 + (15 + 20) = 70$  |
| 28 | 49 | 51 | $(28 + 49) + 51 = 128$ | $28 + (49 + 51) = 128$ |

From there derive the associative property of addition: **When adding a sum to a number, we can add the first number to the sum of the two remaining numbers.**

- In Grade 4 Math textbook, from the observation:

$$\begin{aligned}4 \times (3 + 5) &= 4 \times 8 = 32 \\4 \times 3 + 4 \times 5 &= 12 + 20 = 32\end{aligned}$$

Derive the rule: **When multiplying a number by a sum, we can multiply that number by each addend of the sum then add the results.**

Similarly, we introduce other properties.

##### b) *Formation of subtraction*

###### ❖ *Forming subtraction according to the language of set theory*

Subtraction of two natural numbers is presented based on the difference of two cardinal numbers. Specifically as follows: Let a, b be two natural numbers, a is the cardinality of set A, b is the cardinality of set B, A is a subset of B, the difference of b and a is the cardinality of set B\A.

With this understanding, textbooks have formed for students the concept of subtraction as follows:

Students perform the manipulation of “separating” a group of objects from a given set of objects, then count the remaining objects. For example, originally there is a group of 3 counting sticks, separating 1 stick, the remaining part has two sticks. Recording this activity with the subtraction  $3 - 1 = 2$ . Then, to reinforce cognition, have students

observe the drawing in the textbook: the given set is surrounded by an outer closed curve (with blue background). Each subset is surrounded by a smaller curve with white background. The given set comprises 3 dots. The subtractions 3 - 1 and 3 - 2 correspond to separating parts comprising 1 or 2 dots.

###### ❖ *Language describing subtraction operation in word problems.*

- Subtraction with the meaning of “separating”.

Example. The class has 9 students, of which 5 are girls. How many boys are in the class?

- Subtraction with the meaning of “removing, finding remainder”.

Example. Initially there were two bees on the flower, then one bee flew away. How many bees are left?

Example. There were 8 birds on the tree, then two flew away. How many birds are left on the tree?

- Subtraction with the meaning of “less than or more than”.

Example. An has 8 candies, Binh has 2 less candies than An. How many candies does Binh have?

Example. An has 8 candies, An has 2 more candies than Binh. How many candies does Binh have?

###### ❖ *Algorithm for performing subtraction.*

“Vertical subtraction” algorithm:

Step 1: Arrange digits vertically so corresponding digits are in the same columns.

Step 2: Subtract from right to left.

Regardless of whether the operation is written horizontally or vertically, the basic technique is still applying the subtraction table within 10 (subtraction without borrowing) or the subtraction table within 20 (subtraction with borrowing) to find the result.

Teaching the subtraction algorithm is usually demonstrated through 3 “stages”.

- Stage 1: Introducing the operation and basic principles leading to the algorithm, to help students initially understand why there is such an algorithm or “calculation rule”. In textbooks, the “basis of the algorithm” is expressed through illustrative manipulations of visual aids.

- Stage 2: Forming the 2-step algorithm: Arranging digits and calculating.

Example

$$\begin{array}{r} 49 \\ - 25 \\ \hline 24 \end{array}$$

- 9 minus 5 equals 4, write 4.
- - 4 minus 2 equals 2, write 2.

- Stage 3: Practicing applying the algorithm in problems of direct calculation and slightly more advanced is solving word problems involving the operation.

###### ❖ *Properties of subtraction to form basic algebraic structures of number sets.*

- Distributive property of multiplication over subtraction: For any natural numbers  $a$ ,  $b$ ,  $c$  such that  $c \le b$ , we have  $a(b - c) = ab - ac$  and  $(b - c)a = ba - ca$ .

- Subtraction can be considered the inverse operation of addition: If  $a + c = b$  then  $b - c = a$  and  $b - a = c$  for all natural numbers  $a$ ,  $b$ ,  $c$ .

##### c) *Formation of multiplication*

###### ❖ *Forming multiplication according to the language of set theory*

Generally, there are two main ways to form multiplication of natural numbers:

- Multiplication is formed from addition in the corresponding additive monoid.

- Multiplication is formed using set theory.

Multiplication of two natural numbers  $a$  and  $b$  is defined as the addition of equal addends: with two natural numbers  $a$  and  $b$ , the addition  $a + a + \dots + a$  ( $b$  times) is written as  $a \times b$  and called the multiplication of  $a$  by  $b$ . The numbers  $a$ ,  $b$  are called factors, the result of multiplying  $a \times b$  is called the product.

This way of presenting the definition of multiplication, although not following the logical development of the concept, is pedagogically convenient because it suits the characteristics of elementary students' cognition and life experience. However, with this definition of multiplication, we need to agree:

$$a \times 0 = 0, a \times 1 = a.$$

The disadvantage of the above definition of multiplication is that the roles of the factors are not equal and multiplication is only like a substitution for addition of equal addends, not a new operation.

We can understand the definition of multiplying two natural numbers  $a$  and  $b$  as follows: take the set  $A$  with  $a$  elements, the set  $B$  with  $b$  elements, form the Cartesian product of the two sets, denoted  $A \times B$ , meaning:  $A \times B = \{(a,b) | a \in A, b \in B\}$ , then count the number of elements of the set  $A \times B$  to obtain the result of multiplying  $a \times b$ . When defining multiplication as the Cartesian product of two sets, we need to agree:  $A \times \emptyset = \emptyset$ . We can use this definition to describe multiplication.

In Grade 2 Math, multiplication is built from “sum of equal addends”, for example:

$$2 + 2 + 2 + 2 = 8$$

$$\text{or } 2 \times 4 = 8$$

(2 is the addend, 4 is number of addends)

$$\text{Or } 4 + 4 = 8$$

$$\text{Or } 4 \times 2 = 8$$

(4 is the addend, 2 is number of addends).

###### ❖ *Language describing multiplication operation in word problems*

- Multiplication with the meaning of “sum of equal parts”.

Example. Each chicken has two legs. How many legs do 6 chickens have?

- Multiplication with the meaning of “multiplying the quantity”.

Example. The child picked 7 oranges, the mother picked 5 times the child's number of oranges. How many oranges did the mother pick?

###### ❖ Algorithm for performing multiplication

Regardless of whether the operation is written horizontally or vertically, the basic technique is still applying the multiplication table to find the result.

Multiplying numbers with multiple digits is reduced to multiplying single digit numbers using the multiplication table and carrying rules. Multiplying numbers with multiple digits is done as follows:

- Separate the decimal place values of the factors.
- Multiply each digit of the first factor with the digits of the second factor to obtain partial products.
- Add the partial products.
- The result of adding the partial products is the product of the given multiplication.

###### ❖ Properties of multiplication to form basic algebraic structures of number sets

The set of natural numbers together with multiplication is a commutative monoid.

1. Commutative property:  $ab = ba$  for all natural numbers a and b.
2. Associative property:  $(ab)c = a(bc)$  for all natural numbers a, b and c.
3. Existence of identity element 1:  $a1 = a$  for all natural numbers a.
4. In addition, students are introduced to the distributive property between addition and multiplication:  $(a+b)c = ab + ac$ . This aims to prepare for forming the ring of integers later.

These properties have been officially taught and used during the systematization and summary of natural numbers and operations on natural numbers in Semester I of Grade 4 Math.

##### d) Formation of division

###### ❖ Forming division according to the language of set theory

In general, division is built from multiplication (as the inverse operation of multiplication) in corresponding multiplicative monoids, for example:

We have:  $3 \times 2 = 6$

$6 : 2 = 3$

$6 : 3 = 2$

###### ❖ Language describing division in word problems

- Division with the meaning of “dividing equally”.

Example: There are 12 candies divided equally among 2 friends. How many candies does each friend get?

- Division with the meaning of “dividing into groups”.

**Example:** There are 20 students lined up in rows, with 2 students per row. How many rows are there?

❖ *Algorithm for performing division.*

Regardless of whether the operation is written horizontally or vertically, the basic technique is still applying the division table to find the result.

❖ *Properties of division to form basic algebraic structures of number sets.*

Division of natural numbers has the following properties:

### 3.2.4. *Theory of divisibility in the set of natural numbers*

#### 3.2.4.1. *Greatest common divisor*

**Definition 3.12:** Given  $a$  and  $b$  are natural numbers,  $b \neq 0$ . We say:

a)  $b$  is a divisor of  $a$  if  $a$  is divisible by  $b$ .

If  $b$  is a divisor of  $a$  then we also say  $a$  is a multiple of  $b$ .

b) The natural number  $d$  is a common divisor of  $a$  and  $b$ , if  $d$  is simultaneously a divisor of  $a$  and  $b$ .

From the definition we can easily deduce:

- The set  $U(a)$  of divisors of  $a$  is never empty and bounded by  $a$ , since clearly  $1 \in U(a)$ .

- The set  $UC(a, b) = U(a) \cap U(b)$  of common divisors of  $a$  and  $b$  is never empty and bounded above.

**Example 3.12.**

$$U(12) = \{1, 2, 3, 4, 6, 12\}$$

$$UC(12, 18) = \{1, 2, 3, 6\}$$

**Definition 3.13:** Given  $a$  and  $b$  are two natural numbers, at least one of which is nonzero. We call the greatest number among the common divisors of the two numbers  $a$ ,  $b$  the greatest common divisor. We denote it by  $d = (a, b)$  (or  $d = \text{GCD}(a, b)$ ).

**Remark:** Clearly: two given nonzero natural numbers always have a unique greatest common divisor.

**Example 3.13.**

$$(12, 18) = 6 \quad (15, 60) = 15 \quad (8, 15) = 1$$

*Note:* Similarly, we define: The greatest common divisor of  $n$  natural numbers not all zero is the greatest number among the common divisors of those  $n$  numbers.

**Example 3.14.**

$$(12, 18, 42) = 6 \quad (8, 24, 72) = 8 \quad (18, 12, 25) = 1$$

#### 3.2.4.2. *Properties of the greatest common divisor*

**Theorem 3.11:** (On the properties of the greatest common divisor)

(i) If  $a$  is divisible by  $b$  then  $(a, b) = b$ ;

(ii) If  $a : b = q$  (remainder  $r$ ) then  $(a, b) = (b, r)$ .

*Proof:*

(i) Simple.

(ii) We prove  $UC(a, b) = UC(b, r)$ .

Indeed, if  $m$  is a common divisor of  $a$  and  $b$  then  $m$  is also a divisor of  $r = a - bq$ . Hence  $m$  is a common divisor of  $b$  and  $r$ .

Conversely, suppose  $m$  is a common divisor of  $b$  and  $r$ . Then  $m$  is also a divisor of  $a = bq + r$ .

Hence  $m$  is a common divisor of  $a$  and  $b$ . We have what we need to prove.

**Theorem 3.12:** (On the Euclidean algorithm)

To find the greatest common divisor of two natural numbers, proceed as follows:

a) Divide the greater number by the smaller. If the division is without remainder then the smaller number will be the greatest common divisor of the two given numbers;  
b) If there is a remainder, divide the smaller number by the first remainder and continue like that until the division is without remainder, stop. The last divisor in the division without remainder will be the greatest common divisor of the two given numbers.

*Proof:*

Suppose  $a$  and  $b$  are two natural numbers. If  $a$  is divisible by  $b$  then by Theorem 3.11:  $b = (a, b)$ .

Suppose  $a = bq_1 + r_1$ . We perform successive divisions:

$$b = r_1 q_2 + r_2$$

$$r_1 = r_2 q_3 + r_3$$

...

After a number of steps (at most  $b$  steps) the division will have no remainder:

$$r_{n-1} = r_n q_{n+1}$$

Since  $r_1 > r_2 > r_3 > \dots > r_{n-1} > r_n$ .

By Theorem 3.11,  $(a; b) = (b; r_1) = (r_1; r_2) = \dots (r_{n-1}; r_n) = r_n$ .

**Example 3.15.**

Use the Euclidean algorithm to find the greatest common divisor of 21 and 77.

We perform successive divisions:

$$77 : 21 = 3 \text{ (remainder 14);}$$

$$21 : 14 = 1 \text{ (remainder 7);}$$

$$14 : 7 = 2.$$

Therefore,  $(21, 77) = 7$ .

**Theorem 3.13:** (Properties of the greatest common divisor)

(i) For  $d = (a, b)$ , a necessary and sufficient condition is that  $d$  is a common divisor of  $a$ ,  $b$  and  $d$  is divisible by every common divisor of  $a$ ,  $b$ ;

(ii)  $(ma, mb) = m(a, b)$ , for every nonzero natural number  $m$ ;

(iii)  $(a/m, b/m) = 1/m$  (a, b), for every natural number  $m$  that is a common divisor of  $a$  and  $b$ .

*Proof:*

(i) Sufficient condition: Obviously.

Necessary condition: Follows from the Proof of the Euclidean algorithm.

(ii) Multiplying both sides of each equation in the Proof of the Euclidean algorithm by  $m$  we get the Euclidean algorithm for  $ma$  and  $mb$ . Therefore,  $(ma, mb) = mm = m(a, b)$ .

(iii) We have  $(a, b) = (m \setminus (1/m) a, m \setminus (1/m) b) = m(1/m a, 1/m b)$ . From this we deduce what we need to prove.

#### 3.2.4.2. Least common multiple

**Definition 3.14:**

Given  $a$  and  $b$  are natural numbers,  $b \neq 0$ . We say the natural number  $m$  is a common multiple of  $a$  and  $b$  if  $m$  is simultaneously a multiple of  $a$  and  $b$ .

From the definition we can easily deduce:

a) The set  $B(a)$  of multiples of  $a$  consists of natural numbers of the form  $na$ , with  $n$  a natural number.

b) The set  $BC(a, b) = B(a) \cap B(b)$  of common multiples of  $a$  and  $b$  is an infinite set, since it contains numbers of the form  $nb$ , with  $n$  a natural number.

Example 3.16.

$$B(12) = \{0, 12, 24, 36, 48, \dots\}$$

$$BC(12, 8) = \{0, 24, 48, \dots\}$$

**Definition 3.15:** Given  $a$  and  $b$  are two nonzero natural numbers. We call the least nonzero number among the common multiples of the two numbers  $a$ ,  $b$  the least common multiple. We denote it by  $c = [a, b]$  (or  $c = LCM(a, b)$ ).

**Remark:** Clearly: two given nonzero natural numbers always have a unique least common multiple.

**Example 3.17.**

$$[12, 8] = 24$$

$$[15, 60] = 60$$

$$[8, 15] = 120$$

*Note:* Similarly, we define: The least common multiple of  $n$  nonzero natural numbers is the least nonzero number among the common multiples of those  $n$  numbers.

**Example 3.18.**

$$[12, 8, 20] = 120$$

$$(8, 24, 72) = 72$$

$$[18, 12, 25] = 900$$

*Note:* From the definition we can easily deduce: If  $a > 0$  and  $a$  is divisible by  $b$  then  $[a, b] = a$ .

#### 3.2.4.3. Prime numbers

##### **Definition 3.16:**

Given  $p$  is a natural number greater than 1. We call  $p$  a prime number if  $p$  is only divisible by 1 and itself.

We denote the set of all prime numbers by  $P$ .

A natural number  $a$  greater than 1 that is not prime is called a composite number.

We denote the set of all composite numbers by  $H$ . Thus:

$$N = P \cup H \cup \{0, 1\}.$$

For example, 3, 5, 7, 11, 17, ... are prime numbers and 4, 12, 15, 28, ... are composite numbers. The numbers 0 and 1 are neither prime nor composite.

##### **Theorem 3.14.** (Properties of prime numbers)

(i) The least divisor other than 1 of a natural number greater than 1 is a prime number.

(ii) The set  $P$  of all prime numbers is infinite.

(iii) Suppose  $a$  is a natural number. If every divisor of  $a$  other than 1 exceeds  $\sqrt{a}$ , then  $a$  is prime, or in other words: if  $a$  is composite then it has a divisor other than 1 not exceeding  $\sqrt{a}$ .

*Proof:*

(i) Suppose  $p$  is the least divisor other than 1 of  $a$  but  $p$  is composite. By definition there exist  $q, s$  such that  $p = qs$ , where  $1 < q < p$ . Since  $a$  is divisible by  $p$  and  $p$  is divisible by  $q$ ,  $a$  is divisible by  $q$ . Hence  $q$  is a divisor of  $a$  other than 1. This is absurd, since  $p$  is the least divisor other than 1 of  $a$ .

(ii) Suppose  $P$  is finite,  $P = \{p_1, p_2, \dots, p_n\}$ . Let  $p = p_1 p_2 \dots p_n + 1$ . If  $p$  is composite then  $p$  has a prime divisor  $q$  (which is the least divisor other than 1 of  $p$ ). Since  $P$  is finite,  $q = p_i$  for some  $1 \le i \le n$ . Hence  $q$  divides  $p - p_1 p_2 \dots p_n = 1$ . This is absurd. Therefore  $p$  is prime but  $p \notin P$ . Thus  $P$  is infinite.

(iii) Suppose  $a$  is a composite number greater than 1. Then the least divisor other than 1 of  $a$  is a prime number, denoted  $p$ . We have  $a = pq$ . Since  $p$  is the least divisor of  $a$ ,  $p \le q$  or  $p^2 \le pq = a$  or  $p \le \sqrt{a}$ . This completes the proof

*Note:* Property (iii) in the above theorem gives us an algorithm to check if a natural number  $a$  is prime:

a) Find all prime numbers not exceeding  $\sqrt{a}$ .

b) Check in turn if each of those prime numbers is a divisor of  $a$ , if all those prime numbers are not divisors of  $a$  then  $a$  is prime.

Applying this algorithm we can construct a table of prime numbers less than a given natural number  $n$ .

For example, constructing a table of prime numbers not exceeding 100:

| 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 |
|----|----|----|----|----|----|----|----|----|----|
| 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 |
| 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 |

| 31 | 32 | 33 | 34 | 35 | 36 | 37 | 38 | 39 | 40  |
|----|----|----|----|----|----|----|----|----|-----|
| 41 | 42 | 43 | 44 | 45 | 46 | 47 | 48 | 49 | 50  |
| 51 | 52 | 53 | 54 | 55 | 56 | 57 | 58 | 59 | 60  |
| 61 | 62 | 63 | 64 | 65 | 66 | 67 | 68 | 69 | 70  |
| 71 | 72 | 73 | 74 | 75 | 76 | 77 | 78 | 79 | 80  |
| 81 | 82 | 83 | 84 | 85 | 86 | 87 | 88 | 89 | 90  |
| 91 | 92 | 93 | 94 | 95 | 96 | 97 | 98 | 99 | 100 |

The method is:

1) The prime numbers less than  $\sqrt{100}$  are 2, 3, 5, 7.

2) Cross out multiples of 2, 3, 5, 7 in the table.

3) The remaining uncrossed numbers are prime numbers less than 100.

This prime number table is called the Sieve of Eratosthenes.

Definition 3.17. (Relatively prime numbers and twin primes)

Given  $a$  and  $b$  are two natural numbers. We say  $a$  and  $b$  are relatively prime if  $(a, b) = 1$ .

We say  $a_1, a_2, \dots, a_n$  are twin primes if they are pairwise relatively prime.

Example 3.19.

8 and 15 are relatively prime; 24 and 35 are relatively prime.

12, 65, 77, 437 are twin primes.

#### 3.2.3.4. Properties of greatest common divisor and least common multiple

**Theorem 3.15:** (On properties of greatest common divisor)

(i) If  $a$  and  $c$  are relatively prime then  $(ab, c) = (b, c)$ .

(ii) If  $ab$  is divisible by  $c$ , where  $a$  and  $c$  are relatively prime, then  $b$  is divisible by  $c$ .

(iii) If  $a$  is simultaneously divisible by  $b$  and  $c$ , where  $b$  and  $c$  are relatively prime, then  $a$  is divisible by the product of  $b$  and  $c$ .

(iv) Suppose the greatest common divisor of  $a$  and  $b$  is  $d$ . Then there exist natural numbers  $m$  and  $n$  such that  $a = dm$ ,  $b = dn$ , where  $m$  and  $n$  are relatively prime.

*Proof:*

(i) Suppose  $d = (ab, c)$  and  $d' = (b, c)$ . We have:

-  $d$  is a common divisor of  $ab$  and  $c$  so  $d$  is also a common divisor of  $ab$  and  $bc$ . Hence  $d$  is a divisor of  $(ab, bc) = b(a, c) = b$ . Thus  $d$  is a common divisor of  $b$  and  $c$ . Hence  $d$  is a divisor of  $(b, c) = d'(1)$ .

-  $d'$  is a common divisor of  $b$  and  $c$  so  $d'$  is also a common divisor of  $ab$  and  $c$  so  $d'$  is a divisor of  $(ab, c) = d(2)$ .

From (1) and (2) we deduce  $d = d'$ .

Suppose  $ab$  is divisible by  $c$ . Hence  $(ab, c) = c$ . On the other hand, by (i) we have  $(b, c) = (ab, c) = c$ . Hence  $b$  is divisible by  $c$ .

Suppose  $(a, b) = d$ . Hence there exist natural numbers  $m, n$  such that  $a = dm$ ,  $b = dn$ . If  $m$  and  $n$  are not relatively prime then there exists  $d' \neq 1$  such that  $m = d'p$  and  $n = d'q$ . Substituting this we get  $a = dd'p$  and  $b = dd'q$ . This contradicts the assumption that  $d$  is the greatest common divisor of  $a$  and  $b$ .

##### **Example 3.20.**

Proof that the product of three consecutive natural numbers is divisible by 6.

*Solution:* Let  $a$  be a natural number. Let  $T = a(a+1)(a+2)$ . We prove  $T$  is divisible by 6.

Indeed, clearly  $T$  is divisible by 2, because among two consecutive natural numbers there must be an even number (1).

- If  $a$  is divisible by 3 then  $T$  is divisible by 3;

- If  $a$  leaves remainder 1 when divided by 3 then  $a+2$  is divisible by 3 so  $T$  is divisible by 3;

- If  $a$  leaves remainder 2 when divided by 3 then  $a+1$  is divisible by 3 so  $T$  is divisible by 3.

From the above results we deduce  $T$  is divisible by 3 (2).

Since 2 and 3 are relatively prime, from (1) and (2) we deduce  $T$  is divisible by  $2 \cdot 3 = 6$ . This completes the proof.

##### **Example 3.21.**

Find positive integer solutions to the following system of equations:

$$\{x + y = 120 \quad (1)$$

$$(x, y) = 15 \quad (2)$$

*Solution:* From (2) we have  $(x, y) = 15$ . By property (iv) there exist natural numbers  $m$ ,  $n$  such that  $a = 15m$  and  $b = 15n$ , where  $(m, n) = 1$ . Substituting into equation (1) we get:  $15m + 15n = 120$  or  $m + n = 8$ .

The number 8 can be written as the sum of 0 and 8; 1 and 7; 2 and 6; 3 and 5; 4 and 4.

Since  $(m, n) = 1$ ,  $m$  and  $n$  can only be 1 and 7 or 3 and 5.

Substituting this we get the solutions to the given system are:

$$\{x1 = 15, y1 = 105\}$$

$$\{x2 = 105, y2 = 15\}$$

$$\{x3 = 45, y3 = 75\}$$

$$\text{and } \{x4 = 75, y4 = 45\}$$

**Theorem 3.16:** (On properties of least common multiple)

(i) For any nonzero natural numbers  $a, b$  we always have:  $[a; b] = \frac{ab}{(a; b)}$ .

(ii) If  $a$  and  $b$  are relatively prime then  $[a, b] = ab$ .

(iii) For any nonzero natural number  $m$  we always have  $[am, bm] = m[a, b]$ .

*Proof:*

(i) Suppose  $d = (a, b)$ . By Theorem 3.15 there exist natural numbers  $m, n$  such that  $a = dm$ ,  $b = dn$ , where  $(m, n) = 1$ . Let  $u = ab/d$ . We prove  $u = [a, b]$ .

Indeed, we have  $u = \frac{dm \cdot dn}{d} = dmn = an = bm$ . Hence  $u$  is a common multiple of  $a$  and  $b$ .

Conversely, suppose  $v$  is a common multiple of  $a$  and  $b$  so  $v = ak$  and  $ak$  is divisible by  $b$ . Hence  $\frac{ak}{d} : \frac{b}{d} \to mk : n$ . Since  $(m, n) = 1$ ,  $k$  is divisible by  $n$  or  $k = nq$ . Substituting this we get  $v = anq = uq$ . Thus  $v$  is a multiple of  $u$ . This completes the proof.

(ii) Follows from (i).

(iii) We have  $[ma; mb] = \frac{ma \cdot mb}{(ma; mb)} = \frac{ma \cdot mb}{m(a; b)} = m \cdot \frac{ab}{(a; b)} = m[a; b]$ .

*Note:* From the theorem above we can easily deduce: "For  $m = [a, b]$ , a necessary and sufficient condition is that  $m$  is a common multiple of  $a$  and  $b$  and  $m$  is divisible by every common multiple of those two numbers."

We accept without Proof the following theorem:

Suppose  $a, b, c$  are natural numbers, where:

$$a = p_1^{\alpha_1} \cdot p_2^{\alpha_2} \cdots p_n^{\alpha_n};$$

$$b = p_1^{\beta_1} \cdot p_2^{\beta_2} \cdots p_n^{\beta_n};$$

$$c = p_1^{\gamma_1} \cdot p_2^{\gamma_2} \cdots p_n^{\gamma_n},$$

where  $p_1, p_2, \dots, p_n$  are different prime numbers,  $\alpha_i, \beta_j, \gamma_k$  are natural numbers. Then:

$$a)(a; b; c) = p_1^{\min(\alpha_1, \beta_1, \gamma_1)} \cdots p_n^{\min(\alpha_n, \beta_n, \gamma_n)};$$

$$b)[a; b; c] = p_1^{\max(\alpha_1, \beta_1, \gamma_1)} \cdots p_n^{\max(\alpha_n, \beta_n, \gamma_n)}.$$

Where  $m_i = \min\{\alpha_i; \beta_i; \gamma_i\}; k_j = \max\{\alpha_j; \beta_j; \gamma_j\}$  for  $i, j = 1, 2, \dots, n$ .

The theorem above can be stated in words as the following rule:

To find the GCD or LCM of two or more natural numbers, proceed as follows:

a) Factor them into products of different prime factors;

b) The greatest common divisor of those numbers is the product of the common factors with the least exponents;

c) The least common multiple of those numbers is the product of the common and distinct factors with the greatest exponents.

##### **Example 3.22.**

The greatest common divisor of two natural numbers is 7, their least common multiple is 105. Find those two numbers.

*Solution:* Let the two numbers we need to find be  $a$  and  $b$ . By the problem,  $(a, b) = 7$  and  $[a, b] = 105$ . Since

(a, b) = 7, by Theorem 3.15 there exist natural numbers m, n such that  $a = 7m$  and  $b = 7n$ , where m and n are relatively prime. By Theorem 3.16 we have:  $[a; b] = \frac{ab}{(a; b)}$ .

Substituting this we get:  $105 = \frac{7m \cdot 7n}{7} \rightarrow mn = 15$

The number 15 can be factored into 1.15 or 3.5.

Substituting this we get the pairs of numbers we need to find are: 7 and 105 or 21 and 35.

##### **Example 3.23.**

Given  $a = 240$ ,  $b = 8820$  and  $c = 7425$ . Find the greatest common divisor and least common multiple of the three numbers.

*Solution:* We have:

$240 = 23.3.5$ ,  $8820 = 22.32.5.72$  and  $7425 = 33.52.11$ . Applying the above rule we get:

$$(240, 8820, 7425) = 3.5 = 15;$$

$$[240, 8820, 7425] = 23.33.52.72.11 = 5,821,200.$$

#### **3.2.4.5. Positional numeral systems of base $g$ and the decimal system in primary school**

a) Definition of a positional numeral system of base  $g$

$$d) (a \cdot c) : (b \cdot c) = a : b.$$

$$d) (a : c) : (b : c) = a : b.$$

**Theorem 3.17:** Let  $a$  be a natural number greater than 0 and  $g$  be a natural number greater than 1. Then there exist natural numbers  $c_0, c_1, c_2, \dots, c_n$  such that:

$$a = c_n g^n + c_{n-1} g^{n-1} + c_{n-2} g^{n-2} + \dots + c_1 g + c_0 \quad (*)$$

where  $0 \le c_i \le g-1$ ;  $i = 0, 1, \dots, n$ ;  $c_n \ne 0$ .

The representation above is unique for each pair of natural numbers  $a$ ,  $g$ .

*Proof:*

Perform the successive divisions of  $a$  by  $g$ , call the remainders in order  $c_0, c_1, c_2, \dots, c_n$  then we have:

$$a = gq_0 + c_0$$

$$q_0 = gq_1 + c_1$$

$$q_1 = gq_2 + c_2$$

$$\dots \dots \dots \dots$$

$$q_{n-2} = gq_{n-1} + c_{n-1}$$

$$q_{n-1} = g \cdot 0 + c_n$$

where  $0 \le c_i \le g-1$ ;  $c_n \ne 0$ . Successively substituting the above equations (from bottom up) gives:  $a = c_n g^n + c_{n-1} g^{n-1} + c_{n-2} g^{n-2} + \dots + c_1 g + c_0$

We will Proof that the representation above is unique. Indeed, suppose:

$a = c_n g^n + c_{n-1} g^{n-1} + c_{n-2} g^{n-2} + \dots + c_1 g + c_0$  and  $a = b_n g^n + b_{n-1} g^{n-1} + b_{n-2} g^{n-2} + \dots + b_1 g + b_0$ . Since  $c_0$  and  $b_0$  are both remainders when dividing a by  $g$ ,  $c_0 = b_0$ . Similarly,  $c_i = b_i$  for  $i = 1, 2, \dots, n$ .

Thus the Proof is complete.

**Definition 3.18:** Assume  $a$  and  $g$  are two natural numbers represented by formula (\*) in Theorem 3.17. In this case, we write:  $a = \overline{c_n c_{n-1} c_{n-2} \dots c_1 c_0_g}$  and call it the representation of the natural number  $a$  in base  $g$  number system or  $g$ -ary number system.

**Example 3.24.**

$$13 = 1 \cdot 2^3 + 1 \cdot 2^2 + 1 = 1 \cdot 2^3 + 1 \cdot 2^2 + 0 \cdot 2 + 1. \text{ Vây } 8 = \overline{1101}_2.$$

$$54 = 1 \cdot 7^2 + 5 = 1 \cdot 7^2 + 0 \cdot 7 + 5. \text{ Vây } 54 = \overline{105}_7.$$

$$54 = 4 \cdot 11 + 10. \text{ Đặt } \alpha = 10 \text{ ta có } 54 = \overline{4\alpha_{11}}.$$

$$503 = 3 \cdot 12^2 + 5 \cdot 12 + 11. \text{ Đặt } \beta = 11 \text{ ta có } 503 = \overline{35\beta_{12}}.$$

*Note:*

1) To represent a natural number  $a$  in base  $g$  number system, we must use digits from 0 to  $g-1$ .

2) When the base  $g$  is greater than 10, the 10 basic digits from 0 to 9 are not enough to represent, so we need to add new characters (beyond the 10 basic digits) which are:  $\alpha=10$ ;  $\beta=11$ ;  $\delta=12$ ; ...

3) To represent the natural number  $a$  in base  $g$  number system, we successively divide  $a$  by  $g$  until the quotient is 0 then stop. The remainders in the divisions will be the digits representing  $a$  in base  $g$  number system.

b) Comparing numbers in base  $g$  number system

When practicing comparing numbers in base  $g$  number system, we apply the following rule:

$$\text{Assume } a = \overline{c_n c_{n-1} c_{n-2} \dots c_1 c_0_g} \text{ and } b = \overline{b_m b_{m-1} b_{m-2} \dots b_1 b_0_g}.$$

a) If  $n < m$  then  $a < b$ ;

b) If  $n = m$  then  $a$  and  $b$  have the same number of digits. In this case, we successively compare the digits in the same position from left to right. The number that has the first larger digit is greater.

**Example 3.25.**

$$\overline{792}_8 < \overline{1032}_8; \quad \overline{2411}_5 > \overline{414}_5$$

$$\overline{2108}_9 < \overline{2703}_9; \quad \overline{31105}_6 > \overline{31015}_6$$

c) Arithmetic operations in base  $g$  number system

Addition and subtraction

**Example 3.26.**

Construct the addition table in base  $g = 7$ .

|   | + | 0  | 1  | 2  | 3  | 4  | 5  | 6 |
|---|---|----|----|----|----|----|----|---|
| 0 | 0 | 1  | 2  | 3  | 4  | 5  | 6  |   |
| 1 | 1 | 2  | 3  | 4  | 5  | 6  | 10 |   |
| 2 | 2 | 3  | 4  | 5  | 6  | 10 | 11 |   |
| 3 | 3 | 4  | 5  | 6  | 10 | 11 | 12 |   |
| 4 | 4 | 5  | 6  | 10 | 11 | 12 | 13 |   |
| 5 | 5 | 6  | 10 | 11 | 12 | 13 | 14 |   |
| 6 | 6 | 10 | 11 | 12 | 13 | 14 | 15 |   |

The filling method is: for example:

- We want to fill in the cell with row 2, column 3: take  $2 + 3 = 5 < 7$ . So we fill 5 in that cell;

- We want to fill in the cell with row 6, column 5: take  $6 + 5 = 11 > 7$ . Take 11 divided by 7, quotient is 1, remainder is 4. The result will be 14. So we fill 14 in that cell.

The rule is:

To fill in any cell in the addition table of base  $g$  number system, take the row number plus the column number of that cell: if the result is less than the base then write it directly, if the result is the base or more, divide it by the base then read from quotient to remainder.

**Example 3.27.**

Calculate:

$$\overline{5476_8} + \overline{4725_8}$$

First, rewrite the calculation vertically:

$$\begin{array}{r} 5476 (8) \\ + 4725 \\ \hline 12423 \end{array}$$

$$\text{Vậy: } \overline{5476_8} + \overline{4725_8} = \overline{12423_8}.$$

The method is:

- Add digit by digit from right to left;

-  $6 + 5 = 11$ . Take 11 divided by 8, quotient is 1, remainder is 3. Write 3, carry 1.

-  $7 + 2 = 9$ , carry 1 is 10. Take 10 divided by 8, quotient is 1, remainder is 2. Write 2, carry 1.

- Continue similarly...

**Example 3.28.**

Calculate:

$$\overline{2031_9} - \overline{745_9}$$

First, rewrite the calculation vertically:

$$\begin{array}{r} 2031 (9) \\ - 745 \\ \hline 1175 \end{array}$$

$$\text{Vậy: } \overline{2031_9} - \overline{745_9} = \overline{1175_9}.$$

The method is:

- Subtract digit by digit from right to left;

- 1 cannot subtract 5, borrow 1 (take  $1 + 9 = 10$ ) then take 10 minus 5 equals 5, write 5, borrow 1.

- 4 borrow 1 is 5; 3 cannot subtract 5, borrow 1 ( $3 + 9 = 12$ ) then take 12 minus 5 equals 7, write 7, borrow 1.

- Continue similarly...

Multiplication and division

##### **Example 3.29.**

Construct the multiplication table in base  $g = 6$ .

| x | 1 | 2  | 3  | 4  | 5  |
|---|---|----|----|----|----|
| 1 | 1 | 2  | 3  | 4  | 5  |
| 2 | 2 | 4  | 10 | 12 | 14 |
| 3 | 3 | 10 | 13 | 20 | 23 |
| 4 | 4 | 12 | 20 | 24 | 32 |
| 5 | 5 | 14 | 23 | 32 | 41 |

The filling method is: for example:

- We want to fill in the cell with row 3, column 1: take  $3 \times 1 = 3 < 6$ . So we fill 3 in that cell;

- We want to fill in the cell with row 5, column 4: take  $5 \times 4 = 20 > 6$ . Take 20 divided by 6, quotient is 3, remainder is 2. The result will be 32. So we fill 32 in that cell.

The rule is:

To fill in any cell in the multiplication table of base  $g$  number system, take the row number times the column number of that cell: if the result is less than the base then write

it directly, if the result is the base or more, divide it by the base then read from quotient to remainder.

**Example 3.30.**

Calculate:

$$\overline{435_6} \times \overline{54_6}$$

First, rewrite the calculation vertically:

$$\begin{array}{r} 432 \quad (6) \\ \times 54 \\ \hline 3012 \\ \hline 3502 \\ \hline 42032 \end{array}$$

$$\text{V\acute{a}y: } \overline{435_6} \times \overline{54_6} = \overline{42032_6}.$$

The method is:

- Multiply digit by digit from right to left;
- In the first partial product:  $4 \times 2 = 8$ . Take 8 divided by 6, quotient is 1, remainder is 2. Write 2, carry 1.
- $4 \times 3 = 12$ , carry 1 is 13. Take 13 divided by 6, quotient is 2, remainder is 1. Write 1, carry 2.
- Continue similarly...

**Example 3.31.**

Calculate:

$$\overline{14443_5} : \overline{32_5}$$

First, rewrite the calculation vertically:

$$\begin{array}{r} 144'4'3' \quad 32 \quad (5) \\ 114 \quad \overline{243} \\ 304 \\ \hline 233 \\ \hline 213 \\ \hline 201 \\ \hline 12 \end{array}$$

$$\text{So: } \overline{14443_5} : \overline{32_5} = \overline{243_5} \text{ (remainder } \overline{12_5})$$

The method is:

- Divide digit by digit from left to right;

- In the first division:  $144 : 32$ , quotient is 2. Take  $\overline{2_5} \times \overline{32_5} = \overline{114_5}$ . Take  $\overline{144_5} - \overline{114_5} = \overline{30_5}$ .

- Bring down 4 to get  $\overline{304_5}$  then continue dividing as above.

- Continue similarly...

d) Arithmetic operations in base  $g$  number system

- In elementary school Mathematics, students mainly practice (counting, comparing, calculating, ...) in base  $g = 10$  number system, also known as the decimal system. In the decimal system: every 10 units of the next position to the left has the value of 1 unit in the immediate previous position.

- Besides the decimal system, students are also introduced to some other base number systems, for example:

+ Base  $g = 2$  number system, also called binary system, often called pairs in elementary school. In the binary system: every 2 units of the next position to the left has the value of 1 unit in the immediate previous position.

+ Base  $g = 12$  number system, also called duodecimal system, often called dozens in elementary school. In the duodecimal system: every 12 units of the next position to the left has the value of 1 unit in the immediate previous position.

+ Base  $g = 60$  number system, also called sexagesimal system. We see this counting method in time measurement: 1 hour = 60 minutes; 1 minute = 60 seconds. In the sexagesimal system: every 60 units of the next position to the left has the value of 1 unit in the immediate previous position.

...

- When representing natural numbers in the decimal system, note that:

+ We will write 2047; 672 instead of  $\overline{2047_{10}}; \overline{672_{10}}$ ;

+ When representing a natural number with at least 1 unknown digit, we must use a vinculum over that number. In this case, we agree that: each character written under the vinculum represents a digit from 0 to 9. The first digit from the left must be nonzero.

For example:  $\overline{abcd}; \overline{2a4b}; \overline{16a}; \dots$

+ When setting up the vertical calculation, we do not need to use the vinculum, for example:

abcde

+ ba6m

**Theorem 3.18.** A natural number  $a$  is divisible by 2 if and only if its unit digit is 0, 2, 4, 6 or 8.

*Proof.*

Assume  $a = \overline{c_n c_{n-1} \dots c_1 c_0}$ . We have:

$$\begin{aligned}a &= c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0 \\&= (c_n 10^{n-1} + c_{n-1} 10^{n-2} + \dots + c_1). 10 + c_0\end{aligned}$$

Hence  $a$  is divisible by 2 if and only if  $c_0$  is divisible by 2 or  $c_0 = 0, 2, 4, 6$  or 8. This Proofs the theorem.

**Theorem 3.19:** A natural number  $a$  is divisible by 5 if and only if its unit digit is 0 or 5.

*Proof:* Similar to Theorem 3.18.

**Theorem 3.20:** A natural number  $a$  is divisible by 3 (or 9) if and only if the sum of its digits is divisible by 3 (or 9).

*Proof:*

Assume  $a = \overline{c_n c_{n-1} \dots c_1 c_0}$ . We have:

$$\begin{aligned}a &= c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0 \\&= c_n (9 + 1)^n + c_{n-1} (9 + 1)^{n-1} + \dots + c_1 (9 + 1) + c_0 \\&= \dots \\&= T_n 9 + (c_n + c_{n-1} + \dots + c_1 + c_0)\end{aligned}$$

Hence  $a$  is divisible by 3 (or 9) if and only if  $c_n + c_{n-1} + \dots + c_1 + c_0$  is divisible by 3 (or 9) or the sum of the digits of  $a$  is divisible by 3 (or 9).

**Theorem 3.21.** A natural number  $a$  is divisible by 4 (or 25) if and only if the number formed by its last two digits is divisible by 4 (or 25).

*Proof.*

Assume  $a = \overline{c_n c_{n-1} \dots c_1 c_0}$ . We have:

$$\begin{aligned}a &= c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0 \\&= (c_n 10^{n-2} + c_{n-1} 10^{n-3} + \dots + c_2). 100 + \overline{c_1 c_0}\end{aligned}$$

Hence  $a$  is divisible by 4 (or 25) if and only if  $\overline{c_1 c_0}$  is divisible by 4 (or 25) or the number formed by the last two digits of  $a$  is divisible by 4 (or 25). This Proofs the theorem.

**Theorem 3.22.** A natural number  $a$  is divisible by 11 if and only if the difference between the sum of its even digit positions and the sum of its odd digit positions is divisible by 11.

*Proof.*

Assume  $a = \overline{c_n c_{n-1} \dots c_1 c_0}$ . We have:

$$\begin{aligned}a &= c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0 \\&= c_n (11 - 1)^n + c_{n-1} (11 - 1)^{n-1} + \dots + c_1 (11 - 1) + c_0 \\&= 11T_n + (-1)^n c_n + 11T_{n-1} + (-1)^{n-1} c_{n-1} + \dots + 11T_1 - c_1 + c_0 \\&= 11(T_n + T_{n-1} + \dots + T_1) + (c_0 + c_2 + c_4 + \dots + c_{2k}) - (c_1 + c_3 + \dots + c_{2k-1})\end{aligned}$$

Hence  $a$  is divisible by 11 if and only if the difference between the sum of its even digit positions and the sum of its odd digit positions is divisible by 11. This Proofs the theorem.

##### **Example 3.32.**

Find a natural number  $n$  between 5000 and 6000 such that  $n$  is divisible by 6, 9 and 25.

*Solution:*

Since  $n$  is between 5000 and 6000, it has the form  $n = \overline{5abc}$ . Since  $n$  is divisible by 25,  $\overline{bc}$  is divisible by 25. Also, since  $n$  is divisible by 6, it must be even. Hence  $n = \overline{5a00}$  or  $n = \overline{5a50}$ .

a) Consider  $n = \overline{5a50}$ : since  $n$  is divisible by 9,  $5 + a + 5 + 0 = a + 10$  is divisible by 9. Hence  $a = 4$ . Substituting, we get  $n = 5400$ .

b) Consider  $n = \overline{5a00}$ : since  $n$  is divisible by 9,  $5 + a + 0 + 0 = a + 5$  is divisible by 9. Hence  $a = 8$ . Substituting, we get  $n = 5850$ .

##### **Example 3.33.**

Let  $a$  be a natural number. Writing the digits of  $a$  in reverse order gives the natural number  $b$  which is 3 times  $a$ . Proof that  $b$  is divisible by 9.

*Solution:*

Let  $a = \overline{c_1 c_2 \dots c_k}$ . Writing the digits of  $a$  in reverse order gives  $b = \overline{c_k c_{k-1} \dots c_2 c_1} = 3a$  (1).

Hence  $b$  is divisible by 3. By the divisibility rule of 3,  $s = c_k + c_{k-1} + \dots + c_2 + c_1$  is divisible by 3. Thus,  $a$  also has digit sum divisible by 3 so  $a$  is divisible by 3, hence  $a = 3q$ .

Substituting into (1) gives  $b = 9q$ . Thus  $b$  is divisible by 9. Hence the digit sum  $s$  of  $b$  is divisible by 9. The digit sum of  $a$  is also divisible by 9.

Therefore  $a$  is divisible by 9. This Proofs the statement.

##### **Example 3.34.**

Find the even 3-digit number which is divisible by 5, 9 and 11.

*Solution:*

Let the required number be  $n = \overline{abc}$ . Since  $n$  is even and divisible by 5,  $c = 0$ . Substituting, we get  $n = \overline{ab0}$ . Since  $n$  is divisible by 11,  $a - b$  is divisible by 11. Hence  $a = b$ .

Also, since  $n$  is divisible by 9,  $a + b + 0 = a + b$  is divisible by 9. Hence  $a + b$  can only be 0, 9 or 18.

From the above,  $a = b = 9$ . Substituting, we get  $n = 990$ .

##### **Example 3.35.**

Proof that among any 11 natural numbers, there always exist two numbers whose difference is divisible by 2 and 5.

*Solution:*

With 11 natural numbers there are 11 unit digits corresponding to those numbers. Since there are only 10 distinct unit digits (which are 0, 1, 2, ..., 9), there must be 2 numbers among the 11 that have the same unit digit. The difference of these two numbers will be a multiple of 10 so it is divisible by both 2 and 5.

## 3.3. The integers

### 3.3.1. Constructing the integers from natural numbers

The Cartesian product of the sets  $\mathbb{N} \times \mathbb{N}$  is defined as follows:

Given the ordered pairs  $(m, n)$  and  $(m', n')$  in  $\mathbb{N} \times \mathbb{N}$ , we say  $(m, n)$  is equivalent to  $(m', n')$ , denoted  $(m, n) \sim (m', n')$ , if and only if  $m+n' = m'+n$ .

This defines an equivalence relation, denoted by  $\sim$ , on  $\mathbb{N} \times \mathbb{N}$ . Using this relation, we construct the set of equivalence classes,  $\mathbb{Z}$ , which represents the set of all integers. Here,  $\mathbb{Z}$  is the set of all such equivalence classes, and each class represents a unique integer.

*Note: 1.*  $\mathbb{Z} = \mathbb{N} \times \mathbb{N} / \sim$  contains integer classes corresponding to the product of sets  $\mathbb{N} \times \mathbb{N}$  in the form  $(m, n)$ , according to the equivalence relation. We have the following possibilities:

a. If  $m > n$ , then  $(m, n) = (k, 0)$ , where  $k = m - n \in \mathbb{N}^*$

b. If  $m < n$ , then  $(m, n) = (0, k)$ , where  $k = n - m \in \mathbb{N}^*$

c. If  $m = n$ , then  $(m, n) = (0, 0)$ .

Thus, every integer class can represent an integer according to the form  $(k, 0)$  or  $(0, k)$ . To simplify, we denote the integer  $(k, 0)$  by  $k$  and the integer  $(0, k)$  by  $-k$ , where  $k \neq 0$ , the integer  $(0, 0)$  by 0.

Thus,  $\mathbb{Z} = \{\dots, -k, \dots, -2, -1, 0, +1, +2, +3, \dots, +k, \dots\}$ .

The integers -1, -2, -3, ... and the positive integers +1, +2, +3, ... are usually written without the "+" sign. When writing positive integers, we often omit the "+" sign in front of them.

2. Each natural number  $n$  corresponds uniquely to the integer  $(n, 0)$ . Hence,  $\mathbb{N}$  is a subset of  $\mathbb{Z}$ .

### 3.3.2. Operations with integers

#### 3.3.2.1. Addition and Subtraction

For the integers  $z_1 = (m_1, n_1)$  and  $z_2 = (m_2, n_2)$ , we define their sum as:

$$z_1 + z_2 = (m_1 + m_2, n_1 + n_2)$$

## 3.3. Rational numbers are not negative

### 3.3.1. Construct a set of non-negative rational numbers

#### 3.3.1.1. The need to build a set of non-negative rational numbers

If we stop at the set of natural numbers, many divisions cannot be performed, such as  $3:7, 25:8, 1:6, \dots$

If we stop at the set of natural numbers, many measurements of quantities cannot be performed; for example, the measurement of 12cm cannot be represented; 2m 4dm are in meters; we cannot perform 100g; 3006g; 4kg 25g equals kilograms; ...

In high school math, many properties of fraction operations (commutative properties, associative properties, distributive properties of addition and multiplication, etc.) cannot be rigorously proven and must be proven. admitted (through some illustrative examples).

In the real world of work and production, due to the development requirements of science and engineering, there is always a need to solve the above problems.

Therefore, in this section, we expand the set of natural numbers by adding new numbers so that, in that new set of numbers, we can overcome the above limitations.

#### 3.3.1.2. Construct a set of non-negative rational numbers

**Definition 3.19.** A non-negative fraction (or simply, a fraction) is an ordered pair (a; b), where a and b are natural numbers, and b is not equal to 0. The number b represents the number of equal parts into which the unit is divided, while a represents the number of equal parts taken. Fractions are typically indicated using the symbol  $\frac{a}{b}$ , replacing the ordered pair (a; b), where a is referred to as the numerator and b is called the denominator.

The set of all fractions is denoted by P. Thus,  $P = \mathbb{N} \times \mathbb{N}^*$ , where  $\mathbb{N}^*$  is the set of non-zero natural numbers.

On the set P, we define a binary relationship " $\sim$ " as follows:

Two fractions  $\frac{a}{b}; \frac{c}{d}$  are called equivalent, denoted by  $\frac{a}{b} \sim \frac{c}{d}$ , if  $ad = cd$ .

Such as  $\frac{1}{2} \sim \frac{4}{8}; \frac{3}{4} \sim \frac{9}{12}; \frac{1}{2} \sim \frac{2}{4}$  is not equivalent to  $\frac{2}{5}; \frac{3}{4}$  is not equivalent to  $\frac{4}{3}$ .

We can easily show that this is an equivalence relation defined on the set of fractions P. According to theorem, we can divide the set P into equivalence classes and get the quotient set:  $P | \sim = \{C(\frac{a}{b}) : \frac{a}{b} \in P\}$ .

Each class is equivalent  $C(\frac{a}{b})$  is a set of equal fractions (equal to fractions  $\frac{a}{b}$ ). Such as:

$$C(\frac{1}{2}) = \{\frac{1}{2}; \frac{2}{4}; \frac{3}{6}; \dots; \frac{45}{90}; \dots; \frac{120}{240}; \dots\}$$

$$C(\frac{3}{4}) = \{\frac{3}{4}; \frac{6}{8}; \frac{9}{12}; \dots; \frac{45}{60}; \dots; \frac{75}{100}; \dots\}$$

Each equivalence class  $C(\frac{a}{b})$  we will call a non-negative rational number (for brevity we call it rational number), denoted by  $r = C(\frac{a}{b})$ . The set of all non-negative rational numbers we denote by  $Q_+$ . Thus  $Q_+ = P/\sim$ .

Note:

1. Every non-negative rational number  $r = C(\frac{a}{b})$  is a set of equal fractions  $\frac{a}{b}$ . For brevity, we will use symbols  $\frac{a}{b}$  to denote rational numbers  $r = C(\frac{a}{b})$ . Example, we denote  $\frac{1}{2}$  to indicate rational numbers  $r = C(\frac{1}{2})$ ;  $\frac{9}{5}$  to indicate rational numbers  $r = C(\frac{9}{5})$ .

2. Each non-negative rational number  $r$  has a unique representative, which is an simplified fraction.

Indeed, suppose  $\frac{p}{q}$  and  $\frac{p'}{q'}$ , that two simplified fractions, are both representative of the rational number  $r$ . According to the equivalence class definition we have  $\frac{p}{q} \sim \frac{p'}{q'}$ . It follows that  $pp' = p'q$ . Because  $\text{GCD}(p; q) = \text{GCD}(p'; q') = 1$ ,  $p = p'$  and  $q = q'$ . Figure out what must be proven.

We use the convention: when we talk about representative fractions of rational numbers  $r$ , we understand it as minimal fractions  $\frac{p}{q}$  *there*.

3. Each natural number  $a$  can be expressed as a fraction  $\frac{a}{1}$ . Therefore, each natural number  $a$  also uniquely identifies a rational number  $r$  whose representative fraction is  $\frac{a}{1}$ . Therefore, the set of natural numbers  $N$  can be considered a part of the set of rational numbers  $Q^+$ .

4. We convention that the rational number  $C(\frac{0}{1})$  defined by is 0 and the rational number  $C(\frac{1}{1})$  defined by is 1.

### 3.3.2. Order relations in the set of rational numbers are non-negative

In high school, we know:

- $\frac{3}{7} < \frac{5}{7}$ . So can we compare two rational numbers  $r = C(\frac{3}{7})$  and  $s = C(\frac{5}{7})$  get it?
- $\frac{2}{7} < \frac{3}{5}$ . So can we compare two rational numbers  $r = C(\frac{2}{7})$  and  $s = C(\frac{3}{5})$  get it?

In general: let's come up with a rule to compare any two rational numbers  $r = C(\frac{a}{b})$  and  $s = C(\frac{c}{d})$ . Satisfy this requirement with the following definition:

**Definition 3.20.** Given two rational numbers  $r = C(\frac{a}{b})$  and  $s = C(\frac{c}{d})$ . We say:

a) Rational number  $r$  is less than or equal to rational number  $s$ , denoted by  $r \le s$ , if  $ad \le bc$ .

b) The rational number  $r$  is less than the rational number  $s$ , denoted by  $r < s$ , if  $r \le s$  và  $r \ne s$ .

c) The rational number  $r$  is greater than or equal to the rational number  $s$ , denoted by  $r \ge s$ , if  $s \le r$ .

d) The rational number  $r$  is greater than the rational number  $s$ , denoted by  $r > s$ , if  $s < r$ .

The relations  $r \le s$  and  $r \ge s$ , we call inequalities; the relations  $r < s$  and  $r > s$  are called strict inequalities

**Comment:** By the definition above, we have reduced the comparison of rational numbers to the comparison of natural numbers.

**Example 3.36.**  $C(\frac{3}{7}) < C(\frac{5}{7})$  because  $3.7 < 5.7$ ;

$$C(\frac{5}{9}) > C(\frac{3}{11}) \text{ because } 5.11 > 9.3;$$

$$C(\frac{2}{5}) = C(\frac{6}{15}) \text{ because } 2.15 = 5.6.$$

**Theorem 3.23** (About the properties of ordering relations in the set  $\mathbb{Q}^+$ ):

(i) Comparing two rational numbers does not depend on the choice of their representative fractions;

(ii) The ordering relation is reflexive: For any rational number  $r$ , we always have  $r \le r$ ;

(iii) The ordering relation is antisymmetric: For all rational numbers  $r$ ,  $s$ , we always have:  $(r \le s \text{ and } s \le r) \rightarrow r = s$ ;

(iv) The ordering relation is transitive: For all rational numbers  $r$ ,  $s$ ,  $t$ , we always have:  $(r \le s \text{ and } s \le t) \rightarrow r \le t$ .

*Proof:*

(i) Suppose  $\frac{a}{b'}, \frac{a'}{b''}$  are two representative fractions of rational number  $r$ ,  $\frac{c}{d'}, \frac{c'}{d''}$  are two representative fractions of rational number  $s$ , in which  $ad \le bc$ . We will prove  $a'd' \le b'c'$ .

Indeed, by assumption:  $ab' = a'b$ ;  $cd' = c'd$ . Suppose  $a'd' > c'b'$ . Applying the properties of the set of natural numbers, we have:  $a'bcd' = ab'c'd$  and  $adc'b' < bca'd'$ .

This is absurd. This completes the proof

(ii) and (iii) Clarity.

(iv) Suppose  $r = \frac{a}{b}$ ;  $s = \frac{c}{a}$ ;  $t = \frac{m}{n}$ , where

$$r \le s, s \le t \rightarrow ad \le bc; cn \le md \rightarrow adcn \le bcmd \rightarrow an \le mb \rightarrow r \le t.$$

**Theorem 3.24.**

(i) *Density of the set of rational numbers*: Between two different rational numbers, there exist infinitely many other rational numbers;

(ii) *Archimedes axiom*: Every rational number is bounded by a natural number, or in other words, for every rational number  $r$ , there always exists a natural number  $n$  such that  $r < n$ .

*Proof:*

(i) Suppose  $r = \frac{a}{b}$ ,  $s = \frac{c}{d}$ , there are two rational numbers, where  $r > s$ . It follows that  $ad < bc$ . Set  $t = \frac{ad+bc}{2bd}$ . We have:  $\frac{c}{d} = \frac{2bc}{2bd} < \frac{ad+bc}{2bd} < \frac{2ad}{2bd} = \frac{a}{b}$ . From here it follows that  $r > t > s$ . This completes the proof

(ii) Suppose  $r = \frac{a}{b}$ , that according to Archimede's principle, in the set of natural numbers, there exists a natural number  $n$  such that  $nb > a$ . It follows that  $n > r$ .

### 3.3.3. *Mathematical operations in the set of non-negative rational numbers*

#### 3.3.3.1. *Addition and multiplication*

**Definition 3.21.** Let  $r$  and  $s$  be two non-negative rational numbers, in which  $r = C(\frac{a}{b})$ ;  $s = C(\frac{c}{d})$ . We call:

a) The sum of two rational numbers  $r$  and  $s$  is a rational number  $t$ , denoted  $t = r + s$ , where  $t = C(\frac{ad+bc}{bd})$ .

The rule for corresponding each pair of rational numbers  $r$ ,  $s$  with a rational number  $t$  mentioned above is called addition of rational numbers, in which  $r$  and  $s$  are called terms,  $t$  is the sum and  $r + s$  is also called the sum.

b) The product of two rational numbers  $r$  and  $s$  is a rational number  $p$ , denoted by  $p = r \times s$  (or  $rs$  or  $rs$ ), where  $p = C(\frac{ac}{bd})$ .

The rule for corresponding each pair of rational numbers  $r$ ,  $s$  with a rational number  $p$  mentioned above is called multiplication of rational numbers, in which  $r$  and  $s$  are called factors,  $p$  is called product and  $rs$  is also called is the product.

**Example 3.37.** Let  $r$  and  $s$  be two rational numbers whose corresponding

representative fractions are  $\frac{4}{9}$  and  $\frac{7}{12}$ . We have:

$$r + s = C\left(\frac{4.12 + 9.7}{9.12}\right) = C\left(\frac{37}{36}\right); r \cdot s = C\left(\frac{4.7}{9.12}\right) = C\left(\frac{7}{27}\right).$$

**Attention:** From the definition we prove that the sum and product of two rational numbers do not depend on the choice of their representative fractions.

Or, in other words, for any two rational numbers  $r$  and  $s$ , there always exists only one rational number  $t$  as the sum and one rational number  $p$  as their product.

Let  $\frac{a}{b}, \frac{a'}{b'}$  be two representative fractions of the rational number  $r$ , and let  $\frac{c}{d}, \frac{c'}{d'}$  be two representative fractions of the rational number  $s$ . I will prove that  $C\left(\frac{ad+bc}{bd}\right) =$

$$C\left(\frac{a'd'+b'c'}{b'd'}\right)$$

Indeed, according to the hypothesis:  $ab' = a'b$ ;  $cd' = c'd$ . Applying properties of natural numbers, we have:  $ab'dd' = a'bdd'$  and  $cd'bb' = c'dbb'$  or  $(ad + bc)b'd' = (a'd' + b'c')bd$ .

From here, it follows that, the sum of two rational numbers does not depend on the choice of their representative fractions.

Similarly, we can prove the uniqueness of the product of two rational numbers.

**Theorem 3.25:** (Properties of addition and multiplication of rational numbers)

Suppose  $r, s, t$  are any three rational numbers. Then:

(i) Commutative property:

$$r + s = s + r \text{ and } rs = sr$$

(ii) Combination properties:

$$(r + s) + t = r + (s + t) \text{ and } (rs).t = r.(st)$$

(iii) Properties of numbers 0 and 1:

$$r + 0 = 0 + r = r \text{ and } r.1 = 1.r = r$$

(iv) Distribution characteristics:

$$r.(s + t) = rs + rt \text{ and } (s + t).r = sr + tr$$

(v) Simplified law:

$$r + t = s + t \text{ implies } r = s \text{ and } rt = st, \text{ with } r = s.t \neq 0$$

(vi) Inverse element: For every rational number  $r \neq 0$ , there always exists a unique inverse  $r^{-1}$  of  $r$ , such that  $r \cdot r^{-1} = 1$ .

(vii) The product of two rational numbers is 0 if and only if at least one of them is 0.

*Proof:*

(i), (ii), (iii), (iv) are simple: deduced directly from the properties of operations in the set of natural numbers.

(v) Suppose  $\frac{a}{b}, \frac{c}{d}, \frac{m}{n}$ , that in order are the representative fractions of the rational numbers  $r, s, t$ . By definition, we have:  $r + t = C\left(\frac{an+bm}{bn}\right); s + t = C\left(\frac{cn+dm}{dn}\right)$ . Because

$r + t = s + t$ , so  $(an + bm)dn = bn(cn + dm)$  or  $andn + bmdn = bncn + bndm$ . It follows that  $ad = bc$ .

From here we can deduce what must be proven.

Similarly, we prove the law of reduction for multiplication.

(vi) Suppose  $r = C\left(\frac{a}{b}\right) \neq 0 \rightarrow a \neq 0$ . Set  $r^{-1} = C\left(\frac{b}{a}\right)$  will be the inverse of  $r$ .

(vii) Suppose  $r = C\left(\frac{a}{b}\right), s = C\left(\frac{c}{d}\right)$ , that  $rs = 0$  is satisfied. By definition, we have  $\frac{ac}{bd} = 0$ .

Deduce  $ac = 0$ . According to the properties of multiplication of natural numbers, we have  $a = 0$  or  $b = 0$ . From here, deduce  $r = 0$  or  $s = 0$ .

**Theorem 3.26** (Monotonicity of addition and multiplication of rational numbers):

Suppose  $r$ ,  $s$  and  $t$  are any three rational numbers. We have:

If  $r \le s$ , then  $r + t \le s + t$  and  $rt \le st$ .

In particular, if  $r < s$  and  $t > 0$  then  $rt < st$ .

*Proof:*

Suppose  $\frac{a}{b}$ ,  $\frac{c}{d}$ ,  $\frac{m}{n}$ , in order are the representative fractions of the rational numbers  $r$ ,  $s$ ,  $t$ .

By definition, we have:  $r + t = C(\frac{an+bm}{bn})$ ;  $s + t = C(\frac{cn+dm}{dn})$ . Therefore  $r \le s$ , so  $ad \le bc$ . Transforming in turn, we get:  $andn + bmdn \le cnbn + dmbn$  or  $(an + bm)dn \le (cn + dm)bn$ . From here we can deduce what must be proven.

Similarly, we prove the monotonicity of multiplication.

#### 3.3.3.2. Subtraction

**Definition 3.22.** Let  $r$  and  $s$  be two non-negative rational numbers, where  $r = C(\frac{a}{b})$ ;  $s = C(\frac{c}{d})$ . We call the difference of two rational numbers  $r$  and  $s$  a rational number  $u$ , denoted  $u = r - s$ , where  $u = C(\frac{ad-bc}{bd})$ , if  $ad - bc$  is the nature number. The rule for corresponding each pair of rational numbers  $r$ ,  $s$  with a rational number  $u$  mentioned above is called subtraction of rational numbers, in which  $r$  is the number to be subtracted,  $s$  is the subtraction number and  $u$  is the difference and  $r - s$  is also called the difference.

**Example 3.38.** Let  $r$  and  $s$  be two rational numbers whose representative fractions are  $\frac{8}{9}$  and  $\frac{7}{12}$ , respectively. We have:  $r - s = C(\frac{8.12-9.7}{9.12}) = C(\frac{11}{36})$ .

**Theorem 3.27** (Properties of subtraction of rational numbers):

Suppose  $r$ ,  $s$ ,  $t$  are any three rational numbers. Then:

(i)  $r - s = u$  if and only if  $u + s = r$   
(ii)  $r(s - t) = rs - rt$ , if either side is meaningful.

*Proof:*

(i) Suppose  $\frac{a}{b}$ ,  $\frac{c}{d}$ ,  $\frac{m}{n}$ , that in order are the representative fractions of the rational numbers  $r$ ,  $s$ ,  $u$ . By definition, we have  $r - s = C(\frac{ad-bc}{bd}) = C(\frac{m}{n}) = u$  if and only if and  $-bcn = bdm$  or  $= bdm + bcn$ . Inferred  $\frac{a}{b} \sim \frac{dm+cn}{dn}$ . From here we can deduce what must be proven.

(ii) Let  $u = s - t$ , from (i) we deduce  $s = u + t$ . We have:  $rs = r(u + t) = ru + rt = r(s - t) + rt$ . From here, we deduce what must be proven.

#### 3.3.3.3. Division

**Theorem 3.28:**

Suppose  $r$  and  $s$  are two rational numbers, in which  $s$  is different from 0. Then there exists only one rational number  $q$ , such that  $qs = r$ .

*Proof:*

Therefore  $s \neq 0$ , there exists an inverse rational number  $s^{-1}$ . Set  $q = rs^{-1}$ .

It is clear that  $qs = rs^{-1}s = r$ .

**Definition 3.23.** We call the rational number  $q$  in Theorem 3. ? the quotient of two rational numbers  $r$  and  $s$ , denoted  $q = r : s$ .

The rule for corresponding each pair of rational numbers  $r$ ,  $s$  with a rational number  $q$  above is called division of rational numbers, in which  $r$  is the dividend,  $s$  is the divisor and  $q$  is the quotient,  $r : s$  is also called the quotient.

**Example 3.39.**

Let  $r$  and  $s$  be two rational numbers whose representative fractions are  $\frac{8}{9}$  and  $\frac{7}{12}$ , respectively. We have:

$$r : s = C\left(\frac{8.12}{9.7}\right) = C\left(\frac{32}{21}\right).$$

**Remark:** From the above results, we see:

1. Addition and multiplication of rational (non-negative) numbers are always possible.
2. Subtraction of rational numbers is not always possible.
3. Division of any rational number by a non-zero rational number is always possible.

#### 3.3.3.4. Fraction formation in primary school

In the primary math curriculum, fraction content is officially presented in math grades 4 and 5. It includes the following content:

- Form the concept of fractions;
- Compare fractional numbers;
- Fraction calculations;
- Mixed numbers;
- Solve problems with fractions.

##### a) Form the concept of fractions in primary school

The concept of fractions is formally presented in Math grades 4 and 5. It includes the following content:

- Through symbols, the concept of fractions (less than 1) is formed;
- From division with remainder comes the concept of fractions;
- Introduce how to read, write and recognize the structure of a fraction;
- Introduce the concept of mixed numbers.

Such as:

- From the symbol of a shape (circle, square, paper tape, ...) divided into equal parts, some of which are colored, we form the concept of fractions less than 1.

- Through some division problems with remainders (for example, dividing 3 cakes by 4 people, dividing 5 oranges by 4 people, etc., we arrive at fractions) to form the concept of fractions (less than or greater than 1).  $\frac{3}{4}$ ;  $\frac{5}{4}$ ; ...

From the above concepts, we conclude for students:

1. The structure of a fraction includes: the numerator is a natural number written in dashes; The denominator is a non-zero natural number written under strikethrough.
2. The quotient of dividing a natural number by a non-zero natural number can be written as a fraction, the numerator is the dividend and the denominator is the divisor.
3. Every natural number can be written as a fraction with the numerator being that natural number and the denominator equal to 1.

- From the need to perform 2 cakes and  $\frac{3}{4}$ . The cake, we form gives students the concept of mixed numbers  $2\frac{3}{4}$ .

##### *b) Comparing fractions in primary school*

In the primary math curriculum, comparison relationships between fractions are presented in Grade 4 Math. Includes the following contents:

- Introduce the concept of equivalent fractions (which is the concept of equivalent fractions we built in the above section).
- Form concepts and consolidate fraction reduction skills;
- Form concepts and develop rules for congruent denominators of fractions;
- Develop rules for comparing two fractions (with and without the same denominator).

Such as:

- From the symbol of a piece of paper, we form for students the concept of two equivalent fractions;
- Based on the concept of two equal fractions, we form the concept and rules for reducing fractions; the concept and rules for reducing the denominators of fractions;
- Using visual images, form for students rules for comparing two fractions (with or without the same denominator).

##### *c) Construct mathematical operations in fractions*

Fractions are formed for 4th graders in four steps:

1. From practical problems combined with symbols, form the meaning of each operation;
2. Form rules for practicing each mathematical operation (addition, subtraction, multiplication and division of fractions);
3. Introduce properties of fraction calculations.
4. Practice skills to practice calculations.

Detail:

- Use paper symbols divided into equal parts from textbooks to form the meaning and practice rules for adding (or subtracting) two fractions with the same denominator.
- Applying the same denominator method, the textbook forms the meaning and rules for practicing addition (or subtraction) of two fractions with different denominators.
- From a practical problem about calculating the area of a rectangle combined with the symbol of a piece of cardboard divided into equal parts, the textbook forms the meaning and practice rules for multiplying two fractions.
- From a practical problem of calculating the length of a rectangle when knowing the area and width of that shape, the textbook forms the meaning and rules for practicing division of two fractions.
- The properties (commutative, associative, distributive, multiplying a number by a sum, ...) of operations on fractions are derived directly from the corresponding properties of operations on the set of natural numbers through analogical reasoning (in practice sessions).

##### *d) Solving fractions in primary school*

Fraction problems in primary school can be divided into four types:

- Form 1. Math on fraction structure;
- Form 2. Math about comparing fractions;
- Form 3. Math about operations on fractions;
- Form 4. Mathematics has typical writing on fractions;

Below we illustrate examples for each type of math.

##### **Form 1. Math on fraction structure**

**Example 3.40.** Write fractions:

1. The sum of the numerator and denominator is 8;
2. Greater than 1 and whose product of the numerator and denominator is 12.

###### **Solution**

a) The number 8 can be analyzed as the sum of the following pairs of numbers: 0 and 8; 1 and 7; 2 and 6; 3 and 5; 4 and 4. Fractions whose sum of numerator and denominator is 8 are:

$$\frac{0}{8}, \frac{1}{7}, \frac{7}{1}, \frac{2}{6}, \frac{6}{2}, \frac{3}{5}, \frac{5}{3}, \frac{4}{4}.$$

b) The number 12 can be analyzed as a product of the following pairs of numbers: 1 and 12; 2 and 6; 3 and 4. Fractions greater than 1 where the product of the numerator and denominator is equal to 12 are:

$$\frac{12}{1}, \frac{6}{2}, \frac{4}{3}.$$

**Example 3.41.** The product of the numerator and denominator of a fraction less than 1 is 315. When we divide both the numerator and denominator of that fraction by 3, we get the simplest fraction. Find that fraction.

**Solution** The number 315 can be analyzed as a product of the following pairs of numbers: 1 and 315; 3 and 105; 5 and 63; 7 and 45; 9 and 35; 15 and 21.

The fractions greater than 1 whose product of the numerator and denominator is 315 is:

$$\frac{1}{315}; \frac{3}{105}; \frac{5}{63}; \frac{7}{45}; \frac{9}{35}; \frac{15}{21}$$

Using the trial and selection method, we get the fraction, we need to find as:  $\frac{3}{105}; \frac{15}{21}$ .

**Example 3.42.** Simplify the following fraction:

$$a) \frac{232323}{414141};$$

$$b) \frac{132132}{231231}.$$

**Solution** We have:

$$a) \frac{232323}{414141} = \frac{232323 \cdot 10101}{414141 \cdot 10101} = \frac{23}{41}.$$

$$b) \frac{132132}{231231} = \frac{132132 \cdot 1001}{231231 \cdot 1001} = \frac{132}{231} = \frac{132 \cdot 33}{231 \cdot 33} = \frac{4}{7}.$$

**Form 2. Math about comparing fractions**

**Example 3.43.** Arrange the following fractions:

$$a) \frac{5}{7}; \frac{3}{4}; \frac{5}{8} \text{ in order from greatest to least;}$$

$$b) \frac{4}{7}; \frac{2}{5}; \frac{8}{11} \text{ in order from least to greatest.}$$

**Solution** a) Reducing the denominators of the given fractions gives us:

$$\frac{5}{7} = \frac{40}{56}; \frac{3}{4} = \frac{42}{56}; \frac{5}{8} = \frac{35}{56}.$$

Because  $\frac{42}{56} > \frac{40}{56} > \frac{35}{56}$ , so the given fractions arranged in order from greatest to least

$$\text{are: } \frac{3}{4}; \frac{5}{7}; \frac{5}{8}.$$

b) Reducing the number of pupils to the given fractions gives us:

$$\frac{4}{7} = \frac{8}{14}; \frac{2}{5} = \frac{8}{20}.$$

Because  $\frac{8}{20} < \frac{8}{14} < \frac{8}{11}$ , so the given fractions arranged in order from least to greatest

$$\text{are: } \frac{2}{5}; \frac{4}{7}; \frac{8}{11}.$$

**Example 3.44.** Without using the same denominator, write the following fractions in order from least to greatest:

$$\frac{45}{7}; \frac{35}{9}; \frac{17}{4}.$$

**Solution** We have:

$$\frac{45}{7} = 6\frac{3}{7}; \frac{35}{9} = 3\frac{8}{9}; \frac{17}{4} = 4\frac{1}{4}.$$

Since  $3 < 4 < 6$ , the given fractions in order from least to greatest are:  $\frac{35}{9}; \frac{17}{4}; \frac{45}{7}$ .

##### **Form 3. Math about operations on fractions**

**Example 3.45.** Calculate the value of the expression:

$$a) \frac{1414}{2121} + \frac{1313}{1414};$$

$$b) \frac{135135}{189189} - \frac{112112}{224224}.$$

**Solution**

$$a) \frac{1414}{2121} + \frac{1313}{1414} = \frac{14}{21} + \frac{13}{7} = \frac{2}{7} + \frac{13}{14} = \frac{4+13}{14} = \frac{17}{14}.$$

$$b) \frac{135135}{189189} - \frac{112112}{224224} = \frac{135}{189} - \frac{112}{224} = \frac{5}{7} - \frac{1}{2} = \frac{10-7}{14} = \frac{3}{14}.$$

**Example 3.46.** Calculate:

$$a) \frac{9}{14} + \frac{5}{8} + \frac{6}{7} + \frac{17}{24};$$

$$b) \frac{2013}{2015} \times \frac{2008}{2011} \times \frac{2015}{2012} \times \frac{2011}{2013} \times \frac{1006}{1004}.$$

**Solution** Applying the commutative and associative properties of addition and multiplication we have:

$$a) \frac{9}{14} + \frac{5}{8} + \frac{6}{7} + \frac{17}{24} = \left(\frac{9}{14} + \frac{6}{7}\right) + \left(\frac{5}{8} + \frac{17}{24}\right) \\ = \frac{9+12}{14} + \frac{15+17}{24} = \frac{21}{14} + \frac{32}{24} = \frac{3}{2} + \frac{4}{3} = \frac{9+8}{6} = \frac{17}{6}.$$

$$b) \frac{2013}{2015} \times \frac{2008}{2011} \times \frac{2015}{2012} \times \frac{2011}{2013} \times \frac{1006}{1004} = \left(\frac{2013}{2015} \times \frac{2015}{2012}\right) \times \left(\frac{2008}{2011} \times \frac{2011}{2013}\right) \times \frac{1006}{1004} \\ = \frac{2013}{2012} \times \frac{2008}{2013} \times \frac{1006}{1004} = \frac{2008}{2012} \times \frac{1006}{1004} = \frac{1004 \times 2 \times 1006}{1006 \times 2 \times 1004} = 1.$$

##### **Form 4. Math has typical text on fractions**

**Example 3.47.** Two women went to the market to sell eggs. After calculating, one woman said: "2/5 number of my eggs is 1.5 times more than 4/7 number of yours and

$\frac{2}{5}$  number of my eggs more than  $\frac{4}{7}$  number of yours are 40 eggs." How many eggs did each woman bring to the market to sell?

**Solution** Because  $1.5 = \frac{3}{2}$ , so according to the topic we have the following diagram:

![](e9bc763ebea46fe89aede23775517f44_img.jpg)

$\frac{2}{5}$  number of eggs of the first woman: ? egg

$\frac{4}{7}$  number of eggs of the second woman: ? egg 40 eggs

$\frac{2}{5}$  the number of eggs of the first woman is:  $40 \times 3 = 120$  (eggs)

The number of eggs the first woman brought to the market to sell were:  
 $120 : 2 \times 5 = 300$  (eggs)

$\frac{4}{7}$  the number of eggs of the second woman is:  $40 \times 2 = 80$  (eggs)

The number of eggs the second woman brought to the market to sell was:  
 $80 : 4 \times 7 = 140$  (eggs)

Answer: the first woman: 300 eggs;  
the second woman: 140 eggs.

##### **Example 3.48.**

Two transport teams are assigned to transport a shipment: after team I transported  $\frac{3}{5}$  the number of delivered goods and team II transported  $\frac{3}{8}$  the number of the delivered goods, the remaining goods of both teams are 560 tons, of which the remaining goods of team I are equal to  $\frac{3}{4}$  the remaining goods of team II. How many tons of goods were assigned to each team to transport initially?

**Solution** According to the topic, we have the following diagram:

![](79607caa47ed192b11a2c7b17f0b88dd_img.jpg)

Remaining goods of team I: ? ton

Remaining goods of team II: ? ton

560 tons

The remaining goods of team I are:  $560 : (3 + 4) \times 3 = 240$  (tons)

The remaining goods of team II are:  $560 - 240 = 320$  (tons)

The number of goods that team I initially delivered was:

![](044324e651f5e7bb5178c637b769cb76_img.jpg)

Diagram showing a horizontal line segment representing a quantity, with a dashed line indicating the total length. The total length is marked by tick marks. The total length is labeled as 240 tons.

? ton  
 $240 : 2 \times 5 = 600$  (tons)

The number of goods that team II was initially assigned to transport were:

![](f217ea7a6e9347a9ca4d6173ed57c33e_img.jpg)

Diagram showing a horizontal line segment representing a quantity, with a dashed line indicating the total length. The total length is marked by tick marks. The total length is labeled as 320 tons.

? ton  
 $320 : 5 \times 8 = 512$  (tons)  
Answer: Team I: 600 tons;  
Team II: 512 tons.

### 3.3.4. *Mathematical basis of decimal numbers in primary school*

#### 3.3.4.1. *Decimal fraction*

Fractions  $\frac{3}{10}$ ;  $\frac{116}{100}$ ;  $\frac{35}{1000}$ ;  $\frac{12}{1}$ ; ... all have denominators that are powers of 10 with natural exponents. Fractions of this type are often encountered in quantity measurements,

**Example 3.49.**

- The length of the table edge is  $1\text{m}25\text{cm}$  or  $1\text{m}\frac{25}{100}\text{m}$ ;
- The package weighs  $365\text{g}$  or  $\frac{365}{1000}\text{kg}$ ;

**Definition 3.24.** Fraction  $\frac{a}{b}$  is called a decimal fraction if and only if denominator  $b$  is a power of 10 with a natural exponent ( $b = 10^n, n \in \mathbb{N}$ ).

For example, fractions  $\frac{3}{10}$ ;  $\frac{116}{100}$ ;  $\frac{35}{1000}$ ;  $\frac{12}{1}$ ; ... are decimal fractions.

Fraction  $\frac{3}{4}$  not a decimal fraction, but  $\frac{3}{4}$  again as a decimal fraction  $\frac{75}{100}$ .

**Definition 3.25.** Fraction  $\frac{a}{b}$  is called representable as a decimal if and only if it is equal to a decimal fraction.

For example, fractions  $\frac{1}{2}$ ;  $\frac{24}{25}$ ;  $\frac{15}{8}$ ; ... are fractions that can be expressed as decimals;

fractions  $\frac{2}{3}$ ;  $\frac{9}{14}$ ;  $\frac{35}{24}$ ; ... cannot be expressed in decimal form.

Below we give a sign to identify whether a fraction can be expressed as a decimal or not:

**Theorem 3.29** (Conditions for fractions to be expressed as decimals):

To simplify fractions  $\frac{p}{q}$  expressed in decimal form, the necessary and sufficient condition is that its denominator  $q$  contains no prime divisors other than 2 and 5.

*Proof:*

*Sufficient conditions.* Suppose  $q$  only has prime divisors 2 and 5. So  $q = 2^n 5^m$ . Suppose  $n \le m$ . We have  $\frac{p}{q} = \frac{p}{2^n 5^m} = \frac{p \cdot 2^{m-n}}{2^m 5^m} = \frac{p \cdot 2^{m-n}}{10^m}$ . So fraction  $\frac{p}{q}$  can be expressed in decimal form.

*Prerequisites.* Assume simplified fractions  $\frac{p}{q} = \frac{a}{10^n}$ . It follows that  $aq = p \cdot 10^n$ .

Suppose  $k$  is a prime divisor other than 2 and 5 of  $q$ . It follows that  $k$  is a divisor of  $p$ . So  $k = \text{UC}(p; q)$ . Because fractions  $\frac{p}{q}$  minimally so  $k = 1$ . This completes the proof

**Example 3.50.**

- Fractions  $\frac{127}{40}$ ;  $\frac{13}{16}$ ;  $\frac{31}{125}$  are all minimal and their denominators only have prime divisors of 2 or 5, so they can be expressed as decimals.

- Fractions  $\frac{7}{9}$ ;  $\frac{13}{14}$ ;  $\frac{31}{120}$  are all minimal and the denominator of each fraction has prime divisors other than 2 and 5 so they cannot be expressed as a decimal.

- Fractions  $\frac{21}{14} = \frac{3}{2}$ ;  $\frac{13}{65} = \frac{1}{5}$  can all be expressed in decimal form.

#### 3.3.4.2. Non-negative decimal number

For convenience in calculation and use, a separate representation for decimal fractions is proposed.

**Definition 3.26.** A rational number  $r$  is called a non-negative decimal number (for brevity, we call it a decimal number), if it has a representative that is a decimal fraction, or in other words: its representative fraction can be represented as decimal form.

The set of all (non-negative) decimal numbers is denoted by  $Q_{+10}$ .

**Example 3.51.**

$$\frac{123}{10}; \frac{9}{16}; \frac{8}{100}; \frac{13}{40}; \frac{47}{10000} \in Q_{+10}; \\ \frac{9}{7}; \frac{17}{12}; \frac{17}{30} \notin Q_{+10}$$

As we know, every decimal number has a representation as a decimal fraction. This representation has the disadvantage of being cumbersome and inconvenient in computational practice. Therefore, we often represent decimal numbers in condensed form. Example.

$+ \frac{123}{10} = 12.3$  and read as twelve whole units and three tenths of the unit or for brevity, we read: twelve point three.

$+ \frac{71}{100} = 0.71$  and read as: zero whole unit and seventy-one hundredths of a unit or for brevity we read: zero point seventy-one.

$+ \frac{43}{10000} = 0.0043$  and read as zero whole unit and forty-three ten thousandths of a unit or for brevity we read: zero point zero zero four three.

So the condensed form of a decimal number is the written form without a denominator of a decimal fraction according to the following rules:

- Remove the denominator, and use a comma to divide the digits of the numerator into two groups: the first group to the right of the comma has the same number of digits as the number of zeros in the denominator; The second group to the left of the comma includes the remaining digits of the numerator.

- If the number of digits in the numerator is less than or equal to the number of zeros in the denominator, we write additional zeros in front of the numerator before using comma division.

*The number to the left of the comma is called the integer part, and the group of digits to the right of the comma is called the decimal part of that number.*

For example, the decimal number 32.0013 has an integer part of 32 and a decimal part of the group of digits 0013.

Thus, each decimal number has two ways of representation: fractional form and condensed form.

#### 3.3.4.3. Order relationship in a set of non-negative decimal numbers

Because  $Q_{+10} \subset Q$ . So, when comparing two decimal numbers, we compare two corresponding rational numbers. Detail:

**Definition 3.27.** Let  $r$  and  $s$  be two decimal numbers. We say that the decimal number  $r$  is less than or equal to the decimal number  $s$ , denoted by  $r \le s$ , if rational number  $r$  is less than or equal to rational number  $s$ .

##### Example 3.52.

Compare the two decimal numbers  $r = 9.63$  and  $s = 12.1$ .

$$\text{We have } 9.63 = \frac{963}{100} < \frac{121}{10} = 12.1.$$

Building an order relationship in a set of decimal numbers as above has theoretical advantages, but has the disadvantage of being cumbersome in comparison practice (must include comparing fractions). Therefore, when comparing decimal numbers, we often use one of the two rules below:

**Rule 1.** To compare a decimal number with a decimal number, do the following:

1. Make their number of decimal places equal (by adding zeroes to the missing rows);
2. Removing the comma, we get two natural numbers;
3. Compare the two natural numbers you just received. Whichever number is larger will be the corresponding decimal number. If two natural numbers are equal, then the two corresponding decimal numbers are also equal.

**Rule 2.** To compare a decimal number with a decimal number, do the following:

1. Compare the integer part with the integer part, the number with the larger integer part will be larger;
2. If their integer parts are equal, we compare the tenths digit, the number with the larger tenths digit will be larger;
3. If their tenths digits are also equal, we compare the hundredths digits and so on until we find a larger number.
4. If the integer part and the digits in their decimal part are equal, then the two numbers are equal.

**Example 3.53.** Compare the two decimal numbers  $r = 9.63$  and  $s = 12.1$ .

**Method 1.** We have  $12.1 = 12.10$ . Since  $963 < 1210$ ,  $9.63 < 12.1$ .

**Method 2.** Since  $9 < 12$ ,  $9.63 < 12.1$ .

### 3.3.5. Infinite repeating decimal number

In the set of natural numbers  $\mathbb{N}$ , we have shown that between two natural numbers  $a$  and their successor is a space. In the set of rational numbers  $\mathbb{Q}_+$ . We show that between any two rational numbers there always exists an infinite number of other rational numbers.

The theorem below confirms the similarity of decimal numbers  $\mathbb{Q}_{+10}$  as in the set of rational numbers:

**Theorem 3.30** (About density of decimal numbers)

For every rational number  $r$ , for every natural number  $k$ , there exists a decimal number  $t$  such that:

$$r - \frac{1}{10^k} < t < r + \frac{1}{10^k}$$

Or in other words: every rational number  $r$  can be approximated by a decimal number  $t$  with arbitrarily small errors.

*Proof:*

Suppose  $r \in Q_+$ ;  $k \in N$ . According to Archimede's axiom, there exists a natural number  $n$  such that  $r < n$ . We set:

$X = \{a \in N : a \le 10^k r\}$ . Obviously  $X \subset N, X \neq \emptyset$  and **blocked** on. From here, we deduce that  $X$  has the greatest element, denoted  $M$ . Then  $M \le 10^k r < M+1$  or

$$\frac{M}{10^k} \le r < \frac{M}{10^k} + \frac{1}{10^k}.$$

Put  $t = \frac{M}{10^k}$ . This completes the proof

**Attention:** Theorem 3.32 theoretically confirms the existence of the decimal number  $t$  but does not provide an algorithm to find this decimal number.

In practical calculation, we find  $t$  as follows: Suppose we have to find a decimal number that approximates a rational number  $r = \frac{a}{b}$  with error less than  $10^{-k}$ .

Let  $M$  be the approximate quotient of division  $a \cdot 10^k$  divided by  $b$ . Then  $t = \frac{M}{10^k}$  is the decimal number to find.

**Example 3.54.1)** Approximate rational numbers  $r = \frac{7}{11}$  by a decimal number with an error less than  $10^{-5}$ .

**Solution** We divide 7.105 by 11 to get 63636 (residual 4). So the decimal number to find is 0.63636.

2) Approximate rational numbers  $r = \frac{43}{22}$  by a decimal number with an error less than  $10^{-3}$ .

**Solution** We divide  $43 \cdot 10^3$  by 22 to get the quotient 1954 (remainder 12). So the decimal number to find is 1.954.

In the previous Exercises, we learned that each number is a simplified fraction  $r = \frac{a}{b}$  there are two possibilities:

- If the denominator  $b$  does not contain any prime divisors other than 2 and 5, then  $r$  is a decimal number;
- If the denominator  $b$  contains a prime divisor other than both 2 and 5, then  $r$  is not a decimal number. In this case, according to **Theorem 3. ?**,  $r$  can be approximated by a decimal number with arbitrarily small errors.

In this section, we show that such rational numbers can be represented by a “decimal” number in the broad sense.

First, let's start with a specific problem: Let's approximate the fraction  $r = \frac{13}{11}$  by decimal numbers with different tolerances. Applying the method above, we get the following results:

- If the error does not exceed  $\frac{1}{100}$  then we get the number 1.18;

- If the error does not exceed  $\frac{1}{10000}$  then we get the number 1.1818;

- If the error does not exceed  $10^{-6}$  then we get the number 1.181818;

- ...

Continuing the above process we arrive at the following result:

- Never get a decimal equal  $\frac{13}{11}$ .

- If we continue the above process forever, we will get a "decimal" number with an infinite number of digits in the decimal part.

- The digits in the decimal part will repeat cyclically with a period of 18. In this case we write:

$$\frac{13}{11} = 1.181818\ldots \text{ or } \frac{13}{11} = 1. (18)$$

and is called an infinite repeating decimal number with a period of 18.

Next we consider the same problem with fractions  $r = \frac{855}{22}$ . Using similar arguments as above, we get the following result:

- If the error does not exceed 10-3, we get the decimal number 38.863;

- If the error does not exceed 10-5, we get the decimal number 38.86363;

- If the error does not exceed 10-7, we get the decimal number 38.8636363.

$$\text{So } \frac{855}{22} = 38.8636363\ldots$$

We get an infinite repeating decimal number but the period (which is 63) does not start immediately after the decimal point but starts from the second decimal place. Such numbers are called infinite recurring decimals. In this case, we write:  $r = 38.9(63)$

More generally: assume fractions  $\frac{a}{b}$  not a decimal number. We perform

successive divisions of  $a$  by  $b$  (by adding the digit 0 to the right of the remainder after each division step and continuing to divide), we will encounter a certain remainder  $r$  that we encountered in the previous division step. Then the process will repeat so the digits in the quotient will also repeat cyclically. The received decimal number has an infinite number of digits in the decimal part, including a group of digits that repeat cyclically. That group of repeating digits is the partial quotient between two equal

remainders called the period of that infinite repeating decimal number. If the period begins immediately after the comma, it is called a simple repeating decimal; otherwise, it is called an infinite repeating decimal.

### 3.3.6. *Content of teaching decimals in primary school*

In the primary math curriculum, content about decimals is presented in grade 5 math. It includes the following content:

- Form the concept of decimal numbers;
- Compare decimal numbers;
- Decimal calculations;
- Solve math problems with decimals.

#### 3.3.6.1. *Form the concept of decimal numbers in primary school*

The concept of decimals in grade 5 math includes the following contents:

- Form the concept of decimal numbers;
- Introduce how to read, write and recognize the structure of a decimal number;
- Introducing the rows of a decimal number;
- Use decimals to represent quantitative measurements.

For example, through specific operations, the concept of "decimal numbers" is formed for students in two ways:

- A decimal is a way of writing a decimal fraction without a denominator, Example.

$$\frac{1}{10} = 0.1; \frac{8}{100} = 0.08; \frac{1024}{1000} = 1.024; \dots$$

- Decimal numbers are a way to represent quantity measurements (from many units of measurement to one unit of measurement or from a smaller unit of measurement to a larger unit), Example.

$$3\text{m } 7\text{dm} = 3.7\text{m}; 12\text{m} = 0.012\text{km}; 3\text{kg } 50\text{g} = 3.050\text{ kg};$$

$$2\text{ tons } 35\text{kg} = 2.035\text{ tons}; 458\text{cm}^2 = 0.0458\text{m}^2; \dots$$

From the above concepts, we conclude for students:

- The structure of a decimal number includes: the integer part is the natural number to the left of the comma and the decimal part is the group of digits to the right of the comma. The integer part and the decimal part are separated by a comma. For example, the number 12.045 has an integer part of 12, a decimal part of 045 and is read as twelve point zero four five.

- From the structure of decimal numbers, we form the concept of tenths, hundredths, and thousandths of decimals. For example, the decimal number 12.045 has a tenths place of 0, a hundredths place of 4, and a thousandths place of 5.

#### 3.3.6.2. *Comparison of decimal numbers in primary school*

Similar to fractions, when comparing two decimals we aim for two situations:

- This number is greater or less than that number;
- Draw the conclusion that those two numbers are equal.

Through measuring quantities (lengths), we bring the comparison of decimal numbers to the comparison of natural numbers (which the student has mastered before).

Specifically: from the problem "Compare 35.7m and 35.698m" we make the following comments:

- Their integer parts are equal (both equal to 35m);

- The decimal part of 35.7m is  $\frac{7}{10}m = 700\text{mm}$ ; The decimal part of 35.698m is

$$\frac{698}{100}m = 698\text{mm}. \text{ Because } 700\text{mm} > 698\text{mm} \quad \frac{7}{10}m > \frac{698}{1000}m.$$

Therefore  $35.7\text{m} > 35.698\text{m}$ .

From here we draw the rule: To compare two decimal numbers, we do the following:

a) *Compare the integer part of those two numbers. The number with the larger integer part will be larger;*

b) *If their integer parts are equal, compare the decimal parts, respectively from the tenths, hundredths, thousandths, ..., to the same row, which decimal has the greatest digit in the corresponding place. more will be bigger.*

c) *If the integer part and the decimal digits of those two numbers are equal, then those two numbers are equal.*

At the same time, the textbook also draws a rule: If we add (or delete) the digit 0 at the end of the decimal part of a decimal number, we get a decimal number equal to it.

#### 3.3.6.3. Build mathematical operations in the set of decimal numbers in primary school

Operations in the set of decimal numbers are presented in Grade 5 Math in five steps:

1) From practical problems, form the meaning of each operation;

2) Forming rules for practicing each mathematical operation (addition, subtraction, multiplication and division of decimal numbers);

3) Introduce the properties of decimal calculations;

4) Introduce mental math rules: mentally multiply and divide by 10; 100; 1000; ...

5) Practice skills to practice calculations.

Detail:

- From the problem of adding the length of two line segments, the textbook forms the meaning and practice rules for adding two decimal numbers;

- The same goes for subtraction;

- From a practical problem about calculating the perimeter of a triangle with three equal sides, the textbook forms the meaning and practice rules for multiplying decimals;

- Division of decimal numbers is introduced through the following steps:

+ Divide decimal for a natural number;

+ Divide natural number gives a natural number whose quotient is a decimal;

+ Divide a natural number for a decimal number;

+ Divide a decimal number for a decimal number.

Each step comes from a practical problem about measuring length quantities.

- The properties (commutative, associative, distributive, multiplying a number by a sum, ...) of operations on decimal numbers are derived directly from the corresponding properties of operations on the set of digits naturally through similar reasoning (in practice sessions).

#### 3.3.6.4. Solve math problems with decimals in primary school

Math problems about decimals in primary school can be divided into four types:

Form 1. Mathematics on the structure of decimal numbers;

Form 2. Math about comparing decimals;

Form 3. Math about operations on decimal numbers;

Form 4. Math about percentages.

Below, we illustrate examples for each type of math.

##### Form 1. Math about the structure of decimal numbers

**Example 3.55.** Write the following numbers as decimals:

$$a) \frac{7}{100};$$

$$b) \frac{123}{10};$$

$$c) \frac{9}{40}.$$

**Solution**

$$a) \frac{7}{100} = 0.07;$$

$$b) \frac{123}{10} = 12.3;$$

$$c) \frac{9}{40} = \frac{225}{1000} = 0.225.$$

**Example 3.56.** Write the measurements below as decimals:

a) 25dm 5cm with unit of meter;

b) 70g with unit of kilogram;

c)  $5\text{dm}^2 8\text{cm}^2$  in square meters;

d)  $2\text{m}^2 5\text{cm}^2$  with units of square decimeters.

**Solution**

$$a) 25\text{dm}5\text{cm} = \frac{255}{100} \text{ cm} = 2.55\text{m}$$

$$b) 70\text{g} = \frac{70}{1000} \text{ kg} = 0.070\text{kg};$$

$$c) 5\text{dm}^2 8\text{cm}^2 = \frac{508}{10000} \text{ m}^2 = 0.0508\text{m}^2;$$

$$d) 2\text{m}^2 5\text{cm}^2 = \frac{20005}{10000} = 2.0005\text{m}^2.$$

**Example 3.57.** Given three digits 0, 1, 2. Write all three-digit decimal numbers in both integer and decimal parts less than 20 so that each given digit appears in the writing exactly once.

**Solution**

The decimal numbers to find are:

0.12  
0.21;  
1.02;  
1.20;  
2.01;  
2.10;  
10.2;  
12.0.

**Example 3.58.** The tenths and hundredths digits of a two-digit decimal are two consecutive even numbers written in ascending order. The product of the decimal digits is equal to the integer part of that number. The digits in both the integer part and the decimal part are different. Find that decimal number.

**Solution** The decimal part of the decimal number to find can be: 02; 24; forty six; 68.

Tahas the following table:

| Decimal part | Natural parts | Decimal | Conclude |
|--------------|---------------|---------|----------|
| 02           | 0             | 0.02    | Type     |
| 24           | 8             | 8.24    | Select   |
| 26           | 24            | 24.64   | Type     |
| 68           | 48            | 48.68   | Type     |

The decimal number to find is 8.24.

**Form 2. Math about comparing decimal numbers**

**Example 3.59.** Write the following decimal numbers:

a) 5.90; 8.93; 9.029; 4.94 in order from least to greatest;  
b) 72.037; 72.730; 72.703; 72.307 in order from greatest to least.

**Solution**

a) The given numbers are written in order from least to greatest are:  
4.94; 5.90; 8.293; 9.029.  
b) The given numbers written in order from greatest to least are:  
72.730; 72.703; 72.307; 72.037.

**Example 3.60.** Write 5 decimals between the numbers 2.5 and 2.6.

**Solution**

The decimal number to find is:  
2.51; 2.52; 2.53; 2.54; 2.55.

**Example 3.61.** Replace a by the appropriate digit to:

$$0.46 < 0.4a6 < 0.485$$

**Solution**

- For  $0.46 < 0.4a6$  then  $a = 6, 7, 8$  or  $9$ ;
- For  $0.4a6 < 0.485$  then  $a = 1, 2, 3, 4, 5, 6$  or  $7$ ;
- From there, it follows that for  $0.46 < 0.4a6 < 0.485$ , then  $a = 6$  or  $7$ .

**Form 3. Math about operations on decimal numbers**

**Example 3.62.** Find y:

a)  $51.42 - y = 3.45 : 0.12$  b)  $8.064 \times y = 2.4 : 0.25$   
c)  $y : 5.6 = 0.8 \times 2.25$  d)  $2.85 : y = 1.4 - 0.65$

**Solution**

a)  $51.42 - y = 3.45 : 0.12$   
 $51.42 - y = 28.75$   
 $y = 51.42 - 28.75$   
 $y = 22.67$

b)  $8.064 \times y = 2.4 : 0.25$   
 $8.064 \times y = 9.6$   
 $y = 8.064 : 9.6$   
 $y = 0.84$

c)  $y : 5.6 = 0.8 \times 2.25$   
 $y : 5.6 = 1.8$   
 $y = 1.8 \times 5.6$   
 $y = 10.08$

d)  $2.85 : y = 1.4 - 0.65$   
 $2.85 : y = 0.75$   
 $y = 2.85 : 0.75$   
 $y = 3.8$

**Example 3.63.** Give  $A = \frac{(x+4.25):0.5}{(5.25-4.75)\times 2.5}$ .

a) Find A, when  $x = 5$ ;  
b) Find x so that A = 12.

**Solution** a)  $x = 5$ , we have:

$$A = \frac{(5+4.25):0.5}{(5.25-4.75)\times 2.5} = \frac{9.25:0.5}{0.5\times 2.5} = \frac{18.5}{1.25} = 14.8.$$

b) When A = 12, we have:

$$\begin{aligned}\frac{(x + 4.25):0.5}{(5.25 - 4.75) \times 2.5} &= 12 \\ \frac{(x + 4.25):0.5}{0.5 \times 2.5} &= 12 \\ \frac{(x + 4.75):0.5}{1.25} &= 12 \\ (x + 4.75):0.5 &= 12 \times 1.25 \\ (x + 4.75):0.5 &= 15 \\ x + 4.75 &= 15 \times 0.5 \\ x + 4.75 &= 7.5 \\ x &= 7.5 - 4.75 \\ x &= 2.75.\end{aligned}$$

**Example 3.64.** Calculate the value of the following expression in the most reasonable way:

$$a) \frac{0.2 \times 213 \times 7 + 0.14 \times 2460 + 54.1 \times 14}{1 + 4 + 7 + \dots + 64 - 365};$$
$$b) \frac{(213.78 - 43.75 \times 0.37) \times (49.6 \times 0.25 - 24.8 \times 8)}{5.13 \times 2.45 - 12.48 \times 0.75}.$$

**Solution**

a) We have:

$$\begin{aligned}0.2 \times 213 \times 7 + 0.14 \times 2460 + 54.1 \times 14 \\= 1.4 \times 213 + 1.4 \times 246 + 541 \times 1.4 \\= 1.4 \times (213 + 246 + 541) = 1.4 \times 1000 = 1400.\end{aligned}$$

Next, we calculate the value of the expression in the form:  $1 + 4 + 7 + \dots + 64$  is the sum of the terms of an equidistant sequence with the first term equal to 1, the last term equal to 64, the distance equal to 3, and the number. The terms of that sequence are:  $(64 - 1) : 3 + 1 = 22$  (number). The value of the expression in the form is:  $(1 + 64) \times 22 : 2 - 365 = 350$ .

The value of the given expression is:  $\frac{1400}{350} = 4$ .

b) We comment:  $49.6 : 0.25 - 24.8 \times 8 = 49.6 \times 4 - 49.6 \times 4 = 0$ .

So the value of the given expression is 0.

**Example 3.65.** Find a decimal number, knowing that when dividing that number by 2, then subtracting 1.8 and then multiplying by 2.5, the result is 37.5.

**Solution**

The number before multiplying by 2.5 is:

$$37.5 : 2.5 = 15$$

The number before subtracting 1.8 is:

$$15 + 1.8 = 16.8$$

The number to look for is:

$$16.8 \times 2 = 33.6.$$

**Example 3.66.**

Replace each letter in the following calculation by the appropriate number to get the correct calculation:

$$a) \overline{8a}.ba + \overline{c1}.4d = \overline{d4}.1c;$$

$$b) \overline{13}.ab: 2.6 = a.b.$$

Solution

a) We rewrite the calculation as follows:

$$\begin{array}{r} 8a.b.a \\ + c1.4d \end{array}$$

###### d 4.1 c

According to as a result of the calculation, the addition of the tens digit cannot be remembered. It follows that the addition of the tens digit can only be:  $8 + 1 = 9$ . So  $c = 1$  and  $d = 9$ .

Instead of calculating, we will find  $a = 2$  and  $b = 6$ .

Instead, we get the calculation we need to find:

$$82.62 + 11.49 = 94.11.$$

b) We rewrite the calculation as follows:

$$13 + 0.ab = 0.ab \times 26$$

$$0.ab \times 26 - 0.ab = 13$$

$$0.ab \times (26 - 1) = 13$$

$$0.ab \times 25 = 13$$

$$0.ab = 13 : 25 = 0.52$$

$$\text{Deduce } a = 5 \text{ and } b = 2.$$

$$\text{Thus, } 13.52 : 2.6 = 5.2$$

##### **Form 4. Math about percentages**

**Example 3.67.** Class 5A has 40 students, including 22 female students. What percentage of the whole class are female students?

###### **Solution**

The percentage of female students in the class 5A is:

$$22 : 40 = 0.55$$

$$0.55 = 55\%$$

Answer: 55%.

**Example 3.68.** Savings interest rate is 0.65%/month. Ms. Thu deposited 80,000,000 VND in savings. How much profit will she get after one month?

###### **Solution**

Ms. Thu's profit after one month is:

$$80,000,000 : 100 \times 0.65 = 520,000 \text{ (VND)}$$

Answer: 520,000 VND

**Example 3.69.** In the warehouse there are 60 tons of sticky rice. The amount of sticky rice accounts for 15% of the total amount of rice in warehouse. How many tons of rice are there in the warehouse?

###### **Solution**

Total quantity of rice in warehouse is:

$$60 : 15 \times 100 = 400 \text{ (tons)}$$

Answer: 400 tons of rice.

**Example 3.70.** A person who sells a fan for 200,000 VND earns a profit of 10% on the selling price. To make a profit of 15% of the original price, how much money must that person sell the fan for?

###### **Solution**

10% profit on the selling price means: If we consider the selling price as 100%, the interest accounts for 10%, the principal accounts for 90%.

The original price of that fan is:

$$200,000 : 100 \times 90 = 180,000 \text{ (VND)}$$

A profit of 15% of the original price means: If we consider the original price to be 100%, the profit is 15% and the selling price is 115%.

To make a profit of 15% of the original price, that person must sell the fan for:

$$180,000 : 100 \times 115 = 207,000 \text{ (VND)}$$

Answer: 207,000 VND.

**Example 3.71.** When increasing the radius of a circle by 10%, the area of the circle will increase by what percentage?

**Solution** Answer: 21%.

## 3.4. Rational numbers - Integers numbers

### 3.4.1. The need to build a set of rational numbers

In previous topics, we expanded the set of natural numbers  $\mathbb{N}$  to obtain the set of non-negative rational numbers. If we stop at the set of non-negative rational numbers:  $\mathbb{Q}_+$

- Many subtractions cannot be performed, for example,  $3 - 5, \frac{1}{4} - 4, \dots$
- Expressing the measurements of two opposite quantities will create difficulties, for example, height and depth, loss and gain, 0°C upper and 0°C lower temperatures, ...

Due to the development needs of mathematics and other scientific and technical fields, people expand the set of non-negative rational numbers  $\mathbb{Q}_+$  to add new numbers to overcome the above limitations.

### 3.4.2. Construct a set of rational numbers

Based on the Cartesian product  $\mathbb{Q}_+ \times \mathbb{Q}_+$ , we define the binary relationship as follows:

With  $(r; s)$  and  $(r'; s') \in \mathbb{Q}_+ \times \mathbb{Q}_+$ , we define:

$$(r; s) \sim (r'; s') \text{ if and only if } r + s' = r' + s.$$

From the definition we can easily deduce that " $\sim$ ", it is an equivalence relation defined on the set  $\mathbb{Q}_+ \times \mathbb{Q}_+$ .

Applying the quotient set theorem, we can divide the set  $\mathbb{Q}_+ \times \mathbb{Q}_+$  according to the equivalence relationship  $\sim$  and obtain the quotient set  $\mathbb{Q}_+ \times \mathbb{Q}_+/\sim$ .

We will call the quotient set  $\mathbb{Q}_+ \times \mathbb{Q}_+/\sim$  is the set of rational numbers and denote it by  $\mathbb{Q}$ . Each element of the set  $\mathbb{Q}$  is called a rational number.

Suppose  $\alpha \in \mathbb{Q}$ . Such  $\alpha$  is defined by an equivalence class whose representative element is  $(r; s) \in \mathbb{Q}_+ \times \mathbb{Q}_+$ . Thus,  $\alpha = \overline{(r; s)} \in \mathbb{Q} = \mathbb{Q}_+ \times \mathbb{Q}_+ / \sim$

It is easy to show that each rational number  $\overline{(r; s)}$  is uniquely determined by a representative element of one of the following three forms:  $(p; 0)$  or  $(0; p)$  (with  $p \in \mathbb{Q}_+$ ) or  $(0; 0)$ .

For convenience, we make the following convention:

a) If the rational number  $\alpha$  is determined by an equivalence class of the form  $\alpha = \overline{(r; 0)}$ , where  $r \neq 0$ , then we will write  $\alpha = +r$  or  $\alpha = r$  and call it a positive rational number.

b) If the rational number  $\alpha$  is determined by an equivalence class of the form  $\alpha = \overline{(0; r)}$ , where  $r \neq 0$ , then we will write  $\alpha = -r$  and call it a negative rational number.

c) If the rational number  $\alpha$  is determined by an equivalence class of the form  $\alpha = \overline{(0; 0)}$ , we will write  $\alpha = 0$  and call it a rational number zero or zero.

d) The number  $-r$  is called the lie of the number  $r$ .

e) In particular, we write  $1 = \overline{(1; 0)}$ .

Thus, the set of rational numbers  $\mathbb{Q}$  is decomposed into three disjoint sets:

$\mathbb{Q} = \mathbb{Q}^+ \cup \mathbb{Q}^- \cup \{0\}$ , where  $\mathbb{Q}^+$  is the set of positive rational numbers,  $\mathbb{Q}^-$  is the set of negative rational numbers.

### 3.4.3. Mathematical operations of integers numbers

Suppose  $\alpha$  and  $\beta$  are two rational numbers, where  $\alpha = \overline{(r; s)}$  and  $\beta = \overline{(r'; s')}$ . We define:

a) The sum of two rational numbers  $\alpha$  and  $\beta$  is a rational number  $\gamma$ , symbol  $\gamma = \alpha + \beta$ , is determined by the rule:  $\gamma = \overline{(r + r'; s + s')}$ .

The rule for corresponding each pair of rational numbers  $\alpha, \beta$  to a rational number  $\gamma$  mentioned above is called addition of rational numbers.

b) The product of two rational numbers  $\alpha$  and  $\beta$  is a rational number  $\delta$ , symbol  $\delta = \alpha\beta$ , is determined by the rule:  $\delta = \overline{(rr' + ss'; rs' + r's)}$ .

The rule for corresponding each pair of rational numbers  $\alpha, \beta$  to a rational number  $\delta$  mentioned above is called multiplication of rational numbers.

c) We call the difference of two rational numbers  $\alpha$  and  $\beta$  a rational number  $\rho$ , denoted by:  $\rho = \alpha - \beta$ , determined by the rule:

$$\rho = \alpha + (-\beta), \text{ where } -\beta \text{ is the lie of the number } \beta.$$

The rule for corresponding each pair  $\alpha, \beta$  of rational numbers to a rational number  $\rho$  mentioned above is called the retention of finite numbers.

d) We say that a rational number  $\beta$  is the inverse of a rational number  $\alpha$ , denoted by  $\beta = \alpha^{-1}$ , if:  $\alpha\beta = 1$ .

With two rational numbers  $\alpha$  and  $\beta$ , where  $\beta \neq 0$ , we definition: the quotient of  $\alpha$  division  $\beta$  by is a rational number  $\varepsilon$ , symbol:  $\varepsilon = \alpha : \beta$  or  $\varepsilon = \frac{\alpha}{\beta}$ ; in there  $\varepsilon = \alpha\beta^{-1}$ .

The rule for corresponding each pair of rational numbers  $\alpha, \beta (\beta \neq 0)$ , with a rational number  $\varepsilon$  mentioned above, is called division of rational numbers.

**Example 3.72.** Give  $\alpha = \frac{3}{4}$  and  $\beta = \frac{1}{5}$ . Find the sum, difference, product, and quotient of  $\alpha$  and  $\beta$ . We have:

$$\alpha + \beta = \overline{\left(\frac{3}{4}; 0\right)} + \overline{\left(\frac{1}{5}; 0\right)} = \overline{\left(\frac{3}{4} + \frac{1}{5}; 0\right)} \\ = \overline{\left(\frac{15+4}{20}; 0\right)} = \overline{\left(\frac{19}{20}; 0\right)} = \frac{19}{20}$$

$$\alpha - \beta = \alpha + (-\beta) = \overline{\left(\frac{3}{4}; 0\right)} + \overline{\left(0; \frac{1}{5}\right)} \\ = \overline{\left(\frac{3}{4}; \frac{1}{5}\right)} = \overline{\left(\frac{11}{20}; 0\right)} = \frac{11}{20}$$

$$\alpha\beta = \overline{\left(\frac{3}{4}; 0\right)} \cdot \overline{\left(\frac{1}{5}; 0\right)} = \overline{\left(\frac{3}{4} \cdot \frac{1}{5}; 0\right)} \\ = \overline{\left(\frac{3}{20}; 0\right)} = \frac{3}{20}$$

$$\alpha : \beta = \alpha\beta^{-1} = \overline{\left(\frac{3}{4}; 0\right)} \cdot \overline{\left(\frac{5}{1}; 0\right)} \\ = \overline{\left(\frac{3}{4} \cdot \frac{5}{1}; 0\right)} = \overline{\left(\frac{15}{4}; 0\right)} = \frac{15}{4}.$$

**Example 3.73.** Give  $\alpha = \frac{5}{2}$  and  $\beta = -\frac{11}{3}$ . Find the sum, difference, product, and quotient of  $\alpha$  and  $\beta$ :

$$\alpha + \beta = \overline{\left(\frac{5}{2}; 0\right)} + \overline{\left(0; \frac{11}{3}\right)} = \overline{\left(\frac{5}{2}, \frac{11}{3}\right)} \\ = \overline{\left(0; \frac{7}{6}\right)} = -\frac{7}{6}$$

$$\alpha - \beta = \alpha + (-\beta) = \overline{\left(\frac{5}{2}; 0\right)} + \overline{\left(\frac{11}{3}; 0\right)} \\ = \overline{\left(\frac{5}{2} + \frac{11}{3}; 0\right)} = \overline{\left(\frac{37}{6}; 0\right)} = \frac{37}{6}$$

$$\begin{aligned}\alpha\beta &= \overline{\left(\frac{5}{2}; 0\right)} \cdot \overline{\left(0; \frac{11}{3}\right)} = \overline{\left(0; \frac{5}{2} \cdot \frac{11}{3}\right)} \\&= \overline{\left(0; \frac{55}{6}\right)} = -\frac{55}{6} \\ \alpha: \beta &= \alpha\beta^{-1} = \overline{\left(\frac{5}{2}; 0\right)} \cdot \overline{\left(0; \frac{3}{11}\right)} \\&= \overline{\left(0; \frac{15}{22}\right)} = -\frac{15}{22}.\end{aligned}$$

**Example 3.74.** Give  $\alpha = -\frac{4}{7}$ ;  $\beta = -\frac{5}{3}$ . Find the sum, difference, product and quotient of  $\alpha$  and  $\beta$ .

We have:

$$\begin{aligned}\alpha + \beta &= \overline{\left(0; \frac{4}{7}\right)} + \overline{\left(0; \frac{5}{3}\right)} = \overline{\left(0; \frac{4}{7} + \frac{5}{3}\right)} \\&= \overline{\left(0; \frac{47}{21}\right)} = -\frac{47}{21}.\ \alpha - \beta &= \overline{\left(0; \frac{4}{7}\right)} + \overline{\left(\frac{5}{3}; 0\right)} = \overline{\left(\frac{5}{3}; \frac{4}{7}\right)} \\&= \overline{\left(\frac{23}{21}; 0\right)} = \frac{23}{21} \\ \alpha: \beta &= \alpha\beta^{-1} = \overline{\left(0; \frac{4}{7}\right)} \cdot \overline{\left(0; \frac{3}{5}\right)} \\&= \overline{\left(\frac{4}{7} \cdot \frac{3}{5}; 0\right)} = \overline{\left(\frac{12}{35}; 0\right)} = \frac{12}{35}.\end{aligned}$$

From the definition, we can easily deduce that the set  $\mathbb{Q}$  with the above two addition and multiplication operations is a field. We call it the field of rational numbers.

### 3.4.4. Order relations in the set of rational numbers

Give  $\alpha, \beta \in \mathbb{Q}$ . We say:

a)  $\alpha$  is less than  $\beta$ , denoted by  $\alpha < \beta$ , if  $\beta - \alpha$  is a positive rational number.  
b)  $\alpha$  is less than or equal to  $\beta$ , denoted by  $\alpha \le \beta$ , if  $\alpha < \beta$  or  $\alpha = \beta$ .

### 3.4.5. Construct the set of integers in $\mathbb{Q}$

We call:

a) Every rational number defined by the equivalence class  $\alpha = \overline{(n; 0)}$ , which  $n$  is a natural number other than 0, is a positive integer, written as  $\alpha = n$ .  
b) Every rational number defined by the equivalence class  $\alpha = \overline{(0; n)}$ , in which  $n$  is a natural number other than 0, is a negative integer, written as  $\alpha = -n$ .

Positive integers, negative integers or zero are collectively called integers.

The set of all integers is denoted by  $\mathbb{Z}$ .

So:

$$\mathbb{Z} = \{n \in \mathbb{Q} \mid n \in \mathbb{N} \text{ or } -n \in \mathbb{N}\}.$$

### 3.4.6. Decimal (in $\mathbb{Q}$ )

In the previous subtopics we constructed the set of non-negative decimal numbers  $\mathbb{Q}_{+10}$  (which is a subset of  $\mathbb{Q}_+$ ). Thus, every non-negative decimal number  $r$  is also a rational number, we have  $r \in \mathbb{Q}$  or  $\mathbb{Q}_{+10} \subset \mathbb{Q}$ .

From there, we expand the concept of decimal numbers in the set of rational numbers  $\mathbb{Q}$  as follows:

Rational numbers  $\alpha$  are called decimals, if  $\alpha \in \mathbb{Q}_{+10}$  or  $-\alpha \in \mathbb{Q}_{+10}$ . The set of all decimal numbers is denoted by  $\mathbb{Q}_{10}$ .

Example. 2.017 and  $-2.017$  are decimal numbers.

## 3.5. REAL NUMBERS

### 3.5.1. The need to construct the set of real numbers

So far, we have expanded the sets of numbers according to the following scheme  $\mathbb{N} \leftrightarrow \mathbb{Q}_+ \leftrightarrow \mathbb{Q}$ .

If we stop at the set of rational numbers  $\mathbb{Q}$  then:

+ ) Many root operations cannot be performed.

We will prove that there does not exist a rational number  $x$  such that  $x^2 = 2$ .

Indeed, assume for contradiction that  $x$  is a rational number such that  $x^2 = 2$ , where  $x = p/q$  in lowest terms. It follows that  $p^2 = 2q^2$ . Therefore,  $p$  is an even number.

Now, assume  $p$  is even, so we can write  $p = 2r$  for some integer  $r$ . Substituting into the original equation gives  $(2r)^2/q^2 = 2$ . This implies  $2r^2 = q^2$ , so  $q$  is also even.

This is a contradiction since  $p$  and  $q$  have no common factors. Therefore, we have proved by contradiction that there does not exist a rational number  $x$  such that  $x^2 = 2$ .

Likewise,  $\sqrt{2}, \sqrt{5}, \sqrt{6}, \dots$ , they cannot be rational numbers.

+ ) Many equations cannot find rational solutions, for example:  $x^2 - 3 = 0$ ,  $x^4 - 4 = 0$ , or etc.

+ ) The measure of many quantities that cannot be expressed, for example, the measure of the diagonal of a square with sides equal to 1 unit of length; The measurements of a rectangular diagonal with a length of 2 units of length and a width of 1 unit of length are not rational numbers.

For the above reasons, we must expand the set of rational numbers  $\mathbb{Q}$  to add new numbers to meet the development requirements of mathematics and other sciences.

### 3.5.2. Construct the set of real numbers

There are many ways to construct the set of real numbers. Below we present a relatively simple construction method: expand the set of decimal numbers to get the set of real numbers.

In the previous sections, we considered two types of decimals: decimals (with finite digits in the decimal part) and infinite repeating decimals.

In addition to the two types of decimal numbers mentioned above, we also encounter a third type of "decimal number": those are decimal numbers with an infinite number of digits in the decimal part, the digits in the decimal part are not repeated, according to any rules. Every decimal like that is called an infinite non-repeating decimal. Every infinite non-repeating decimal number is called an irrational number. The set of all irrational numbers is denoted by  $I$ .

The set of all rational numbers and irrational numbers forms the set of real numbers, denoted by  $\mathbf{R}$ . So  $\mathbf{R} = \mathbf{Q} \cup \mathbf{I}$ .

**Example 3.75.**

+) 0.712; -4.008; 13.9 are decimal numbers  
+) 3.9545454 ... = 3.9(54) or -2.(18) are infinite repeating decimals.  
+) 0.4142135 ... ... or -2.6457513 ... ... are infinite non-repeating decimals (also known as irrational numbers).  
+) Each number 0.712; -4.008; 13.9; 3.9(54); -2.(18); 0.4142135...; -2.6457513... is a real number.

### 3.5.3. Mathematical operations in the set of real numbers

According to the above definition, each real number has the form

$$x = a_1 x_1 x_2 x_3 \dots \dots \dots \dots \dots \dots \dots \dots x_n \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \dots \$$

#### **Example 3.77.**

Let  $x = 0.9545454$  .... and  $y = -7.2$ .

Find the sum, difference, product and third-order approximate quotient of x and y.

We have:

$$\begin{array}{lll}x + y & \approx 0.954 - 7.200 & = -6.246; \\x - y & \approx 0.954 + 7.200 & = 8.154; \\xy & \approx 0.954 \times (-7.200) & = -6.8688 \approx -6.869; \\x: y \approx 0.954: (-7.200) & & = -0.1325 \approx -0.133.\end{array}$$

#### **Example 3.78.**

Let  $x = -\sqrt{2}$  and  $y = 1.603$ .

Find the sum, difference, product and first-order approximate quotient of x and y.

$$\begin{array}{l} \text{We have:} \\ -\sqrt{2} = -1.4142135 \dots \\ x + y \approx -1.4 + 1.6 = 0.2; \\ x - y \approx -1.4 - 1.6 = -3; \\ xy \approx -1.4 \times 1.6 = -2.24 \approx -2.2; \\ x: y \approx -1.4: 1.6 = -0.875 \approx -0.9.\end{array}$$

#### **Example 3.79.**

Let  $x = -\sqrt{3}$  and  $y = -\sqrt{5}$ .

Find the third-order approximate sum, difference, product, and quotient of x and y. We have:

$$\begin{array}{l} -\sqrt{3} = -1.7320508 \dots \dots \text{ and } -\sqrt{5} = -2.2360679 \dots \dots \dots \\ x + y \approx -1.732 - 2.236 = -3.968; \\ x - y \approx -1.732 + 2.236 = 0.504; \\ xy \approx (-1.732) \times (-2.236) = 3.872752 \approx 3.873; \\ x: y \approx (-1.732): (-2.236) = 0.7745974 \approx 0.775.\end{array}$$

# CHAPTER 3 EXERCISES

**Exercise 1.** Prove that the following sets are equivalent:a) X is the set of points on a circle with center O and radius  $R_1$  and the set Y of points on a circle with center O and radius  $R_2$ , with  $R_1 < R_2$ .

b) Set A of points belongs to a circle with center O and radius R and set B of points belonging to the diameter of that circle.

c) The set X includes points located in the circle with center O and radius R and the set P of points in the plane.

**Exercise 2.** Let A and B be two sets. Prove thata)  $A \times B \sim B \times A$ ;b) Set A is always equivalent to a subset of  $A \times B$ .**Exercise 3.** Prove that set A is finite if and only if every function from A to itself is injective.

**Exercise 4.** Prove that:

a) Every set equivalent to an infinite set is infinite;

b) Every set containing an infinite set is infinite;

c) An infinite set cannot be equivalent to a finite set.

**Exercise 5.** Prove that the set of points on a line is an infinite set.**Exercise 6.** State the basic contents when forming primary concepts of natural numbers in primary mathematics.**Exercise 7.** Give illustrative examples of how 2-digit, 3-digit, and 4-digit numbers are formed in primary mathematics.**Exercise 8.** State how the concepts of even and odd numbers are formed in primary mathematics.**Exercise 9.** What is the mathematical basis for forming the concept of natural numbers in primary school? Give illustrative examples.**Exercise 10.** Given two natural numbers  $a$  and  $b$ , where  $a < b$ . Prove that  $a' < b'$ .**Exercise 11.** Prove that:

a)  $a \le a + b$ ;

b)  $a \le b$ ;  $c \le d \rightarrow a + c \le b + d$  and  $ac < bd$ ;

c)  $a < b$ ;  $c < d \rightarrow a + c < b + d$  and  $ac < bd$ .

**Exercise 12.** Demonstrate how to guide students to the concept of comparing two objects in primary mathematics.**Exercise 13.** Provide an illustrative example of developing the skill of comparing three-digit numbers in primary mathematics.**Exercise 14.** Present the concept of "sequence of natural numbers" and state the properties of sequences of natural numbers in primary mathematics.**Exercise 15.** Prove that:

a) The sum of two natural numbers equals 0 if and only if both numbers are 0.

b) The product of two natural numbers equals 0 if and only if at least one of them is 0.

c) The product of two natural numbers equals 1 if and only if both numbers are 1.

**Exercise 16.** Prove that:

a)  $(a + b)' = a + b'$ ;

b)  $a(b') = ab + a$ .

**Exercise 17.** Prove that:

a)  $(a + b) - c = (a - c) + b = a + (b - c)$ ;

b)  $a - (b + c) = (a - b) - c = (a - c) - b$ ;

c)  $a - (b - c) = (a - b) + c = (a + c) - b$ .

where  $a$ ,  $b$ ,  $c$  are natural numbers and it is assumed that the above calculations can all be performed.**Exercise 18.** Prove the following properties of division of natural numbers:

$$\text{a) } (a + b) : c = a : c + b : c;$$

$$\text{b) } (ab) : c = (a : c) \cdot b = a \cdot (b : c);$$

$$\text{c) } a : (bc) = (a : b) : c;$$

$$\text{d) } a : (b : c) = (ac) : b;$$

for all natural numbers  $a$ ,  $b$ ,  $c$  and assuming the above calculations can be performed.

**Exercise 19.** List the steps to present addition and subtraction of natural numbers in primary mathematics.

**Exercise 20.** Give illustrative examples of:

a) Form addition within 10;

b) Form rules for practicing addition and subtraction of numbers with two, three or more digits in primary mathematics.

**Exercise 21.** List the steps to present multiplication of natural numbers in primary mathematics.

**Exercise 22.** Give illustrative examples of:

a) Form multiplication in tables and multiplication tables;

b) Forming rules for multiplying with one, two or three-digit numbers in primary mathematics.

**Exercise 23.** List the steps to present division (complete division and division with remainder) in the set of natural numbers in primary mathematics.

**Exercise 24.** Give illustrative examples of:

A) Forming division equations and division tables;

b) Forming rules for practicing division by one, two or three-digit numbers in primary mathematics.

**Exercise 25.** Give illustrative examples of how to form properties, rules, and formulas for practicing calculations of natural numbers in primary school mathematics.

**Exercise 26.** Let  $a$ ,  $b$ ,  $c$  be three natural numbers. Prove that:

a) If  $a$  is divisible by the product  $bc$  then  $a$  is divisible by both  $b$  and  $c$ ;

b) If  $(a + b)$  is divisible by  $c$  and  $a$  is divisible by  $c$  then  $b$  is also divisible by  $c$ .

**Exercise 27.** When dividing 100 by a natural number, we get a remainder of 16. Find the approximate divisor and quotient in that division.

**Exercise 28.** When dividing a natural number by 38, we get an approximate quotient of 15. Find the least and greatest value of the dividend and the remainder in that division.

**Exercise 29.** When dividing 335 by a natural number, we get an approximate quotient of 11. Find the divisor and remainder in that division.

**Exercise 30.** Prove that there are no natural numbers:

a) When divided by 15, the remainder is 6 and when divided by 24, the remainder is 16;

b) When divided by 18, the remainder is 9 and when divided by 27, the remainder is 12.

**Exercise 31.** Let a and b be two natural numbers. Prove that:

1. The sum  $a + b$  is even if and only if both a and b are both even or odd;
2. The sum  $a + b$  is odd if and only if one of the two numbers is odd and the second number is even;
3. Calculate  $ab$  as odd if and only if both a and b are odd;
4. The product  $ab$  is even if and only if at least one of the two numbers is even;

**Exercise 32.** Let a be an odd natural number. Prove that:

1. $a^3 - a$  is divisible by 12;
2. $a^5 - a$  is divisible by 30;

**Exercise 33.** Let a be a natural number. Find the remainder in the division:

1. $(a^3 + 11a + 2015) : 3$ ;
2. $(a^5 - a + 2015) : 15$ ;
3. $(a^3 + 3n^2 - n - 2015) : 24$

**Exercise 34.** Find the greatest common factor and least common multiple of a and b, knowing that:

1. $a = 1370$  and  $b = 210$ ;
2. $a = 2448$  and  $b = 380$ .

**Exercise 35.** Find the greatest common factor and least common multiple of a, b and c, knowing that:

1. $a = 4200$ ;  $b = 6750$ ;  $c = 2205$ .
2. $a = 3960$ ;  $b = 4500$ ;  $c = 12 100$ .

**Exercise 36.** Let a be a natural number. Prove that:

$$\begin{aligned}a) & \frac{3a+1}{2a+1}; \\b) & \frac{24a+4}{14a+3}; \\c) & \frac{a^2+2a+2}{5a^2+10a+13}.\end{aligned}$$

is a simplified fraction.

**Exercise 37.** Find the positive integer solution of the following system of equations:

$$\begin{cases}a) & x + y = 120 \\ & (x; y) = 15\end{cases}$$
$$\begin{cases}b) & x + y = 375 \\ & (x; y) = 25\end{cases}$$

**Exercise 38.** Find two natural numbers, knowing that:

1. Their greatest common divisor is 21, their least common multiple is 2310.
2. Their greatest common divisor is 22, their least common multiple is 6930.

**Exercise 39. a)** Given  $(a; b) = 1$ . Find  $(a; a + b)$ ;

b) Let  $(a; b) = d$ . Find  $(a + b; a - b)$ .

**Exercise 40.** Find the least common multiple of:

a)  $a = 3m + 1$  and  $b = 2n + 1$ ;

b)  $a = 21n + 4$  and  $b = 14n + 3$ ;

c)  $a = n + 2$  and  $b = n + 4$

where  $n$  is a natural number.

**Exercise 41.** Prove that the product of 5 consecutive natural numbers is divisible by 120.

**Exercise 42.** Let  $a$  and  $b$  be two odd numbers not divisible by 3. Prove that:

$a^2 - b^2$  is divisible by 24.

**Exercise 43.** Prove that for every natural number  $n$  greater than 1, there always exist  $n$  consecutive natural numbers that are all composite numbers.

**Exercise 44.** Let  $a$  be a natural number greater than 1. Prove that the following numbers are all composite numbers:

a)  $a^4 + 4$ ;

b)  $a^4 + a^2 + 1$ ;

c)  $a^4 + 4^a$ .

**Exercise 45.** Let  $p$  be a prime number greater than 5. Find the remainder in division:

a)  $p : 6$ ;

b)  $p : 18$ ;

c)  $p : 30$ .

**Exercise 46.** Let  $p$  and  $q$  be prime numbers greater than 3. Prove that:

a)  $p^2 - 1$  is divisible by 24;

b)  $p^2 - q^2$  is divisible by 24.

**Exercise 47.** Prove that:

a) If  $p$  and  $8p - 1$  are both prime numbers, then  $8p + 1$  is composite;

b) If  $p$  is a prime number greater than 3 and  $2p + 1$  are both prime numbers, then  $4p + 1$  is composite.

**Exercise 48.** Find a prime number  $p$  such that:

a)  $p + 10$  and  $p + 14$  are both prime numbers;

b)  $p + 6$ ;  $p + 8$ ;  $p + 12$  and  $p + 14$  are both prime numbers.

**Exercise 49.** Are the following numbers prime numbers? Why?

a) 127;

b) 179;

c) 2017.

**Exercise 50.** Find the prime number  $p$  such that  $2p + 1$  is the cube of a natural number.

**Exercise 51.**a) Express the number  $a = 558$  in the base system  $g = 5$  and  $g = 7$ .

b) Let's represent the number  $a = 3971$  in the base systems  $g = 11$  and  $g = 12$ .

c) Let's represent the number  $a = 6635$  in the base systems  $g = 9$  and  $g = 12$ .

**Exercise 52.** Express the following numbers in the decimal number system:

a)  $\overline{10101_2}$ ;

b)  $\overline{4502_6}$ ;

c)  $\overline{1\alpha 75_{11}}$ ;

d)  $\overline{\beta 8\alpha_{12}}$

**Exercise 53.** Make addition and multiplication tables in base  $g = 2$ ;  $3$ ;  $4$ ;  $\dots$ ;  $11$ ; twelfth.

**Exercise 54.** Calculate:

$$a) \overline{3254_6} + \overline{2435_6};$$

$$d) \overline{325_6} \times \overline{54_6};$$

$$b) \overline{21547_9} - \overline{5768_9};$$

$$e) \overline{3207_8} : \overline{45_8};$$

$$c) \overline{7\alpha 95_{12}} + \overline{8\beta \alpha 9_{12}}.$$

$$g) \overline{2\beta \alpha 12} \times \overline{72_{12}}.$$

**Exercise 55.** Determine the base  $g$  so that the following writing is correct:

$$a) \overline{77_g} = 63;$$

$$b) \overline{4243_g} = 2773; c) \overline{2103_g} + \overline{1013_g} = \overline{3120_g}$$

$$d) \overline{124_g} \times \overline{35_g} = \overline{5036_g};$$

$$e) \overline{3631_g} : \overline{45_g} = \overline{64_g} (\text{the remainder } \overline{23_g})$$

**Exercise 56.** Find a natural number with 4 digits and greater than 9000, such that  $n$  is divisible by 2, 9 and 25.

**Exercise 57.** Find the natural number  $n$  greater than 6000 and less than 7000 such that when divided by 25, the remainder is 19, and when divided by 6 and 9, the remainder is 3.

**Exercise 58.** Prove that in any 8 natural numbers there always exist two numbers whose difference is divisible by 7.

**Exercise 59.** Replace  $a$  and  $b$  by appropriate digits to get natural numbers  $n = \overline{a85b}$  is the least four-digit number that leaves a remainder of 3 when divided by 5 and a remainder of 2 when divided by 3.

**Exercise 60.** How many numbers are there:

a) Are there 4 numbers divisible by 5 and all of their digits are even?

b) Are there 4 digits greater than 5000, all of which are even numbers and the hundreds digit is all 2?

**Exercise 61.** Given six digits 0, 5, 6, 7, 8, 9. From the given six digits you can write:

a) How many 5-digit numbers are divisible by 2 and 5?

b) How many even numbers have 5 different digits where the thousands digit is 8?

**Exercise 62.** Write one more digit to the left of 52 and two digits to the right to get the least number with 5 different digits when divided by 5, remainder 2 and remainder 4 when divided by 9.

**Exercise 63.** There are 18 sticks, each stick's length is 1cm, 2cm, 3cm, ..., 17cm, 18cm. Those 18 sticks can be used to arrange:

a) A square;

b) A rectangle.

or not? Why? Know that when arranging, we use all 18 sticks and do not change the length of each stick.

**Exercise 64.** An iron shop has 7 boxes containing two types of nails, 5cm and 10cm (each box contains only one type of nail). Number of nails in each box in order of weight: 24kg; 26kg; 34kg; 37kg; 41kg; 55kg and 54kg. After selling all 6 boxes and

only having 1 box of 10 cm nails left, the salesman found that among the sold nails, 5 cm nails were 3 times more than 10 cm nails. How many kilograms of each type of nail did the store initially have?

**Exercise 65.** Summarizing the 2014 - 2015 school year, Hoa Binh Primary School has 162 excellent students and 216 advanced students. The principal plans to reward each good student with twice as many notebooks as an advanced student. The clerk calculated that she would have to buy 1.245 notebooks to give out enough prizes. Ask the clerk whether the calculation is right or wrong? Why?

**Exercise 66.** Let  $X$  be the set of all students of Hoa Binh Primary School. In the set  $X$ , we define the binary relationship  $e$  as follows:

“Two students  $a$  and  $b$  have a relationship with each other if and only if  $a$  and  $b$  are in the same class.”

1. Prove that  $e$  is an equivalence relation defined on the set  $X$ ;
2. Find the quotient set  $X/e$ .

**Exercise 67.** Let  $N$  be natural numbers. In set  $N$  we define the binary relationship  $e$  as follows:

“Two natural numbers  $a$  and  $b$  are related to each other if and only if they have the same remainder when divided by 4”.

1. Prove that  $e$  is an equivalence relation defined on set  $N$ ;
2. Find the quotient set  $N/e$ .

**Exercise 68.** Let  $T$  be the set of all triangles in the plane. In the set  $T$  we define a binary relationship as follows:

“Two triangles  $ABC$  and  $A'B'C'$  are related to each other if and only if they are similar to each other.”

1. Prove that  $e$  is an equivalence relation defined on the set  $T$ ;
2. Find the quotient set  $T/e$ .

**Exercise 69.** Let  $P$  be the set of all points in the Cartesian coordinate plane. In the set  $P$  we define the binary relation  $e$  as follows:

“Two points  $A$  and  $B$  are related to each other if and only if the distance from  $A$  to the origin is equal to the distance from  $B$  to the origin.”

1. Prove that  $e$  is an equivalence relation defined on the set  $P$ ;
2. Find the quotient set  $P/e$ .

**Exercise 70.** If correct, write  $D$ , if incorrect, write  $S$  in the blank box:

$$a) \frac{2}{3}e\frac{14}{21};$$

$$b) \frac{5}{8}e\frac{11}{14};$$

$$c) \frac{3}{7}e\frac{7}{3};$$

$$d) \frac{9}{5}e\frac{54}{30}.$$

**Exercise 71.** List the following class of fractions that define rational numbers:

$$a) r = \frac{5}{2};$$

$$c) r = 0;$$

$$b) r = \frac{2}{7};$$

$$d) r = 1.$$

**Exercise 72.** Let  $r$  and  $s$  be two rational numbers whose representative fraction is

$$\frac{8}{3} \text{ và } \frac{5}{6}.$$
 Find  $r + s$ ;  $r - s$ ;  $r \times s$  and  $r : s$ .

**Exercise 73.** Fill in the appropriate number in the blank box:

$$a) C\left(\frac{11}{21}\right) = C\left(\frac{\Delta}{3} + \frac{\Delta}{7} + \frac{\Delta}{21}\right);$$

$$b) C\left(\frac{13}{16}\right) = C\left(\frac{\Delta}{2} + \frac{\Delta}{8} + \frac{\Delta}{16}\right);$$

$$c) C\left(\frac{11}{21}\right) = C\left(\frac{\Delta}{21} + \frac{1}{\Delta} + \frac{\Delta}{3}\right).$$

**Exercise 74.** Let  $r$ ,  $s$  and  $t$  be three rational numbers, in which  $t$  is different from 0.

Prove that:

$$a) (rs) : t = (r : t)s = r(s : t).$$

State the corresponding property of dividing fractions in primary school.

$$b) (r + s) : t = r : t + s : t$$

State the corresponding property of dividing fractions in primary school.

**Exercise 75.** Fill in the >; < or = in the dot:

$$a) C\left(\frac{2323}{3131}\right) \dots C\left(\frac{23}{31}\right);$$

$$b) C\left(\frac{494949}{2282828}\right) \dots C\left(\frac{8}{3}\right);$$

$$c) C\left(\frac{171171}{173173}\right) \dots C\left(\frac{169169}{171171}\right);$$

$$d) C\left(\frac{135135}{135135}\right) \dots C\left(\frac{6}{7}\right).$$

**Exercise 76.** Write 5 rational numbers between two numbers:

$$a) r = C\left(\frac{3}{5}\right) \text{ and } s = C\left(\frac{4}{5}\right);$$

$$b) r = C\left(\frac{5}{6}\right) \text{ and } s = C\left(\frac{5}{7}\right).$$

**Exercise 77.** Fill in the appropriate letters or numbers in the blanks:

a) When adding (or multiplying) the side with the  
.................................... side, we get a new inequality in the same direction as  
the given inequalities.

b) When multiply both sides of a strict inequality by the same ....................  
.................................... then the inequality ....................

**Exercise 78.** Let  $0 < r < s$ . Fill in the >; < or = in the dot:  $\frac{1}{r} \dots \frac{1}{s}$ .

**Exercise 79.** If correct, write D, if incorrect, write S in the blank box:

a)  $\frac{5}{0,1}$  is a fraction.

b)  $\frac{7}{1}$  is a fraction.

$e) \frac{1+2}{3 \times 4}$  is a fraction.

$e) \frac{0}{5}$  is a fraction.

$h) 0$  is a fraction.

$d) \frac{0,7}{0,1}$  is a fraction.

$g) \frac{1}{1}$  is a fraction.

$i) 1$  is a fraction.

**Exercise 80.** The product of the numerator and denominator of a fraction greater than 1 is 200. If we divide both the numerator and denominator of that fraction by 5, we get the simplest fraction. Find that fraction.

**Exercise 81.** When multiplying both the numerator and denominator of a simplified fraction by 4, we get a fraction whose sum of the numerator and denominator is 24. Find that simplified fraction.

**Exercise 82.** When adding to both the numerator and denominator of a fraction  $\frac{13}{7}$  with the same natural number we get an equal fraction  $\frac{21}{19}$ . Find all natural numbers there.

**Exercise 83.** When adding to the numerator, at the same time subtract from the denominator of the fraction  $\frac{31}{69}$  with the same natural number, we get an equal fraction  $\frac{7}{3}$ . Find all natural numbers there.

**Exercise 84.** Mother gave birth at the age of 28. How old is the child if 3 times the mother's age is equal to 7 times the child's age?

**Exercise 85.** Fill in the mark  $\in$  or  $\notin$  in the blank box:

a)  $\frac{3}{8} \in Q_{+10}$ ;

c)  $\frac{7}{20} \in Q_{+10}$ ;

e)  $\frac{9}{12} \in Q_{+10}$ ;

b)  $\frac{4}{7} \notin Q_{+10}$ ;

d)  $\frac{3}{16} \notin Q_{+10}$ ;

f)  $\frac{4}{26} \notin Q_{+10}$ .

**Exercise 86.** Fill in the form:

Sample:  $\frac{3}{4} = \frac{75}{100} = 0.75$ .

$$a) \frac{17}{40} = \dots = \dots$$

$$b) \frac{142}{125} = \dots = \dots$$

$$c) \frac{45}{24} = \dots = \dots$$

$$d) \frac{75}{120} = \dots = \dots$$

**Exercise 87.** Write according to the form:

$$\text{Sample: } 1,5 = \frac{15}{10} = \frac{3}{2}$$

$$a) 1,25 = \dots = \dots$$

$$b) 0,0048 = \dots = \dots$$

$$c) 4,75 = \dots = \dots$$

**Exercise 88.** If correct, write D, if incorrect, write S in the blank box:

a) The sum of two decimals is a decimal.

b) The difference of two decimals is a decimal.

c) The product of two decimals is a decimal.

d) The quotient of a decimal number with a non-zero decimal number is a decimal number.

**Exercise 89.** Prove that between two different decimal numbers there are infinitely many other decimal numbers between them.

**Exercise 90.** Fill in the appropriate number in the blanks:

a) Numbers 182, 304 have the integer part ............; The decimal part is ............

b) The number 0.070 has an integer part of ............; The decimal part is ............

c) Number 120,0048 has an integer part of ............; The decimal part is ............

**Exercise 91.** Fill in the blanks according to the form:

Sample: The number 32.018 has a tens place of 3, a units place of 2, a tenths place of 0, a hundredths place of 1, and a thousandths place of 8.

a) The number 203.041 ....................................................

b) The number 3.201 ....................................................

c) The number  
20.0001 ....................................................

**Exercise 92.** If correct, write D, if incorrect, write S in the blank box:

a) 20 is a decimal number.

b) 1.02 is a decimal number.

c)  $\frac{2}{3}$  is a decimal number.

d)  $\frac{5}{8}$  is a decimal number.

![](e31ef79318666dd5f4f0da841835c954_img.jpg)

□

**Exercise 93.** Given four digits 0, 1, 2, 3. Write all the large decimal numbers 20 such that each given digit appears in the writing exactly once. Then arrange the written numbers in order from greatest to least.

**Exercise 94.** Given five digits 0, 3, 4, 8, 9. Write all the decimal numbers less than 40 and greater than 5 such that each given digit appears in the writing exactly once. Then arrange the written numbers in order from least to greatest.

**Exercise 95.** When the comma of a decimal number is moved one place to the left, the number decreases by 28,928 units. Find that decimal number.

**Exercise 96.** When you forget the comma of a decimal number with two digits in the decimal part, the number increases by 341.55 units. Find that decimal number.

**Exercise 97.** When adding a natural number to a decimal number with one digit in the decimal part, by mistake, a student forgot the comma of the decimal number and set the calculation as adding two natural numbers. So the result of the calculation increases by 110.7 units. Find that decimal number.

**Exercise 98.** When adding 312 to a decimal number with one digit in the decimal part, by mistake, a student forgot the comma of the decimal number and mistakenly copied the plus sign (+) into a minus sign (-). Therefore, the result of the calculation is reduced by 135.3 units. Find the correct result of that calculation.

**Exercise 99.** When adding a natural number to a decimal number with two decimal places, by mistake, a student forgot the comma of the decimal number and set the calculation as adding two natural numbers. So the result is 435. Find the natural number and the decimal number. Know that the result of the calculation is exactly 313.23.

**Exercise 100.** Fill in the appropriate number to replace the \* sign:

a)  $0.07 < 0.0*9 < 0.081$ ;

b)  $1.*28 < 1.1*9 < 1.110$ .

**Exercise 101.** Calculate the value of the following expression in the most reasonable way:

$$a) \frac{250 \times 1.8 + 2.5 \times 128 + 292 \times 2.5}{1 + 5 + 9 + \dots + 97 + 225};$$

$$b) \frac{10.1 \times 10.2 - 30.3 \times 3.4 + 14.68}{7.29 \times 540 \times 2 + 14.58 \times 460}.$$

**Exercise 102.** Find the remainder in division:

a)  $2.43 : 7$ , if the quotient has three decimal places.

b)  $14.23 : 0.6$ , if taking a quotient with two decimal places.

c)  $32.07 : 1.7$ .

**Exercise 103.** Replace each letter in the following calculation by the appropriate number:

a)  $\overline{8ab} \cdot a - \overline{d51c} = \overline{cd6d}$ ; b) 15.abc : 0.abc = 121;  
c) 6.ab = a.b x 4.1; d) a.bc + 0.ab =  $\overline{bc}$ .b.

**Exercise 104.** A person who sells a fan for 400000 VND makes a profit of 10% on the selling price. To make a profit of 20% of the original price, how much does that person have to sell the fan for?

**Exercise 105.** A bookstore selling a story book for 19200 VND earns a profit of 20% of the original price. To make a profit of 20% on the selling price, how much does the store have to sell the storybook for?

**Exercise 106.** When increasing the length of a rectangle by 25%, by what percentage must the width be reduced so that the area of the rectangle remains unchanged?

**Exercise 107.** How many grams of salt must be added to a jar containing 200g of 5.5% salt solution to get a jar containing 10% salt solution?

**Exercise 108.** Pour 200g of 0.6% salt solution into a jar containing 300g of 0.8% salt solution. What percentage of salt is received in a bottle of solution?

## ANSWERS OR INSTRUCTIONS FOR SOLVING CHAPTER 3 EXERCISES

**Exercise 1.** a) Hint: For each point M in X, we connect M with the center O and cut Y at N. We define  $f(M) = N$ . Then f will be bijective from X to Y.

b) From each point M on X, we lower the perpendicular line MN to the diameter of the circle. Then N will be the image of the ray f from X to Y.

c) Bijective f is determined by the rule:  $f(M) = N$ , in which: point N lies on ray OM and is an equal distance  $\frac{1}{OM}$  from O.

**Exercise 2.** a) Simple. b) A is equivalent to A x {b}, where b belongs to B.

**Exercise 5.** Hint: the set of points on the line is equivalent to the interval (-1;1).

**Exercise 10.** Hint:  $a < b$  means that there exist two sets A and B such that  $a = \text{Card A}$ ,  $b = \text{Card B}$  and A is a true subset of B. Suppose b belongs to B - A and c does not belong to B. When that  $a' = \text{Card A}$  and  $a' < b'$ .  $\{b\}$ ,  $b' = \text{Card B} \cup \{c\}$ .

**Exercise 15.** Suggestions: a) Deduce from the property: the union of two empty sets is an empty set.

b) Deduce from the property: The Cartesian product of set A with the empty set is an empty set.

**Exercise 16.** Hint:  $a' = a + 1$ .

**Exercise 17.** a) Let  $b - c = m$ . It follows that  $b = m + c$ . We have:

$$(a + b) - c = [a + (m + c)] - c = [(a + m) + c] - c = a + m = a + (b - c).$$

Similar to the remaining sentences.

**Exercise 18.** Hint: a)  $a : c = m$ ; b)  $c : n = m$ . We have  $a = mc$  and  $b = nc$ . Instead we get:

$$a + b = mc + nc = (m + n)c. \text{ Deduce } (a + b): c = m + n = a : c + b : c$$

Similar to the remaining sentences.

**Exercise 26.** Hint: a) Suppose  $a$  is divisible by the product  $bc$ . It follows that  $a = (bc)d = b(cd) = c(bd)$ . From here we can deduce what must be proven.

Similar to the remaining sentences.

**Exercise 27.** Call the divisor  $b$  and the approximate quotient  $q$ . Applying the theorem on division with remainder we have:  $100 = bq + 16$ . From here we have  $bq = 84$ . The number 84 can represent the product of pairs of numbers:

$$84 = 1 \times 84 = 2 \times 42 = 3 \times 28 = 4 \times 21 = 6 \times 14 = 7 \times 12.$$

Because the remainder in division is 16, the approximate divisor and quotient in that division can be:  $b = 84$  then  $q = 1$ ;  $b = 42$  then  $q = 2$ ;  $b = 28$  then  $q = 3$  or  $b = 21$  then  $q = 4$ .

**Exercise 28.** Hint: Call the dividend  $a$  and the remainder  $r$ . Applying the theorem on division with remainder we have:

$$a = 38 \times 15 + r = 570 + r$$

From here, the least value of  $r$  is 0 and  $a$  is 570; The maximum value of  $r$  is 37 and  $a$  is 607.

**Exercise 29.** Call the divisor  $b$  and the remainder  $r$ . Applying the theorem on division with remainder we have:

$$335 = 11b + r (*), \text{ where } 0 \le r < b.$$

From here, it follows that  $11b \le 335$ . On the other hand, because the approximate quotient in division is equal to 11:

$$12b > 335. \text{ From here it follows that } b = 28, 29 \text{ or } 30.$$

Substituting (\*) we get the corresponding remainders  $r = 27, 16$  or  $5$ .

**Exercise 30.** a) Suppose there exists a natural number  $a$  that leaves a remainder of 6 when divided by 15 and a remainder of 16 when divided by 24. Deduce  $a = 15q + 6$  and  $a = 24 + 16$ . So  $a$  is both divisible by 3 and not divisible by 3.

This is absurd. Figure out what must be proven.

b) Similar.

**Exercise 31.** a) Assuming  $a$  and  $b$  are both even numbers:  $a = 2n$ ;  $b = 2m$ . We have  $a + b = 2(n + m)$

Suppose  $a$  and  $b$  are both odd numbers:  $a = 2n + 1$  and  $b = 2m + 1$ . We have  $a + b = 2(n + m + 1)$

Similar to the remaining sentences.

**Exercise 32.** a) Suppose  $a$  is an odd number. Let  $T = a^3 - a = a(a-1)(a+1)$ .

Because  $a$ ,  $a-1$  and  $a+1$  are three consecutive natural numbers,  $T$  is divisible by 3.

Because  $a$  is an odd number,  $a-1$  and  $a+1$  are two consecutive even numbers, so  $T$  is divisible by 4.

It follows that to prove.

Question b is similar.

**Exercise 33.** Hint: a) Consider in turn the cases where a is divisible by 3, a divided by 3 leaves a remainder of 1 and a divided by 3 leaves a remainder of 2 to show that  $a3 + 11a$  is always divisible by 3. Deduce the remainder of  $a3 + 11a + 2015$  divided by 3 equals the remainder of 2015 divided by 3 and equals 2.

Similar to the remaining sentences.

**Exercise 34.** a)  $(1370; 210) = 10$  and  $[1370; 210] = 28770$ .

b)  $(2448; 380) = 4$  and  $[2448; 380] = 232560$ .

**Exercise 35.** a)  $(4200; 6750; 2205) = 3$  and  $[4200; 6750; 2205] = 9261000$ .

b)  $(3960; 4500; 12 100) = 10$  and  $[3960; 4500; 12 100] = 19800$ .

**Exercise 36.** Hint: Using the Euclidean algorithm, we can show that the greatest common divisor of the numerator and denominator of each fraction is equal to 1. It follows that they are minimal fractions.

**Exercise 37.** a) From  $(x; y) = 15$ , it follows that there exist two natural numbers  $m$  and  $n$  such that  $x = 15m$ ,  $y = 15n$ , in which  $(m; n) = 1$ . Substituting into equation (1) we get:

$$15m + 15n = 120 \text{ deduce } m + n = 8.$$

The number 8 can be broken down into:  $8 = 0 + 8 = 1 + 7 = 2 + 6 = 3 + 5 = 4 + 4$ .

Since  $(m; n) = 1$ ,  $m$  and  $n$  can only be equal to 1 and 7 or 3 and 5. Substituting we get  $x1 = 15$ ;  $y1 = 105$  or  $x2 = 105$ ;  $y2 = 15$  or  $x3 = 45$ ;  $y3 = 75$  or  $x4 = 75$ ;  $y4 = 45$ .

b) Similar.

**Exercise 38.** a) Call the two numbers you want to find a and b. According to the problem we have:  $(a; b) = 21$ ,  $[a; b] = 2310$ .

From  $(a; b) = 21$ , we deduce that there exists  $m$ ,  $n$  such that  $a = 21m$ ,  $b = 21n$ , in which  $(m; n) = 1$ .

On the other hand we have  $[a; b] = \frac{ab}{(a; b)}$ . Substituting and simplifying, we get  $mn = 110$ . The number 110 can be the product of pairs of numbers: 1 and 110, 2 and 55, 5 and 22, 10 and 11. Substituting, we get the pairs of numbers we need to find: 21 and 2310; 42 and 1155; 105 and 462; 210 and 231.

b) Similar to sentence a.

**Exercise 39.** a) Suppose  $(a; a+b) = d$ . It follows that  $d$  is a divisor of  $a$  and a divisor of  $a + b$ . So  $d$  is a divisor of  $a + b - a = b$ . It follows that  $d = 1$ .

b)  $(a + b; a - b)$  can be equal to  $d$  or  $2d$ .

**Exercise 40.** Hint: a)  $(3m + 1; 2m + 1) = (2m + 1; m) = (m; m+1) = 1$ . Deduce

$$[3m + 1; 2m + 1] = (3m + 1)(2m + 1)$$

b) Similar.

c)  $[n + 2; n + 4] = (n + 2)(n + 4)$  if  $n$  is odd;  $=(n + 2)(n + 4) : 2$ , if  $n$  is even.

**Exercise 41.** Hint: we show in turn the product of 5 consecutive natural numbers divisible by 3, 5 and 8.

**Exercise 42.** We prove:  $a^2 - 1 = (a - 1)(a + 1)$  is divisible by 3 and 8, because  $a - 1$  and  $a + 1$  are two consecutive even numbers, so their product is divisible by 8. A is not divisible by 3 so  $a - 1$  or  $a + 1$  will be divisible by 3.

$a^2 - b^2 = (a^2 - 1) - (b^2 - 1)$ . From here we can deduce what must be proven.

**Exercise 43.** Hint:  $a_1 = (n + 1)! + 2$ ;  $a_2 = (n + 1)! + 3$ ; ...;  $a_n = (n + 1)! + (n + 1)$

**Exercise 44.** Hint: a)  $a^4 + 4 = a^4 + 4a^2 + 4 - 4a^2 = \dots = (a^2 + 2 + 2a)(a^2 + 2 - 2a)$ .

b) Similar.

c) Consider each case: a is even and a is odd.

**Exercise 45.** a) Call the approximate quotient  $q$  and the remainder  $r$ . Applying the theorem on division with remainder we have:  $p = 6q + r$ , where  $r = 0, 2, 3, 4$  or 5.

- If  $r = 0, 2$  or 4 then  $p$  is even. This is contrary to the assumption that  $p$  is a prime number greater than 5. Therefore  $r$  cannot be equal to 0, 2 or 4.

- If  $r = 3$  then  $p$  is divisible by 3. This is contrary to the assumption that  $p$  is a prime number greater than 5. Therefore  $r$  cannot be equal to 3.

- From the above results, we infer that  $r$  can only be equal to 1 or 5. For example, if  $p = 7$  then  $r = 1$ , if  $p = 11$  then  $r = 5$ .

Similar to the remaining sentences.

**Exercise 47.** Suggestion: a)  $(8p - 1)8p(8p + 1)$  is the product of 3 consecutive numbers so it is divisible by 3 and  $p$  and  $8p - 1$  are both prime numbers so  $8p - 1$  and  $8p$  are not divisible for 3. It follows that  $8p + 1$  is divisible by 3.

b) Similar.

**Exercise 48.** Hint: a)  $p = 3$ , then  $p + 10$  and  $p + 14$  are both prime numbers. We show that for  $p$  other than 3,  $p + 10$  or  $p + 14$  will be composite numbers by respectively considering the cases where  $p$  divided by 3 leaves a remainder of 1 and a remainder of 2.

b) Similar.

**Exercise 49.** a) We have:  $\sqrt{127} \approx 12$ . The prime numbers less than 12 are 2, 3, 5, 7 and 11. These numbers are not divisors of 127, so 127 is prime.

Similar to the remaining sentences.

**Exercise 50.** Suppose  $n^3 = 2p + 1$ . It follows that  $n$  is an odd number,  $n = 2k + 1$ . We have

$$(2k + 1)^3 = 8k^3 + 12k^2 + 6k + 1 = 2p + 1. \text{ Deduce } p = (4k^2 + 6k + 3)k \quad (2k + 1)^3 =$$

Because  $p$  is prime,  $k = 1$ . Substituting, we get  $p = 13$

**Exercise 51.** a)  $558 = \overline{42135}$ ;  $558 = \overline{14257}$ ; b)  $3971 = \overline{2\alpha 90}_{11}$ ;  $3971 = \overline{29\beta}_{12}$

c)  $6635 = \overline{10082}_9$ ;  $6635 = \overline{3\alpha 0\beta}_{12}$ .

**Exercise 52.** a)  $\overline{10101_2} = 21$ ; b)  $\overline{4502_6} = 1046$ ; c)  $\overline{1\alpha 75_{11}} = 2623$ ; d)  $\overline{\beta 8\alpha_{12}} = 1690$ .

**Exercise 54.** a)  $\overline{10133_6}$ ; b)  $\overline{14668_9}$ ; c)  $\overline{14\alpha 82_{12}}$ ; d)  $\overline{31402_6}$ ;

e)  $\overline{55_8}$  (the remainder  $6_8$ ); g)  $\overline{1\alpha 098_{12}}$ .

**Exercise 55.** a)  $g = 8$ ; b)  $g = 5$ ; c)  $g = 6$ ; d)  $g = 7$ ; e)  $g = 8$ .

**Exercise 56.**  $n = 9000$  and  $9900$ .

**Exercise 57.** The numbers to look for are 6219 and 6669.

**Exercise 58.** Hint: Apply the Dirichlet principle.

**Exercise 59.** The number to search for is 1853.

**Exercise 60.** a) 100 numbers b) 50 numbers.

**Exercise 61.** a) 1080 numbers b) 42 numbers.

**Exercise 62.** The number to search for is 1507.

**Exercise 63.** Hint: The total length of 18 sticks is 171cm, so the perimeter of the square and the perimeter of the rectangle, if combined, must be even numbers. So it cannot be merged.

**Exercise 64.** Suggest:

- The total weight of 7 boxes of nails is 271kg (a number divided by 4 with a remainder of 3!)

- The number of 5-inch nails sold is 3 times the number of 10-inch nails sold, so the number of nails sold is divisible by 4.

- It follows that the remaining number of nails is the number divided by 4 with a remainder of 3. Of the 7 barrels, only the 55kg barrel contains a remainder of 3 when divided by 4. It follows that the remaining barrel contains 55kg of 10-centimeter nails. Answer: 162kg of 5cm nails and 109kg of 10cm nails.

**Exercise 65.** She calculated wrongly because the number of good students and the number of advanced students are both divisible by 9, so the total number of notebooks distributed must be divisible by 9, but 1245 is not divisible by 9.

**Exercise 66.** b) Each equivalent class in the quotient set is the set of students in a class of that school. The number of elements in the quotient set is equal to the number of classes of that field.

**Exercise 67.** b) Quotient set  $N/e = \{[0]; [1]; [2]; [3]\}$ , where  $[r]$  is the set of numbers that leave remainder  $r$  when divided by 4, with  $r = 0, 1, 2, 3$ .

**Exercise 68.** b) Each equivalence class is the set of all triangles similar to a given triangle ABC. The quotient set  $T/e$  is the set of all the above equivalence classes.

**Exercise 69.** b) Each equivalence class is a circle with center O and radius  $r$ . The quotient set  $P/e$  is a set of concentric interior lines O, with arbitrary radius  $r$ .

**Exercise 71.** a)  $r = C(\frac{5}{2}) = \{\frac{5}{2}; \frac{10}{4}; \frac{15}{6}; \dots\}$ . Similar to the remaining sentences.

**Exercise 72.**  $r + s = C(\frac{7}{2})$ ;  $r - s = C(\frac{11}{6})$ ;  $r \cdot s = C(\frac{20}{9})$ ;  $r : s = C(\frac{16}{5})$ .

**Exercise 73.** a)  $C(\frac{11}{21}) = C(\frac{1}{3} + \frac{1}{7} + \frac{1}{21})$ . Similar to the remaining sentences.

**Exercise 74.** a) Assuming  $r = C(\frac{a}{b})$ ;  $s = C(\frac{c}{d})$  và  $t = C(\frac{m}{n})$ . We have:

$$(rs) : t = C\left(\frac{ac}{bd}\right) : C\left(\frac{m}{n}\right) = C\left(\frac{acn}{bdm}\right) = C\left(\frac{a}{b}\right) \left(C\left(\frac{cn}{dm}\right)\right) \\ = C\left(\frac{a}{b}\right) C\left(\frac{c}{d}\right) : C\left(\frac{m}{n}\right) = r(s : t).$$

Rule: When dividing the product of two fractions by a third fraction, we can divide one fraction by the third fraction and then multiply by the remaining fraction.

b) Similar.

**Exercise 76.** a)  $\frac{3}{5} = \frac{18}{30} < \frac{19}{30} < \frac{20}{30} < \frac{21}{30} < \frac{22}{30} < \frac{23}{30} < \frac{30}{24} = \frac{4}{5}$ .

b) Similar

**Exercise 79.** a) S; b) D; c) S; d) S; e) D; g) D; h) S; i) S.

**Exercise 80.**  $\frac{40}{5}$ .

**Exercise 81.**  $\frac{1}{5}$  and  $\frac{5}{1}$ .

**Exercise 82.** 50.

**Exercise 83.** 39.

**Exercise 84.** 12 years old.

**Exercise 85.** a)  $\in$ ; b) does not belong; c)  $\in$ ; d)  $\in$ ; e)  $\in$ ; f) does not belong.

**Exercise 88.** a) D; b) D; c) D; d) S.

**Exercise 90.** a) Integer part = 182 and decimal part is 304;

b) The integer part = 0 and the decimal part is 070;

c) Integer part = 120 and decimal part is 0048.

**Exercise 92.** a) S; b) D; c) S; d) S.

**Exercise 93.** 20.13; 20.31; 21.03; 21.30; 23.01; 23.10;

30.12; 30.21; 31.02; 31.20; 32.01; 32.10;

102.3; 103.2; 120.3; 123.0; 130.2; 132.0

201.3; 203.1; 210.3; 213.0; 230.1; 231.0;

301.2; 302.1; 310.2; 312.0; 320.1; 321.0.

**Exercise 95.** 123.4

**Exercise 96.** 3.45

**Exercise 97.** 12.3

**Exercise 98.** 324.3

**Exercise 99.** 312 and 12.3

**Exercise 100.** a)  $0.07 < 0.079 < 0.081$ ; b)  $1.028 < 1.09 < 1.110$

**Exercise 103.** a)  $887.8 - 351.5 = 536.3$  b)  $15.125 : 0.125 = 121$

c)  $6.15 = 1.5 \times 4.1$

**Exercise 104.** 432000 VND.

**Exercise 105.** 20000 VND.

**Exercise 106.** 20%.

**Exercise 107.** 10 grams.

**Exercise 108.** 0.72%.

d)  $9.10 + 0.91 = 10.01$