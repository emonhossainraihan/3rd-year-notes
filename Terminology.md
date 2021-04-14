## Algebra related

### Isomorphisms

Given two objects G and H (which are of the same type; maybe groups, or rings, or vector spaces... etc.), an isomorphism from G to H is a bijection ϕ:G→H which, in some sense, respects the structure of the objects. In other words, they basically identify the two objects as actually being the same object, after renaming of the elements.

> An isomorphism is a structure-preserving bijection. The specific meaning of "structure" will vary, depending on the context.

Usually the term "isomorphism" is used when there is some additional structure on the set.

For isomorphisms things like order and addition and multiplication should be consider. If we map every number to its negative, f(x) = -x, then this a bijection which will not preserve order or multiplication, but it will preserve addition (adding two numbers and then mapping them over will give the same result as mapping them over then adding). We would call this an isomorphism with respect to "groups" (which is the type of structure that cares about addition, or a "group isomorphism" but it is not an isomorphism with respect to "rings" (which care about multiplication) or with respect to linear orders.

**Visualization**: write down the numbers 1 through 9 on a sheet of paper, and you and I will take turns selecting numbers from the list (crossing off each number once it has been selected). The winner is the first person to have chosen exactly three numbers which add up to 15. For example if I selected 9, 6, 2 and you selected 3, 8, 1, 4 then you would win because 3 + 8 + 4 = 15.

The interesting thing is that this game is isomorphic to tic-tac-toe. I don't know what I precisely mean by that, but I can explain why it is true. Simply consider a 3 x 3 magic square:

4 9 2

3 5 7

8 1 6

The rows, columns, and diagonals all add up to 15, and moreover every way of writing 15 as the sum of three numbers from 1 to 9 is represented. When you choose a number, draw an X over it; when I choose a number, circle it. Tic-tac-toe!

### Homomorphism

A homomorphism is simply an isomorphism that is not bijective.

If you havestudied some other branches of math, these functions are the analogues of bijective linear trans-formations for vector spaces, isomorphisms between groups/rings/fields/modules/graphs/linearorders/etc., diffeomorphisms between manifolds, etc.

## Operation

A substitute for the word function usually used when you want to treat the function as a single atomic object. Ex: order of operations (here functions are the little things, and we are looking at a larger idea of how to evaluate them, what order, etc...). Another example: Quicksort takes O(n log n) floating point operations on randomized inputs. Here operation is short hand for: addition, subtraction, division, multiplication, comparison. But those functions and their inputs (integers) really aren’t the main point. The main point is we want to count how many times we do them, so we call them operations to make this context clear.
