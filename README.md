# Gold-Coins

## Problem Statement
We have ​*n* ​gold coins out of which some coins are fake and the rest are
genuine. The number of genuine coins is strictly greater than the number of fake
coins. Coins of the same type have the same weight. We have a balance using
which we can test if two coins have the same weight.

The problem is to find a genuine coin using as few weighings as possible. A
trivial algorithm to solve the problem is to pick one coin and test it with every other
coin. This uses ​*n-1*​ weighings. We want something slightly better. Design an
algorithm that finds a genuine coin in ​*n-B(n)* weighings, where ​*B(n)* denotes the
number of 1s in the binary representation of ​*n*.

## Task List
- [x] Source files
- [x] Header files
- [x] makefile
- [ ] README
    - [ ] Sources referred
    - [ ] Data structures
    - [ ] Pseudo-code
    - [ ] Proof of correctness
    - [ ] Instructions to compile and run
    - [ ] Defects/Side-effects
    - [ ] Individual contributions
- [ ] Subfolder of test cases
    - [ ] Document detailing format of test cases, input and expected output

## Instructions to compile and run
- Compile the source code GoldCoins.cpp using g++
```
g++ GoldCoins.cpp
```
- a.out file will be generated
- Run the generated a.out file as follows : 
```
./a.out
```
### Input
- The first line contains the integer *n* - the number of gold coins.
- The next line contains *n* space-separated 0s or 1s denoting the two different weights of the genuine and fake coins.
- Make sure the genuine coins are more than half of the total coins.

### Output
- The first contains gives the weight of the genuine coin.
- The second line contains the number of weighings required to arrive at the genuine coin.

### Examples
#### input
```
5
1 0 0 1 0
```
#### output
```
Weight: 0
weighings: 2
```

#### input
```
9
1 0 0 1 0 0 1 0 1
```
#### output
```
Weight: 0
weighings: 4
```


## Contributors
- [Advait Lonkar](https://github.com/advait-l) 
- [Amogh Johri](https://github.com/AmoghJohri) 

