# Space_alignment_longtail
Recent studies on Neural Collapse (NC) reveal that, under
class-balanced conditions, the class feature means and clas-
sifier weights spontaneously align into a simplex equiangu-
lar tight frame (ETF). In long-tailed regimes, however, se-
vere sample imbalance tends to prevent the emergence of
the NC phenomenon, resulting in poor generalization per-
formance. Current efforts predominantly seek to recover the
ETF geometry by imposing constraints on features or clas-
sifier weights, yet overlook a critical problem: There is a
pronounced misalignment between the feature and the clas-
sifier weight spaces. In this paper, we theoretically quan-
tify the harm of such misalignment through an optimal er-
ror exponent analysis. Built on this insight, we propose three
explicit alignment strategies that plug-and-play into exist-
ing long-tail methods without architectural change. Exten-
sive experiments on the CIFAR-10-LT, CIFAR-100-LT, and
ImageNet-LT datasets consistently boost examined baselines
and achieve the state-of-the-art performances.
