# kmonitor-nlp

## klasszifikáció

Cikkekről eldönteni, hogy korrupciós témát dolgoznak-e fel.

### eredmények

| model                                                 | accuracy |
| ----------------------------------------------------- | -------- |
| huBERT címen                                          | 91.52%   |
| huBERT leaden                                         | 92.504%  |
| TF-IDF & Random forest szöveg törzsön                 | 87.986%  |
| BoW & Random forest címkéken                          | 84.021%  |
| Kombinált (huBERT címen + huBERT lead + TF-IDF + BoW) | 94.612%  |
| OpenAI GPT-3.5* few shot prompt lead-eken             | ~87%     |
| NYTK/PULI-GPT-3SX cím+lead+törzs @40k                 | 95.415%  |

\*text-davinci-003

## releváns helyszínek, személyek és intézmények kinyerése

TODO
