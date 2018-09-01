# Bug Info #

### ProbFuzz Stan 1 ###

**Type** : [Issue](https://github.com/stan-dev/stan/issues/1610)

**Category** : Numerical

**Description** : ADVI produces NaN after 50 iterations

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/99289c85140a5c665842e732d3612668f449a7fb)




### ProbFuzz Stan 2 ###

**Type** : [Issue](https://github.com/stan-dev/stan/issues/1766)

**Category** : Numerical

**Description** : Generated C++ code assigns NaNs to integers on init

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/51df80c2d612e71f47b0b34918c258ba4d9c34c2)



### ProbFuzz Stan 3 ###

**Type** : [Issue](https://github.com/stan-dev/stan/issues/1308)

**Category** : Numerical

**Description** : NaN error for `<lower=0>` parameter

**Fix version** : NA (Closed)




### ProbFuzz Stan 4

**Type** : [Issue](https://github.com/stan-dev/stan/issues/1053)

**Category** : Numerical

**Description** : overflow in poisson_rng

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/73309790b298daa274752106825fcd7cdefb802a)




### ProbFuzz Stan 5

**Type** : [Commit](https://github.com/stan-dev/stan/commit/95752119e056f4fd7e4899732c6039dff17391bd)

**Category** : Numerical

**Description** : `0*log(0)=NAN` issue in bernoulli_log()

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/95752119e056f4fd7e4899732c6039dff17391bd)



### ProbFuzz Stan 6
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/121)

**Category** : Numerical

**Description** : HMC produces NaNs

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/dc3cbbdbdbcb39a4b6cebf609277bee3bb11ee4b)




### ProbFuzz Stan 7
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/19f6acd7805ad826cad8376b505685ffac532168)

**Category** : Numerical

**Description** : Log1p throws exception

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/19f6acd7805ad826cad8376b505685ffac532168)



### ProbFuzz Stan 8
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/335320da2840f84ea1b6aab1531d3d716443b53c)

**Category** : Numerical

**Description** : init_stepsize in HMC does not handle nans

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/335320da2840f84ea1b6aab1531d3d716443b53c)


### ProbFuzz Stan 9
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/28c10a10d29e6fe2f5d9db54863237e5d9703bd6)

**Category** : Numerical

**Description** : Distributions dont check for NaN

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/28c10a10d29e6fe2f5d9db54863237e5d9703bd6)


### ProbFuzz Stan 10 
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1357)

**Category** : Numerical

**Description** : Normal_cdf_log does not handle nans

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/1647ad59a0c6c7bfbcfeee037cef378d2b95a529)

 

### ProbFuzz Stan 11 
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1474)

**Category** : Numerical

**Description** : Dirichlet rng is unstable for small alpha values

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/45a82fde673f6fce13a6642cf24d7d6c3879e4b6)



 
### ProbFuzz Stan 12
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2410)

**Category** : Language/Translation

**Description** : integrate_ode_bdf allows real return on system function

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/2fc94d408c5625652972f799933f787d69bcc69f)




  -------------------------------------------------
    13:     = integrate_ode_bdf(twoCptModelODE,
    14:                         {1, 1.3}, 1.0, { 2.2, 3 }, { 1.0 }, { 1.0 }, { 2 },
    15:                         10, 10, 10);
                                          ^
    16: }
  -------------------------------------------------

PARSER EXPECTED: ")"

 

 
### ProbFuzz Stan 13
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2365)

**Category** : Language/Translation

**Description** : zero length simplex causes std::bad_alloc

**Fix version** : NA (This was fixed at the Stan level with the expanded scope of a try/catch block specifically to handle errors)



 

### ProbFuzz Stan 14
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2363)

**Category** : Language/Translation

**Description** : The parser does not throw necessary error message

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/b3ace8482ec0e7ab86f530e3950c74f52fea99d6)



### ProbFuzz Stan 15
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2178)

**Category** : Inference/Accuracy

**Description** : NUTS reports incorrect standard deviation and correlation coefficient

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/5845db97697b82566ef040e91d96feb5a609cada)



### ProbFuzz Stan 16
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1906)

**Category** : Inference/Accuracy

**Description** : Statistical efficiency in NUTS reduced

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/7a98bd2d311656a864022f6102fcc04e2e699352)



 
### ProbFuzz Stan 17
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1846)

**Category** : Inference/Accuracy

**Description** : NUTS uses slice sampler to select each point which is ungainly

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/21b36e3acd9f71d6eb37167984e45697913e9e41)




### ProbFuzz Stan 18
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/468ba130dee75c139986f0180b37e403bb22286d)

**Category** : Inference/Accuracy

**Description** : Accuracy of log1p can be better

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/468ba130dee75c139986f0180b37e403bb22286d)


### ProbFuzz Stan 19
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/8d61fa20498cde5101cb7689a5dc602f87df8f80)

**Category** : Inference/Accuracy

**Description** : Bug in ELBO

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/8d61fa20498cde5101cb7689a5dc602f87df8f80)


### ProbFuzz Stan 20
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/de64c61e098512552e46aa853006d6d3424e0da5)

**Category** : Inference/Accuracy

**Description** : Reimplementing NUTS

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/de64c61e098512552e46aa853006d6d3424e0da5)


### ProbFuzz Stan 21
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/d9d92363064d6c166f651cc5139fc50a5aacc6ff)

**Category** : Inference/Accuracy

**Description** : Nesterov optimization code

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/d9d92363064d6c166f651cc5139fc50a5aacc6ff)


### ProbFuzz Stan 22
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/4a29180225cc12ed5c443f547cf90e45f91b0b36)

**Category** : Inference/Accuracy

**Description** : NUTS algo fixes

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/4a29180225cc12ed5c443f547cf90e45f91b0b36)


### ProbFuzz Stan 23
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/68e8f26ba20f4fd6637027b68b03299c28dfaff2)

**Category** : Inference/Accuracy

**Description** : Fixing the acceptance probability in NUTS

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/68e8f26ba20f4fd6637027b68b03299c28dfaff2)


### ProbFuzz Stan 24
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/1dd2a14295c92502d07e9f81862c50ec0a38a98a)

**Category** : Inference/Accuracy

**Description** : Fixing the bernoulli logit derivative

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/1dd2a14295c92502d07e9f81862c50ec0a38a98a)


### ProbFuzz Stan 25
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/3cc01e6da1b5f5b4cdf97457cfb2f3c5768322ae)

**Category** : Dimension/boundary-value

**Description** : Fixing the log of a uniform density

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/3cc01e6da1b5f5b4cdf97457cfb2f3c5768322ae)


### ProbFuzz Stan 26
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2054)

**Category** : Dimension/boundary-value

**Description** : Normalization for lower truncated discrete distributions is off by one

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/40c82248daaa27b27b28118988dc954e0fbfb1a6)



### ProbFuzz Stan 27
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/537)

**Category** : Dimension/boundary-value

**Description** : Initialization on bounds should give more informative messages

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/40c82248daaa27b27b28118988dc954e0fbfb1a6)




### ProbFuzz Stan 28
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1179)

**Category** : Dimension/boundary-value

**Description** : Exponential distribution does not have the correct bounds checks

**Fix version** : NA



### ProbFuzz Stan 29
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1142)

**Category** : Dimension/boundary-value

**Description** : 

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/40c82248daaa27b27b28118988dc954e0fbfb1a6)



0  
-0.0412676  
-0.0412676  

 

### ProbFuzz Stan 30
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/82)

**Category** : Dimension/boundary-value

**Description** : RStan hangs during iteration

**Fix version** : [Pull](https://github.com/stan-dev/stan/pull/94)




### ProbFuzz Stan 31
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/b8d508675437e0fc4207d516495057ae61ba96fc)

**Category** : Dimension/boundary-value

**Description** : Fixing bug on boundary of binomial

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/b8d508675437e0fc4207d516495057ae61ba96fc)


### ProbFuzz Stan 32
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/1cbcad8f9daf21f237f35689f3fd5b53d34a53a0)

**Category** : Dimension/boundary-value

**Description** : Fixing bug on ill-defined gradients

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/1cbcad8f9daf21f237f35689f3fd5b53d34a53a0)


### ProbFuzz Stan 33
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/97372b25218ac05df4b7742f5595d142875c4d9a)

**Category** : Infinite loop

**Description** : Infinite loop caused by 0 next good fft size

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/97372b25218ac05df4b7742f5595d142875c4d9a)




### ProbFuzz Stan 34
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1904)

**Category** : Infinite loop

**Description** : Numerical instability of transition probabilities

**Fix version** : [Commit](https://github.com/stan-dev/stan/pull/1905/commits/feed2dbb699377bd696688f818e8703418b6fe83)



### ProbFuzz Stan 35
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/674)

**Category** : Infinite loop

**Description** : Infinite loop in gamma_p functions

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/e6193fd8aa135acf4f681fe9722c162ddd05cec0)



0  
-0.0412676  
0


### ProbFuzz Stan 36
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/217)

**Category** : Infinite loop

**Description** : Repeating error(nan) in optimization

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/0a553d62ff68006e19267ea627bf346c42240b0f)




### ProbFuzz Stan 37
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2241)

**Category** : Misc

**Description** : RNG in transformed data should use the overall seed

**Fix version** : [Issue Comment](https://github.com/stan-dev/stan/issues/2241#issuecomment-340786343)




### ProbFuzz Stan 38
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2101)

**Category** : Language/Translation

**Description** : Conditional operator fails to compile

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/ae423b2abda9619ed1c2bb97aa4cac96619cdb97)




### ProbFuzz Stan 39
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2386)

**Category** : Misc

**Description** : src/stan/io/writer.hpp is calling functions out of sync

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/6f3f21f4201b1c9ae191639d6e367fc7bc02644f)



### ProbFuzz Stan 40
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1017)

**Category** : Numerical (Not a bug)

**Description** : Adds NaN tests for all distributions

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/78dc3c718d7ceb32d577df3dd61a92f3bc79e688)




### ProbFuzz Stan 41
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/376)

**Category** : Numerical

**Description** : Phi(x) rounds down to 0 for x < -8.5

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/16046b8482e4370317721d2e0226e287ef0d0739)



### ProbFuzz Stan 42
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/8509c13144313d11684e3a38773b193264850b1b)

**Category** : Numerical

**Description** : Large initial step size causes irreversible NaNs in NUTS

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/8509c13144313d11684e3a38773b193264850b1b)



### ProbFuzz Stan 43
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/898)

**Category** : Numerical

**Description** : check_unit_vector fails to throw error if nans are passed in

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/b0ed65253e5797156aeed37e6f7cd5ca4263d05a)



### ProbFuzz Stan 44
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/850)

**Category** : Numerical

**Description** : stan::math::Phi returns 1.0 if nan is passed in, but it should either return NaN or throw an error

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/c59d97af8d557f53c06d3967e028577682b6de0e)



### ProbFuzz Stan 45
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/8fb396f30c3a0d94486e4123011196fd426d57ee)

**Category** : Numerical

**Description** : No check_not_nan() for vector input

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/8fb396f30c3a0d94486e4123011196fd426d57ee)




### ProbFuzz Stan 46
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/9f73c6ec48479e13f92af7dc0a4fa4341edbbd13)

**Category** : Numerical

**Description** : No check for NaN and infinite values in arguments

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/9f73c6ec48479e13f92af7dc0a4fa4341edbbd13)




### ProbFuzz Stan 47
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/2450)

**Category** : Inference/Accuracy


**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/a53cdcd3a25c7050aae71678e403f9478938a814)



### ProbFuzz Stan 48
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1731)

**Category** : Inference/Accuracy

**Description** : argument_configuration_test.cpp fails with ADVI occasionally

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/eeb5f456c178c2ccdbdca10501bf94398f115698)




### ProbFuzz Stan 49
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/2b82d32ffa6cc39b092b04d817cc4161111d826f)

**Category** : Inference/Accuracy

**Description** : Bug in learning rate calculation when using RMSprop

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/2b82d32ffa6cc39b092b04d817cc4161111d826f)


### ProbFuzz Stan 50
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/9d065fb69ffb550915d39d08e085642fbc7aec99)

**Category** : Inference/Accuracy

**Description** : Bug when using inc_beta in binomial distr file

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/9d065fb69ffb550915d39d08e085642fbc7aec99)


### ProbFuzz Stan 51
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/78783e8a8d28d4de33629d20721b9177b09d36de)

**Category** : Inference/Accuracy

**Description** : Depth bound in NUTS off-by-one error

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/78783e8a8d28d4de33629d20721b9177b09d36de)



### ProbFuzz Stan 52
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/247)

**Category** : Dimension/boundary-value

**Description** : The Dirichlet distribution does not have bounds checks on inputs.

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/a4cefe69efbee4b1af8e642501f74016af09ee39)




### ProbFuzz Stan 53
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/6fa3414416103bee84c0e2a295807c64404ec12a)

**Category** : Dimension/boundary-value

**Description** : Improper error handling in pareto distribution for y < y_min

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/6fa3414416103bee84c0e2a295807c64404ec12a)


### ProbFuzz Stan 54
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/70dda7cb97fc1d0ff937c8dde392621e4cd8141b)

**Category** : Dimension/boundary-value

**Description** : Improper error handling in categorical distribution

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/70dda7cb97fc1d0ff937c8dde392621e4cd8141b)




### ProbFuzz Stan 55
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/2d3a7926b970c8d775f0eaa3729df7bd8186f229)

**Category** : Dimension/boundary-value

**Description** : zero count(s) are not allowed in multinomial outcomes

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/2d3a7926b970c8d775f0eaa3729df7bd8186f229)



### ProbFuzz Stan 56
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/b75befa23e0a0c66192ba355955c3f2ad47b3ad6)

**Category** : Dimension/boundary-value

**Description** : Improper error handling in gamma distribution

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/b75befa23e0a0c66192ba355955c3f2ad47b3ad6)




### ProbFuzz Stan 57
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1205)

**Category** : Dimension/boundary-value

**Description** : check_multiplicable incorrectly allows Mx0 or 0xN matrices

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/5224850a9c0a6b78828ec1d05ff9783c21d47268)



### ProbFuzz Stan 58
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1544)

**Category** : Dimension/boundary-value

**Description** : No checks for failures in density or gradient calculations for ADVI

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/8e0fd35ba655f4d1a50b24340900e3f3e5014a78)



### ProbFuzz Stan 59
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1151)

**Category** : Language/Translation

**Description** : Functions in variable declaration constraints don't compile

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/dc61f6fb4508b3b6e10a7bc6e5d8966b248a3330)



### ProbFuzz Stan 60
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1131)

**Category** : Language/Translation

**Description** : integrate_ode causes parser error

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/9e90fff5e01b9f9a0655a5d0ed2dca9725e04752)



### ProbFuzz Stan 61
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1244)

**Category** : Language/Translation

**Description** : Parser error message is not informative

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/df5763064ea8aa0f7f173d2ab3ce5f3107218410)



### ProbFuzz Stan 62
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/1355899edfdee1ea522c921d904f9d3d405af012)

**Category** : Language/Translation

**Description** : Bug in command line parsing

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/1355899edfdee1ea522c921d904f9d3d405af012)


### ProbFuzz Stan 63
 
**Type** : [Commit](https://github.com/stan-dev/stan/commit/5f32769cebe7fb371cdb3a0c2e247fe87c95037c)

**Category** : Language/Translation

**Description** : Reversed sign in truncated distribution code generation

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/5f32769cebe7fb371cdb3a0c2e247fe87c95037c)


### ProbFuzz Stan 64
 
**Type** : [Issue](https://github.com/stan-dev/stan/issues/1713)

**Category** : Language/Translation

**Description** : unit_vector is allowed in parser but can't complie

**Fix version** : [Commit](https://github.com/stan-dev/stan/commit/bdddb045478754959a6f0f2d932776db4b80818a)


