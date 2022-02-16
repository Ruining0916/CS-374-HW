$$X \sim \operatorname{Binomial}(n, p) \ \ \ \ \ \text{or} \ \ \ \ \ b(n, p)$$
**Idea:**
The probability that after $n$ [[Bernoulli trail]], $x$ of them is success
Therefore it is the generalized Bernoulli, since it is the same as Bernoulli when $n = 1$ 
**Input:** 
$x =$ number of success wanted
**Parameters:** 
$n =$ total number of Bernoulli trails (sample size)
$p =$ probability of success for each Bernoulli trails

---
**Equations:**
![[Screen Shot 2022-02-14 at 2.13.20 PM.png]]

---
**e.g.** Given $x = 3$ with parameters $n = 5, p = 0.6$, $$f(3) = P(X = 3) = \binom5 3 0.6^{3}0.4^{2} = 0.3456$$

---
$$\text{R-lang} : \text{dbinom(), 
pbinom()}$$
---

$X$ is a binomial random variable if the following are all true

1. A [[Bernoulli trail]] (success-failure) experiment is performed $n$ times, where $n$ is a (non-random) constant.
2. The trials are <u>independent</u>.
3. The probability of success on each trial is a constant $p$; the probability of failure is $q=1-p$.
4. The random variable $X$ equals the number of successes in the $n$ trials.

---
Explanation:
![[Screen Shot 2022-02-14 at 2.00.12 PM.png]]
![[Screen Shot 2022-02-14 at 2.00.49 PM.png]]



---
visualization: https://shiny.rit.albany.edu/stat/binomial/


---
What does the following mean?
$$X \sim \operatorname{Binomial}(n, p) $$
?
It means: $X$ is a random variable that follows a binomial distribution of specified <u>parameters</u> $n$ and $p$. (to calculate the final value, plug in x for the pmf)


---
What does $d$ and $p$ stand for in dbinom() and pbinom()?
?
d = discrete (pmf)
p = probability (cdf)

[[Probability Distribution]]
#flashcards 
#review 


