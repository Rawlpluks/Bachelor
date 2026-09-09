### Layer 1 - Probability space, filtration, measurable structure
The part that most directly closes the LIM/analysis gap.
**[[Schilling]]**:
- $\sigma$[[sigma-algebra|-algebras]]
- [[Measures]]
- [[Measurable functions]] (random variables as measurable maps)
- Construction of the integral
- The convergence theorems ([[MCT]], [[Fatou]], [[DCT]])
- $L^p$ [[Lp spaces|spaces]]
- [[Radon-Nikodym]]
- [[Conditional expectation]]
Roughly the first $2/3$ of the book in sequence

[[Williams]]: (optional)
- Ch. 9 - Conditonal Expectation
- Ch. 10 - [[Martingales|Discrete Martingales]]
A gentler parallel read if [[Schilling]]'s treatment feels terse

[[ABGK]]:
- Ch. II.1 (lightly) - pick up the continuous-time [[filtration]]/adapted-process vocabulary that [[Schilling]] doesn't emphasize

### Layer 2 - Counting processes and Doob-Meyer
[[ABGK]]:
- Ch. II - [[Counting processes]], [[intensity]], [[sigma-algebra|the predicatble $\sigma$-algebra]], the compensator as [[predicatble projection]], the [[Doob-Meyer decomposition]] $N=\Lambda+M$ and [[stochastic integrals]] w.r.t. M
[[Schilling]]:
- The Martingale chapters give the discrete-time Doob decomposition, which is the exact discrete shadow of Doob-Meyer - Worth reading first so the continuous version isn't a cold sstart

! **NOTE** : [[Schilling]] stops at discrete-time Martingales. The continuous-time counting-process martingales is *only* in [[ABGK]] !

### Layer 3 - Reverse-time truncation (the core)
[[ABGK]]:
- Ch. III - [[Model specification]], [[independent censoring]], and [[truncation]] 
	Where the standard left-truncation + right-censoring risk-set apparatus is built .
	The reversal argument's whole point is to land a right-truncated delay onto *this machinery*, so an understanding is neccessary 
The reversal trick itself isn't in [[ABGK]], so this is the target we're mapping onto, not the source of the argument. 
Match [[Key people|Munir]]s indexing conventions rather than [[ABGK]]'s where they differ

### Layer 4 - Partial likelihood with maritngale justification
[[ABGK]]:
- Ch. VII - Cox-type [[semiparametric hazard regression]], the [[partial likelihood]], the [[Andersen-Gill]] score-as-martingale result
- Ch. II - The [[Martingales|martingale CLT]] section. This is the asymptotic engine behind consistency and asymptotic normality. Read as a pair with VII
[[Matinussen]]:
- Cox/partial-likelihood chapters are the more applied complement if [[ABGK]] VII is heavy going. Also closer to how we will actually fit the models

### Layer 5 - Product integrals (continuous -> discrete)
[[ABGK]]:
- Ch. II - [[Product-integration]] and the [[Duhamel equation]]. The formal object
- Ch. IV -[[ Nelson-Aalen]]
- Ch. V - Kaplan-Meier / Aalen-Johansen [[product-limit]]. The estimators that instantiate it. This is where the product integral becomes concrete, which is exactly where the chain-ladder-as-discrete-product-integral remark gets its footing