# Words _vs_ phrases

Huang–Shi §8.5.1 gives up trying to distinguish between compounds and NPs; Chang §5.2.1.2 meekly accepts Lü's arbitrary rule. The following analysis implements the [defition](#defining-word) above on Chang's examples:

||人造|絲|
|:-:|:-:|:-:|
|Rule 1||free morph|
||adjective|noun|
|NP|complement|head|

||人造|纖維|
|:-:|:-:|:-:|
|Rule 1||free [morph](https://t18d.github.io/HuangSupplement/grammar/#two-character-morphs) (Japanese, 1897)|
||adjective|noun|
|NP|complement|head|

||豆|製品|
|:-:|:-:|:-:|
|Rule 3|word|bound [morph](https://t18d.github.io/HuangSupplement/grammar/#two-character-morphs) (Japanese, 1880)|
||noun|nominal bound root|
|noun|dependent|head|

||生物|製品|
|:-:|:-:|:-:|
|Rule 3|word|bound [morph](https://t18d.github.io/HuangSupplement/grammar/#two-character-morphs) (Japanese, 1880)|
||noun|nominal bound root|
|noun|dependent|head|

||耐火|磚|
|:-:|:-:|:-:|
|Rule 1||free morph|
||adjective|noun|
|NP|complement|head|

||耐火|材料|
|:-:|:-:|:-:|
|||word (s.xi)|
||adjective|noun|
|NP|complement|head|

||自由|泳|
|:-:|:-:|:-:|
|Rule 3|word|bound morph|
||adjective|nominal bound root|
|noun|dependent|head|

||自由|體操|
|:-:|:-:|:-:|
|Rule 1||free [morph](https://t18d.github.io/HuangSupplement/grammar/#two-character-morphs) (Japanese, 1887)|
||adjective|noun|
|NP|complement|head|

Implementation for examples in Huang–Shi §3.4.2:

||光|線|
|:-:|:-:|:-:|
|Rule 1||free morph|
|fossilised NP (1761)|complement|head|
|Rule 4|||

||水|土|
|:-:|:-:|:-:|
|fossilised (Chou)|morph|morph|
|Rule 2|||
