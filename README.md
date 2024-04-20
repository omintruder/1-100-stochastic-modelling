1-100 stochastic modelling
--- 

This is a mathematical research project devoted to model a stochastic process which came to my attention at David Sumpter's public lecture at the University of Oxford (https://www.youtube.com/watch?v=PPCfDe8TfJQ, 43:30). The rules are as follows:

Work in pairs. One of you thinks of a number between 1 and 99. Then the other person does the following.
1. If the number is less than 50, double it, and this is the new number. (e.g. for 42: 42x2=84).
2. If the number if greater than 50 take it away from 100 and then double it to get the new number (e.g. for 84: (100-84)x2=32).
3. Now say the new number to your partner and they repeat step 1 or 2.
What number do you get to eventually?

The answer is you don't get to such a number. You get into an infinite cycle, moreover, that happens very quickly. Some numbers', like 40 or 80, route to cycle takes only 2 step (40 -> 80 -> 40). Most numbers last for 12 steps (7, 99), but no last for more. Though initial author's design doesn't imply that, I allow 50 into the model, as author allows 25 and 75, which turn into 50 after the first step. Code in the 'stochastic process.pynb' model this process and gives off statistical results, copies of which, for the sake of convinience, is put in the 'results.txt' file. Math is beautiful!
