# Bug Info #

### ProbFuzz Pyro 1 ###

**Type** : [Issue](https://github.com/uber/pyro/issues/436)

**Category** : Numerical

**Description** : Gradient evaluates to nan when using Bernoulli

**Fix version** : [Commit](https://github.com/uber/pyro/commit/7b6cf5860d9600e229dd5b5f47a555164d894f7b)

### ProbFuzz Pyro 2 ###

**Type** : [Issue](https://github.com/uber/pyro/issues/574)

**Category** : Language/Translation

**Description** : TransformedDistribution's event_shape forwards to incorrect base distribution's method

**Fix version** : [Commit](https://github.com/uber/pyro/commit/a59b4360319f0b2913fe21c4326aa5793bb7cfe1)

### ProbFuzz Pyro 3 ###

**Type** : [Issue](https://github.com/uber/pyro/issues/420)

**Category** :  Language/Translation

**Description** : Compatibility with pytorch 0.3

**Fix version** : [Commit](https://github.com/uber/pyro/commit/3166c6b725e27ceabf482d1c9428f24f50e52492)

### ProbFuzz Pyro 4

**Type** : [Issue](https://github.com/uber/pyro/issues/377)

**Category** : Language/Translation

**Description** : enum_discrete segfaults on Pytorch 0.2.0 release

**Fix version** : [Commit](https://github.com/uber/pyro/commit/ece8ccc167695f81aa7ec1fed74a70c8fc15254b)

### ProbFuzz Pyro 5

**Type** : [Issue](https://github.com/uber/pyro/issues/70)

**Category** : Language/Translation

**Description** : Inconsistent tensor types

**Fix version** : [Commit](https://github.com/uber/pyro/commit/c5bb9b43093565aeb83f0025341e43778a646762)

### ProbFuzz Pyro 6
 
**Type** : [Issue](https://github.com/uber/pyro/issues/302)

**Category** : Accuracy/Inference

**Description** : Incorrect sampling behaviour in Cauchy distribution

**Fix version** : [Commit](https://github.com/uber/pyro/commit/0f1d27e81213d548d4ddcd65d19c15156dabf59a)

### ProbFuzz Pyro 7
 
**Type** : [Commit](https://github.com/uber/pyro/commit/4acf3ea6ce5cddd1991bab5d3481195a894384ee)

**Category** : Accuracy/Inference

**Description** : Incorrect acceptance ratio in metropolis hastings

**Fix version** : [Commit](https://github.com/uber/pyro/commit/4acf3ea6ce5cddd1991bab5d3481195a894384ee)

### ProbFuzz Pyro 8
 
**Type** : [Commit](https://github.com/uber/pyro/commit/9dc6cf754d2aba272c13059666064b423fd2e098)

**Category** : Accuracy/Inference

**Description** : Bug in klqp

**Fix version** : [Commit](https://github.com/uber/pyro/commit/9dc6cf754d2aba272c13059666064b423fd2e098)

### ProbFuzz Pyro 9
 
**Type** : [Issue](https://github.com/uber/pyro/issues/531)

**Category** : Accuracy/Inference

**Description** : Scale is double counted

**Fix version** : [Commit](https://github.com/uber/pyro/commit/b94f06a2257bf362208c28048544deb297aa5e24)

### ProbFuzz Pyro 10 
 
**Type** : [Issue](https://github.com/uber/pyro/issues/303)

**Category** : Dimension/boundary-value

**Description** : No checks for dimension mismatch

**Fix version** : [Commit](https://github.com/uber/pyro/commit/492c27a1c240c40b780bd7114eeabb63ae07d31d)

	
 
### ProbFuzz Pyro 11 
 
**Type** : [Issue](https://github.com/uber/pyro/issues/253)

**Category** : Dimension/boundary-value

**Description** : Incorrect batching in Categorical.sample

**Fix version** : [Commit](https://github.com/uber/pyro/commit/965d3ca4078c0932410f08e9204862403c30d1f7)

 
### ProbFuzz Pyro 12
 
**Type** : [Issue](https://github.com/uber/pyro/issues/161)

**Category** : Dimension/boundary-value

**Description** : Dirichlet distribution treats shape inconsistently

**Fix version** : [Commit](https://github.com/uber/pyro/commit/00b5688ecb1535f844ee4575ec590f2166dd8a62)

 
### ProbFuzz Pyro 13
 
**Type** : [Issue](https://github.com/uber/pyro/issues/451)

**Category** : Dimension/boundary-value

**Description** : Dealing with empty model and guide

**Fix version** : [Commit](https://github.com/uber/pyro/commit/3671b06e6d0aae661f18f6dde6e92d6fdc5825fd)

### ProbFuzz Pyro 14
 
**Type** : [Issue](https://github.com/uber/pyro/issues/417)

**Category** : Dimension/boundary-value

**Description** : Delta's batch_log_pdf not consistent with e.g. Bernoulli

**Fix version** : [Commit](https://github.com/uber/pyro/commit/492c27a1c240c40b780bd7114eeabb63ae07d31d)

### ProbFuzz Pyro 15
 
**Type** : [Issue](https://github.com/uber/pyro/issues/235)

**Category** : Misc

**Description** : key different

**Fix version** : [Commit](https://github.com/uber/pyro/commit/7d87b71e235ba51051fed5fbc61ace41412737eb)

### ProbFuzz Pyro 16
 
**Type** : [Issue](https://github.com/uber/pyro/issues/328)

**Category** : Misc

**Description** : Batch size should be given as a parameter of inference rather than via the model and/or guide

**Fix version** : [Commit](https://github.com/uber/pyro/commit/82278db06a5f914b2dccde8c2458c876298879ae)

### ProbFuzz Pyro 17
 
**Type** : [Commit](https://github.com/uber/pyro/commit/d133c48ddce86029705d1b430d87080d996afb00)

**Category** : Misc

**Description** : Bug in replaying nested irange

**Fix version** : [Commit](https://github.com/uber/pyro/commit/d133c48ddce86029705d1b430d87080d996afb00)

### ProbFuzz Pyro 18
 
**Type** : [Commit](https://github.com/uber/pyro/commit/97cbbcb5c142376e44d50f3754e33c800ae522c7)

**Category** : Misc

**Description** : batch_log_pdf shouldn't be used when enum_discrete=True but there are no discrete variables in the model

**Fix version** : [Commit](https://github.com/uber/pyro/commit/97cbbcb5c142376e44d50f3754e33c800ae522c7)

### ProbFuzz Pyro 19
 
**Type** : [Issue](https://github.com/uber/pyro/issue/262)

**Category** : Language/Translation (Not a bug)

**Description** : Wrapping bijectors in nn.ModuleList

**Fix version** : [Commit](https://github.com/uber/pyro/commit/cfb2ce39b47719a47dd6c34c8ecfe8db695cbcac)

