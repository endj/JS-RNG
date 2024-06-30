# Testing Javascript random sources

TLDR: XorShift fast

Average times in ms for 20_000 iterations;

| Math.random()      | crypto.getRandomValues   | MersenneTwister     | Xorshift           |
|--------------------|--------------------------|---------------------|--------------------|
| 0.6976608187395926 | 15.846198830361429       | 0.36198830413931643 | 0.0432748537815628 |