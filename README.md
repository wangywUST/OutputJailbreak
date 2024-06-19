# Output Prefix Attacks

This is the repository for our paper [Frustratingly Easy Jailbreak of Large Language Models via Output Prefix Attacks](https://www.researchsquare.com/article/rs-4385503/latest).

We propose Opra and OpraTea 🆘, two novel, effective, and extremely simple jailbreak methods that can attack all large language models (LLMs) without expensive optimization or parameter search. 

Opra enforces the output prefix of LLMs to follow a "fuse", a probed template that expresses positive attitudes towards addressing the input question, even when the user has malicious intent. OpraTea hides the malicious target within the input prompt to bypass the "content filter" designed to detect and block malicious inputs. Both methods are simple yet threaten the security of LLMs because (1) they do not require any expensive optimization or parameter search; (2) the setting up and execution of our methods only requires a single LLM inference; and (3) they can operate on any black-box LLMs.

<img src="fig/fig_2.jpg" width="400">

Please see [our paper](https://www.researchsquare.com/article/rs-4385503/latest) for more details.

## Opra and OpraTea
<img src="fig/fig_1.png" width="400">

A python notebook for running OpraTea on `gpt-3.5-turbo-0613` is here: [`opratea_gpt.ipynb`](https://github.com/wangywUST/OutputJailbreak/blob/main/opratea_gpt.ipynb).

## Bugs or Questions?
If you have any questions related to the repo or the paper, or you encounter any problems when using the datasets/code, feel free to email Yiwei Wang `(wangyw.evan@gmail.com)` or open an issue!