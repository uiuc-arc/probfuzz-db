# Bug Info #

### ProbFuzz Edward 1 ###

**Type** : [Commit](https://github.com/blei-lab/edward/commit/3616d41a28ccec808990b97c9c0272081463e5f5)

**Category** : Numerical

**Description** : Fixing invgamma sampling to prevent returning Inf

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/3616d41a28ccec808990b97c9c0272081463e5f5)

### ProbFuzz Edward 2 ###

**Type** : [Issue](https://github.com/blei-lab/edward/issues/724)

**Category** : Language/Translation

**Description** : Instability of Categorical distribution in tensorflow

**Fix version** : NA (fix was in tensorflow; which Edward uses as its underlying framework.)

### ProbFuzz Edward 3 ###

**Type** : [Issue](https://github.com/blei-lab/edward/issues/347)

**Category** :  Language/Translation

**Description** : Inference object is not stateless

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/10118dbd5cc5f0f93522850656b07514b0d88eee)

### ProbFuzz Edward 4

**Type** : [Issue](https://github.com/blei-lab/edward/issues/518)

**Category** : Language/Translation

**Description** : Importing edward breaks python command-line

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/e7efb88d15627839d801e3b4268ea38e570984d9)

### ProbFuzz Edward 5

**Type** : [Issue](https://github.com/blei-lab/edward/issues/376)

**Category** : Language/Translation

**Description** : Klqp is broken

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/b643111af0484035b4d44125539e2d7a72f77b03)

### ProbFuzz Edward 6
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/1feded926d197b4db0acb885d2717ed046f0960d)

**Category** : Language/Translation

**Description** : Bug in multinomial

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/1feded926d197b4db0acb885d2717ed046f0960d)

### ProbFuzz Edward 7
 
**Type** : [Issue](https://github.com/blei-lab/edward/issues/262)

**Category** : Accuracy/Inference

**Description** : Binary accuracy metric evaluates to 1.0 when benoulli mean is 0.5

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/574c70366e17529d01a4927bc05eda17a24ef495)

### ProbFuzz Edward 8
 
**Type** : [Issue](https://github.com/blei-lab/edward/issues/788)

**Category** : Accuracy/Inference

**Description** : Incorrect calculation of ratio in Metropolis Hastings

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/4d8c1f3af0db805a0653a2e749acb25b8e58df42)

### ProbFuzz Edward 9
 
**Type** : [Issue](https://github.com/blei-lab/edward/issues/722)

**Category** : Accuracy/Inference

**Description** : SGLD variance calculation incorrect

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/79f4193156e03f7721e60b8715d7e76bf638a41c)

### ProbFuzz Edward 10 
 
**Type** : [Issue](https://github.com/blei-lab/edward/issues/752)

**Category** : Accuracy/Inference

**Description** : KLqp normalization issue

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/972a9d9b90ea270a20e109a5ca7d7d3ea3f96885)

### ProbFuzz Edward 11 
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/26cabaff89e0bd559d1f8560f262418e81dea534)

**Category** : Accuracy/Inference

**Description** : Bug in logpdf computation of student T distribution

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/26cabaff89e0bd559d1f8560f262418e81dea534)

### ProbFuzz Edward 12
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/fe016576a977f0f1cd1d365ec2c04d1cea70b399)

**Category** : Accuracy/Inference

**Description** : Bug logpdf computation of uniform distribution

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/fe016576a977f0f1cd1d365ec2c04d1cea70b399)

### ProbFuzz Edward 13
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/43d8a3958d93db946202d27c7ad308d0cd0b8bda)

**Category** : Dimension/boundary-value

**Description** : Distributions dont consider shapes of inputs

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/43d8a3958d93db946202d27c7ad308d0cd0b8bda)

### ProbFuzz Edward 14
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/6a4289ff10860372960a99ddef655c3db3e227b5)

**Category** : Dimension/boundary-value

**Description** : Posteriors do not consider varying dimensions

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/6a4289ff10860372960a99ddef655c3db3e227b5)

### ProbFuzz Edward 15
 
**Type** : [Issue](https://github.com/blei-lab/edward/issues/78)

**Category** : Misc

**Description** : Bernoulli data throws ValueError

**Fix version** : Closed

### ProbFuzz Edward 16
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/5086e4941ea4d3851d7a902aadaa1f68480f31c9)

**Category** : Misc

**Description** : Fixing MAP

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/5086e4941ea4d3851d7a902aadaa1f68480f31c9)

### ProbFuzz Edward 17
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/002a27e203d296d37c5a832aae286eca13e9eed6)

**Category** : Misc

**Description** : Fixing multinomial entropy 

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/002a27e203d296d37c5a832aae286eca13e9eed6)

### ProbFuzz Edward 18
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/fea69a04c2b62ef9ba48496ea5d9e8ef790e29ba)

**Category** : Misc

**Description** : Fixing variational init for instances containing layers

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/fea69a04c2b62ef9ba48496ea5d9e8ef790e29ba)

### ProbFuzz Edward 19
 
**Type** : [Commit](https://github.com/blei-lab/edward/commit/008047dd2b453e230aac9f8aac2fcce7784720dc)

**Category** : Misc

**Description** : Fixing KLpq

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/008047dd2b453e230aac9f8aac2fcce7784720dc)

### ProbFuzz Edward 20
 
**Type** : [Issue](https://github.com/blei-lab/edward/issues/638)

**Category** : Misc

**Description** : No error message for scaling non-analytic KL term

**Fix version** : [Commit](https://github.com/blei-lab/edward/commit/c9afcb1fdf97d0336a77526951421d3443bc2fa3)

