---
term: YPC
---
"Yggdrasil Production Center" - the sampler/softcut system for Yggdrasil. [History]("https://en.wikipedia.org/wiki/Akai_MPC"). The YPC uses an intelligent "first in, first out, round robin" algorithm to play samples. Softcut (the internal sampler engine in norns) has six voices, so if Yggdrasil is instructed to play 7 samples at once, only the first 6 will fire. Once the first sample is complete, another sample will be available. The YPC can support any number of banks, each with any number of samples. YPC can intelligently repitch samples.