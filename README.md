# inverseProblem
A study note for inverse Problem
Definition of inverse problem: 已知道y求x
一般数学是已知x求y

## Terminology:

**well-posted problem** : 
- 1. A solution exisit**
  2. The solution is unqiue
  3. The solution is stable: 输入加入少量扰动（distrubance）解不会有很大的变化 （overfit的NN就不符合这要求）

**ill-posted problem**: 只要上述有一个不符合，就是ill-posed problem

## Application

## Algorithm

**Optimization/Regression**
Linear inverse problem example:

y = Ax + e
want to find x^*

\hat{x} = arg min f(y; Ax)
