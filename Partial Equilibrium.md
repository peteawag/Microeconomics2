---
marp: true
paginate: true
---
<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
section.lead h1 {
  text-align: center;
  font-size: 30pt;
}

section.lead {
  text-align: center;
  font-size: 25pt;
}

section.lead p {
  text-align: center;
  font-size: 18pt;
}
</style>

<!-- _class: lead -->




# Microeconomics 2

## Section 1: Partial Equilibrium

<br>



Peter Wagner, Ph.D. 
Department of Economics
University of York
![center w:5cm](https://www.yorksciencepark.co.uk/wp-content/uploads/2019/01/University-of-York-.jpg)

---

<!-- _class: lead -->

## 1. Introduction

---


There are two ways in which economists have studied market economies:
- General equilibrium (Leon Walras): whole economy
- Partial Equilibrium (Alfred Marshall): single good

Here we study the **Partial Equilibrium Framework!**

---


Why? $\to$ Partial equilibrium model much simpler than any general equilibrium model.


**But:** Not as realistic, as important interdependencies are ignored

In contrast to general equilibrium model, we have: 
- no trade between consumers
- no trade between firms
- significant restrictions on preferences



---

| |Partial Equilibrium| General Equilibrium|
|-|---|---|
| Developed by| Alfred Marshall| Léon Walras|
| Considers| One good vs "everything else"| Whole Economy|
| Underlying Assumption | Markets for different goods independent    | Markets for different goods are interdependent. |
| Equilibrium| Price based on prices of other goods being constant| Prices of goods are determined simultaneously   |
| Pros| Tractable, welfare analysis and comparative statics feasible | More realistic|
| Cons| Some interactions are ignored | More difficult|


---



<!-- _class: lead -->

## 2. Consumers


---



**General assumptions**: Consumers are rational!

- Maximize their own "utility"
- Understand all aspects of the market
- Unlimited computational power


---

### Preferences in the partial equilibrium framework


- Partial equilibrium model:    
  - single consumption good as a "negligable" part of whole economy
  - all other goods bundled  together as one good


- That the market for the consumption good is negligable implies...
  - **negligable wealth effects**: change in income does not affect demand for our consumption good
  - **price independence**: change in the price of our good does not affect prices of other markets
- How can we represent preferences in a way that respects these properties?

---
### Quasi-linear utility model
<br>

We consider a consumer in a market with 2 goods: 
  - $x$ is a consumption good with price $p$
  - $m$ is everything else, or "money", with a price normalised to 1 (numeraire) 
  
The consumer has a given income $I$


---

**Definition:** A consumer is said to have quasi-linear preferences if she has a utility function of the form
  $$\begin{aligned}U(x,m) = u(x)+m\end{aligned}$$ 
where $u$ is increasing and concave (=inverse u-shape)

---
## Individual demand in quasi-linear model

<br>

Consumer $i$ maximises  utility:

  $$U(x,m)=u(x)+m  $$
  subject to the budget constraint 
  $$px+m=I$$

  where $I$ is the given income of the consumer.

---

Unconstrained problem:
 $$\max_{x}\ u(x)-px+I  $$
First-order condition
$$u'(x)=p$$
<br>

The demand of this consumer is a function $x^*(p)$ such that $u'(x^*(p))=p$ for all $p$



---


### No wealth-effects in the quasi-linear model
<br>

![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_quasi_linear/fig_quasi_linear.png?raw=true)


--- 





#### Fundamental Law of Demand

How does demand react to price changes?

- Recall: demand function $x^*(p)$ solves $u'(x^*(p))=p$
- Suppose the price increases: $\hat p>p$, so that $u'(x^*(p))<\hat p$
- $u$ is concave, so $u'(x)$ decreases in $x$
- Therefore: $x^*(\hat p)<x^*(p)$ 

Decreasing demand function:  **Fundamental Law of Demand** 


---
### Aggregate Demand



- Suppose $n$ individuals in the market with demands $x_1^*(p)$, $x_2^*(p)$, ..., $x_n^*(p)$
- **Aggregate demand** = sum of individual demands 
$$
    D(p)=x_1^*(p)+...+x_n^*(p)=\sum_{i=1}^n x^*_i(p).
$$
- If identical preferences $x_i^*(p)=x^*(p)$, then $D(p)=n x^*(p).$

--- 




### Inverse demand

If demand is strictly decreasing, we can invert it:

- **Demand curve:** quantity $q=D(p)$ demanded at price $p$.

- **Inverse demand function:** price $p=P^D(q)$ such that consumers demand $q$. 

Graphically, this corresponds to mirroring the demand curve along the $45^o$ line.



---

![center 120%](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_demand/fig_demand0001.png?raw=true)




---

### Inverse demand and marginal utility

For simplicity, suppose there are n identical consumers. 

Recall that for each $p$, the demand function of each consumer solves:
$$u'(x^*(p))=p$$

For given $q$, we have $p=P^D(q)$, so we can write
$$
u'(q/n)=P^D(q)
$$

**Lesson:** 

    For a given aggregate demand q, the inverse demand measures the corresponding 
    consumers' marginal utility


---

**Exercise:** Let a consumer's quasi-linear utility function be given by 
$$U(x,m)=u(x)+m$$ 
where $u(x)=x-x^2/2$.
1. Verify that $u''(x)<0$ and calculate the consumer's demand function.
2. Suppose there are 2 consumers with quasi-linear utility $U(x,m)$. Calculate Aggregate Demand.
3. Calculate the inverse demand.


---

<!-- _class: lead -->

## 3. Firms

---

### Profit maximisation and cost functions

Assumptions:
- Firms convert money into the consumption good
- The cost of producing an amount $q$ of the good is given by a cost function $C(q)$
- Firms are negligable in size compared to the market (= price-takers)
- Maximize profits


---
### Cost Functions

The total cost of production is the sum of fixed and variable costs
$$
C(q)=c(q)+F
$$

where
-  $F$: fixed costs, e.g., set-up costs
-  $c(q)$: costs that vary with output, e.g., labor.






---


**Marginal cost**: the cost of an additional (infinitesimal) unit of output; the slope of the cost curve at a given output level
$$
MC(q):=C'(q)
$$


**Average cost**: "cost per unit".  For $q>0$ the firm's average total cost function is
$$
AC(q)=\frac{C(q)}{q}
$$




---
### Convexity of costs

General assumption: cost function is increasing  and convex, 
$$C'(q)>0, C''(q)>0$$

Reflects **Law of diminishing returns from production**: Using production processes more intensively makes it over-proportionally less efficient

These assumption imply
- profit maximisation problem has a unique solution
- marginal cost increasing 
- average cost curve has an inverse u-shape
- marginal cost curve and  average cost intersects at its minimum.

---
**Why does marginal cost intersect the average cost at its minimum??**

- Average cost is $AC(q)=C(q)/q$
- If we produce one more item 
    - if additional item cheaper than average cost $\to$ average cost decreases
    - if additional item more expensive than average cost $\to$ average cost increases
- With convex cost, $MC$ is increasing, so $MC$ and $AC$  must intersect once, at the minimum of $AC$


---
![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_cost/fig_cost_2.png?raw=true)

---

### Individual supply of the firm
<br>

- Firm maximises profits:
$$
\max_q \pi(q)=pq-C(q)
$$
- The first-order condition for optimal output is 
$$
p=C'(q)
$$
- The supply of the firm is a function $y^*(p)$ such that $p=C'(y^*(p))$ for all $p$. 



---

### Aggregate supply


- Suppose $m$ firms in the market with supplies $y_1^*(p)$, $y_2^*(p)$, ..., $y_n^*(p)$
- **Aggregate supply** = sum of individual supplies 
$$
    S(p)=y_1^*(p)+...+y_n^*(p)=\sum_{j=1}^n y^*_j(p).
$$
- If identical supply functions: $y_i^*(p)=y^*(p)$, then $S(p)=m y^*(p).$

---

### Properties of aggregate supply 

- If $c$ is convex, then $S(p)$ is increasing!  **Intuition:** if $p$ increases, produce additional units until marginal cost reaches the new price  
- Inverse supply: we can invert $S(p)$ and obtain a function $P^S(q)$ which gives the price that induces a given supply $q$.

---

**Exercise:** Consider the cost function 
$$
C(q)=10+\frac{q^2}{2}
$$

1.  Draw  marginal cost, average cost average variable cost and the average fixed cost corresponding to $C(q)$
2.  Derive the firm's indidivual supply function
3.  Suppose there are 10 firms. Find the Aggregate Supply. 



---




<!-- _class: lead -->

## 4. Elasticities

---

### Demand Elasticity

- *Elasticity* = sensitivity of demand changes in response to price changes

- Important concept: comparative statics, monopoly pricing, etc.

- How to measure? Slope of demand curve would work:
$$D'(p)=\frac{\Delta D(p)}{\Delta p}$$

- But then our measure of elasticity will depend on how we measure things (smaller units, larger change)

- Solution: measure changes **proportionally** in %

---

**Informal definition of demand elasticity**
<br>

$$\text{demand elasticty}=\frac{\text{\% change in demand}}{\text{\% change in price}}$$

In words: 

    The elasticity of demand is defined as the % change in demand resulting 
    from a price increase, divided by the % change in price


---

We distinguish between two measures of elasticity 
  - Arc-price elasticity: sensitivity of demand between two different prices 
  - Point-price elasticity: sensitivity of demand "locally" at a given price $p$


---
### Arc-price elasticity




**Definition**: The *arc-price elasticity* of a demand  $D$ between prices $p$ and $p'>p$ is 
$$
\epsilon_A(p,p')=\left|\frac{\left(\frac{D(p')-D(p)}{D(p)}\right)}{\left(\frac{p'-p}{p}\right)}\right|.
$$

Note: demand is decreasing, so we have $\epsilon_A(p,p')\in [0,\infty)$.

---

### Point-price elasticity




**Definition**: The *point-price elasticity* of a differentiable demand function $D$ at price $p$ is defined as
$$
\epsilon_P(p)=\lim_{p'\to p}\left|\frac{\left(\frac{D(p')-D(p)}{D(p)}\right)}{\left(\frac{p'-p}{p}\right)}\right|=\left|D'(p)\frac{p}{D(p)}\right|.
$$

Note: demand is decreasing, so we have $\epsilon_P(p)\in [0,\infty)$.




---
![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/elasticity2.png?raw=true)


---

**Terminology:** Elastic vs inelastic demand

We call a demand function $D(p)$  ...

- ... elastic at $p$ if $\epsilon(p)>1$
- ... unit-elastic at $p$ if $\epsilon(p)=1$ 
- ... inelastic at $p$ if $\epsilon(p)<1$


---


### Supply Elasticity

Supply elasticity is defined in the same way as demand elasticity
<br>
$$\text{supply elasticty}=\frac{\text{\% change in supply}}{\text{\% change in price}}$$

The definition of arc- and point-price elasticities are analogous to the demand case

---

**Exercises:** 
- Calculate the arc-price elasticity of the demand $D(p)=\max\{1-p,0\}$
- Derive the point-price elasticity of $D(p)=1/p^e$, where $e$ is an arbitrary positive number
- Calculate the arc-price elasticity of the supply function $S(p)=p^2$

---




<!-- _class: lead -->

## 5. Surplus and Welfare

---

### Surplus and Welfare

- How should we measure market performance and "gains from trade"?


- In his seminal book Principles of Economics (1890), Alfred Marshall  proposes to measure "surplus pleasure":

  > The price which a person pays for a thing can never exceed, and seldom comes up to that which he would be willing to pay rather than go without it [...]; and he thus derives from the purchase a surplus of pleasure. **The excess of the price which he would be willing to pay rather than go without it, over that which he actually does pay**, is the economic measure of this **surplus pleasure.** 

*(Alfred Marshall, 1890)*



---

In other words: consumer surplus are the consumers' **gains from trade**

For simplicity: infinitely many identical consumers of mass 1

Each consumer has utility $U(x,m)=u(x)+m$. 
- Utility of consumer with wealth $m$ and without trade: $u(0)+m$
- Utility of consumer with wealth $m$ who buys $q$ goods at price $p$: $u(q)+m-pq$

Consumer surplus from such a trade at given price $p$:
$$CS(p,q)=u(q)-u(0)-pq$$


---

**How can we illustrate consumer surplus in our diagrams?**
#

- Write as integral
$$
\begin{aligned}
CS(p,q)&=u(q)-u(0)-pq=\int_0^q(u'(x)-p)dx
\end{aligned}
$$
- Using the identity $u'(x)=P^D(x)$ from the consumer maximisation problem yields
$$
CS(p,q)=\int_0^q(P^D(x)-p)dx
$$
- Implication: the consumer surplus is the area above the price line and below the inverse demand curve.


---
### Consumer Surplus

![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/consumer_surplus.png?raw=true)


---

## Producer Surplus


- The producer surplus is defined in a similar way. 

- **Producer surplus:** profits = the revenue a firm receives from selling a good at a given price minus the cost of producing it

$$PS(p,q)=pq-c(q)$$

---

- Similar to the consumer surplus case, we can represent this in our standard diagrams.
$$PS(p,q)=\int_0^{q}(p-c'(y))dy$$

- Using the identity $P^S(y)=c'(y)$ from the profit maximisation problem yields
$$PS(p,q)=\int_0^{q}(p-P^S(y))dy$$
- Implication: the producer surplus is the area underneath the price line and above the inverse supply curve.


---
![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/producer_surplus.png?raw=true)





---

## Welfare 

The "welfare" generated in the market which is the total gains it generates. 

**Definition:** The **(Social) Welfare** is the sum of consumer and producer
$$W(p,q):=CS(p,q)+PS(p,q)$$



---
![bg left:60% contain](https://core-econ.org/the-economy/book/images/web/figure-08-05-01-02.jpg)

### Welfare: 

Welfare represents the sum of consumers surplus (utility gain) and producer surplus (profits)






---



**Exercises:** 

1. Calculate the consumer surplus for the demand functions
    - $D(p)=\max\{1-p,0\}$ 
    - $D(p)=\max\{\sqrt{1-p},0\}$
2. Calculate the producer surplus for the  supply function $S(p)=p^2$. 
3. For a given pair of demand and supply functions, at which price is welfare maximised?


---




<!-- _class: lead -->

## 6. Competitive Equilibrium

---

###  Competitive Equilibrium

- We now take the aggregate demand and supply function to characterize market equilibria. 

- **Basic idea:** find a price such that aggregate demand meets aggregate supply.

- Formally, we want find a price $p$ such that $D(p)=S(p)$
- This is called the "market clearing condition". 




---

### Short-run equilibrium

- We first consider competitive equilibrium in the short-run. 

- Properties of short-run equilibria:
   - Fixed cost are sunk, so no exit if firms make losses
  - No entry of new firms


---

### Formal Definition of a Short-Run Competitive
<br>

**Definition**: A *short-run competitive equilibrium* consists of a price $p^*$ and allocations $(x_1^*,\ldots, x_n^*)$ and $(y_1^*,\ldots, y_k^*)$ such that

-  $D(p^*)=S(p^*)$,
-  $x_i^*$ maximizes consumer $i$'s utility at price $p^*$ for each $i$, 
-  $y_j^*$ maximizes the profit of firm $j$ at price $p^*$ for each $j$.


---



### Properties of the competitive equilibrium: 


- In equilibrium, the market clears 
    - Each buyers receives the quantity she demands
    - Each firm sells the quantity it wants to supply 
-  There is neither excess demand nor excess supply  
- There is no way to improve the outcome! $\to$ Efficiency!

---

![w:100cm h:15cm](https://kmlv.github.io/Econ100A_F17/img/Ch16/TS.png)


---

### Long-run equilibrium

- Short-run equilibria are not "stable" in the long-run
  -  profits attract new firms, new firms enter, supply decreases, price falls
  - firms exit when they make losses, supply falls and market price increases

- Long-run equilibrium:  allows for entry and exit!

- The number of firms adjusts so that firms eventually make zero profit 




---

### Formal Definition of a Long-Run Competitive Equilibrium
###

**Definition:** A *long-run competitive equilibrium* consists of a price $p^*$, a number of firms $k^*,$ and allocations of demands $(x_1^*,\ldots, x_n^*)$  and  $(y_1^*,\ldots, y_k^*)$  such that $(p^*,x^*,y^*)$ is a short-run equilibrium and 
$$
\pi_j^*(p^*)=0
$$
for all $j=1,2, \ldots,k$.


---
**Example:** How does this work exactly?

- Consider a market in which 

  1. the demand function is $D(p)=100/p$, 
  2. there are $k$ firms with identical cost function $C(q)=q^2/2+10$
- We first solve for a short-run equilibrium:
  - Profit maximisation: $q=p$
  - Supply function $S(p)=kp$. 
  - Short-run equilibrium: $100/p=k p\Rightarrow p=\frac{10}{\sqrt k}$.
  - Profit for each firm: $\pi=pq-q^2/2-10=\frac{50}{k}-10$

---
**Compare three cases:**

  - Suppose initially $k=25$. Then firms will exit since profits are 

    $$\pi =\frac{50}{25}-10=-8<0.$$
  - Suppose initially $k=1$. Then firms will enter since profits are
    $$\pi =\frac{50}{1}-10=40>0.$$

  - The long-run equilibrium number of firms is $k=5$, since then 
   $$\pi =\frac{50}{5}-10=0.$$


---


---

**Difference between short-run and long-run in short:**
- Short-run equilibrium: $MC=p$
- Long-run equilibrium: $MC=AC=p$ 

Or in words:
- Short-run: firms only consider marginal cost ignore fixed consists
- long-run: firms take marginal and fix cost into account

---


**Technical note:** Integer Problems


 - Sometimes the number of firms in the long run is not a whole number
 - Two solutions:
    1. Redefine equilibrium. No firm in the market makes losses and no additional firm can make a profit
    2. Make firms "infinitesimal" (negligibly small). Then $k^*$ represents a "mass" of firms (infinitely many points)





---



**Exercise**: Let the demand function be $D(p)=\max\{100-p,0\}$ and supply $S(p)=kp$, where $k$ is the number of firms, and $C(q)=q^2/2+10$ is the firms' cost function.

1. Find the price, quantity and number of firms in a long-run equilibrium.
2. How does the long-run equilibrium change when demand changes 
to $D(p)=200-p$.

---




<!-- _class: lead -->

## 6. Taxes


---

### Taxes


- We now evaluate the effect of a goverment tax on the equilibrium. 
- **Quantity tax**: for any purchase of $q$ units, pay tax $tq$
- In equilibrium, consumers and producers face different prices:

  - Price paid by consumers: $\hat p_c$
  - Price received by firms: $\hat p_f$
  - Price difference: $\hat p_c-\hat p_f=t$


---
**Equilibrium with taxation**
- Tax is equivalent to a shift in demand or a shift in supply
- In equilibrium, markets must clear: 

  - quantity demanded  must equal the quantity supplied 
  - at equilibrium quantity $q^*$, difference between prices equal the tax
$$
P^D(q^*)=P^S(q^*)+t
$$
- What about surplus?


---
![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_deadweight/fig_deadweight0001.png?raw=true)

---
![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_deadweight/fig_deadweight0002.png?raw=true)

---
![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_deadweight/fig_deadweight0003.png?raw=true)

---
![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_deadweight/fig_deadweight0004.png?raw=true)

---
![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_deadweight/fig_deadweight0005.png?raw=true)

---
![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_deadweight/fig_deadweight0006.png?raw=true)





---

### Tax Incidence: who pays the tax? 

- The distribution of tax burden determined by relative Elasticities

  - consumers bear more burden if demand more inelastic than supply
  - firms bear more burden if supply more inelastic than demand
- The higher the elasticity of demand and supply, the larger the deadweight loss

---
**Consumers bear burden when demand perfectly inelastic:**


![center w:30cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/tax_incidence/tax_incidence_producers.png?raw=true)

---
**Firms bear burden when supply perfectly inelastic:**

![center w:30cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/tax_incidence/tax_incidence_consumers.png?raw=true)


---




<!-- _class: lead -->

## 6. Monopoly


---

### Monopoly

A *monopoly*  is a market for a good that is supplied by a single firm (from ancient greek *monopolion*, "a right of exclusive sale"), supplier in a monopoly is called a *monopolist*. 

**Examples of monopolists:**


  -  Microsoft, market for operating systems. Market share ' 90\%.
  -  Google: 70\% of US web searches, 70\% of online advertising market.
  -  Gillette, razor blades market, 72\% market share. 
  -  Utilities (electricity, water, telephone, rail, etc.)



---

### Monopoly profits


Market price at supply $q$ is $P(q)$. 

Monopolist's profits
$$
\pi_m(q)=P(q)q - C(q) .
$$





---
To solve for the optimal level of output,  solve the f.o.c. 
$$
\pi_m'(q)=\underbrace{\frac{d}{dq}P(q)q +P(q)}_{:=MR(q)} \ - c'(q)=0
$$

Denote the solution by $q_m$. 


---

### Properties of monopoly output

- Comparison with competitive equilibrium   

    - competitive equilibrium: output $q^*$ solve $MC(q)=P(q)$
    - monopoly output: output $q_m$ solves $MC(q)=MR(q)$ 

- Demand is decreasing $\frac{d}{dq}P(q)<0$, hence $MR(q)<P(q)$, 

- $\Rightarrow$ monopolist under-supplies the market: $q_m<q^*$!! 


---

![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/monopoly-pricing.png?raw=true)

---


### Inverse Elastiticy Rule

- Intuitively, a monopolist can exploit the fact that demand is inelastic.

- The relationship between the profit for the monopolist and elasticity of demand s captured by the **Inverse Elasticity Rule**.

- Consider the marginal revenue for the monopolist:
$$
(*) \ \ \ MR(q)=P(q) + P'(q)q= P(q) \Big(1 + {\color{red}\underbrace{P'(q)\frac{q }{P(q)}}_{=-1/\epsilon}}\Big)
$$

---


- Since $P(q)$ is the inverse of $D(p)$:
$$D(P(q))=q\Rightarrow D'(P(q))P'(q)=1\Rightarrow P'(q)=\frac{1}{D'(P(q))}$$

- Further, recall the definition of elasticity of demand

$$P'(q)\frac{q }{P(q)}=\frac{1}{D'(P(q))}\frac{D(p)}{p}=-\frac{1}{\epsilon(p)}$$

---

- Substituting the first and then the second identity into into equation $(*)$ on the previous slide, we find 
$$(**)\ \ \ MR(q)=P(q) \left(1 - \frac{1}{\epsilon(P(q))}\right)$$


 - Monopolist operates in elastic region of demand $(\epsilon>1)$! Why? 

$$
MR(q)>0 \Rightarrow 1-\frac{1}{\epsilon(P(q))}>0\Rightarrow
\epsilon(P(q))>1
$$
---

## Two-Part Tariffs

- So far we assumed the monopolist sets a uniform price. 

- The monopolist can do better with so-called two-part tariffs!

- Basic idea: in addition to a per unit price, charge an upfront fee

- With a "two-part" tariff, the monopolist supplies the efficient amount

- BUT: the monopolist extracts the entire surplus!!


--- 

####  Optimal two-part tariff

- Principal supplies $q$ at price $p=P(q)$. 

- Consumer willing to pay $T\le CS(q)$ upfront. 

- Price equal to competitive price: $p^*$ $\rightarrow$ demand $q^*=D(p^*)$
- Fee equal to surplus $T^*=CS(q^*)$. 


---

![bg left:55% contain](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/two_part_tariff.png?raw=true)


**Two-part tariff**

Monopolists extracts all surplus: 
1. Consumers demand efficient quantity
2. Monopolist is paid upfront



---

### Oligopoly: Cournot model



- Two symmetric firms that supply entire market. 
- Not price takers: they affect price through outputs
- Firms sets their outputs 
  - independently (no coordination)
  - simultaneously (cannot observe the choice of the other firm)

---

Profit of firm $i$:
$$\pi_i(q_1,q_2)=P(q_1+q_2)q_i-C(q_i)$$
<br>

**Market Equilibrium:** A Cournot Equilibrium is a pair of outputs $(q_1^*,q_2^*)$ such that output $q_1^*$ maximizes the profit of firm 1 given $q^*_2$, and vice versa.



---

### Linear Cournot

For simplicity, suppose we have an inverse demand function 
$$P(q)=a-bq$$
and linear cost $C(q)=c q$


---

The profit maximization problems of both firms are

$$
\begin{aligned}
\max_{q_1} \big(a-b(q_1 + q_2^*)\big)q_1 - c q_1,\\
\max_{q_2} \big(a-b(q_1^* + q_2)\big)q_2 - c q_2.
\end{aligned}
$$


---






The first-order conditions associated with these maximization problems are
$$
\begin{aligned}
a-2bq_1^* - bq_2^* - c =0\Longrightarrow q_1=\frac{a-c-bq_2^*}{2b}\\
a-bq_1^* -2 bq_2^* - c =0\Longrightarrow q_2=\frac{a-c-bq_1^*}{2b}.
\end{aligned}
$$

Two find the Cournot equilibrium, we solve the second equation for $q_2^*$ and substitute in the first to solve for $q_1^*$. This yields the solution
$$
q^*:=q_1^*=q_2^*=\frac{a-c}{3b}.
$$

---






![center w:15cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_cournot/fig_cournot0001.png?raw=true)

---


### Example: Cournot vs. Monopoly and Perfect Competition 


Suppose our demand function is $D(p)=8-p$ and firms have  zero cost $c(\cdot)=0$. 

<br>

**1. Competitive Equilibrium**

The competitive equilibrium price equal marginal cost: $p^*=0$. 

Total demand is $q^*=D(p^*)=8-0=8$.

The competitive equilibrium is $(p^*,q^*)=(0,8)$.


---
**2. Monopoly**

The monopolist solves
$$
\max_{q} \pi(q)=\big(8-q\big)q
$$

FOC is $\pi'(q)=8-2q_m=0$, so optimal quantity is $q_m=4$. 

Corresponding price is $p_m=P(4)=8-4=4$


Monopolist outcome $(p_m,q_m)=(4,4)$


---
**3. Cournot**

Cournot quanities are
$$q_1=q_2=\frac{8}{3}=2 \frac{2}{3}$$

Aggregate Supply is $q=2\times 2 \frac{2}{3}=5\frac{1}{3}$. 

Corresponding price is $p=P(5\frac{1}{3})=8-5\frac{1}{3}=2 \frac{2}{3}$


Monopolist outcome $(p,q)=(2 \frac{2}{3},5\frac{1}{3})$

---


## Review Questions

- What is the purpose of the Partial Equilibrium model?
- What is quasi-linear utility, and why do we use these types of preferences?
- What is the purpose of "elasticity", and why do we define it in terms of %-changes? 
- Why are surpluses the areas between demand and supply?
- What is the difference between efficiency and welfare?
- Why does a monopolist undersupply the market?
- What is the meaning of the "inverse elasticity rule"
- What is the difference between an oligopoly and a perfectly competitive market?







