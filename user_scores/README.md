# Hybrid K2/K3/K5 per-metric minimum

`hybrid_k2_k3_k5.global.scores.json` contains the lowest recorded error among
the separately evaluated Hybrid K2, K3 and K5 models for each matching
reference, metric, variable, depth and lead day. It is a per-metric composite
selected after evaluation, not the score of a single trained model or a
deployable ensemble. It is not an official OceanBench submission.

The source tables were evaluated with OceanBench 0.4.0 and rounded to six
decimal places. Missing metrics have not been filled. This file is reconstructed
from existing tables, not a native `oceanbench evaluate` JSON export.
