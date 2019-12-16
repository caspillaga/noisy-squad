# noisy-squad
A noisy version of the SQuAD dataset

Distributed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) license

This dataset was built by adding noise to the SQuAD 1.1 dataset ("SQuAD: 100,000+ Questions for Machine Comprehension of Text" by Pranav Rajpurkar, Jian Zhang, Konstantin Lopyrev and Percy Liang)

The dataset contains 5 types of noise, inspired on previous work by [Belinkov and Bisk (2018)](https://arxiv.org/abs/1711.02173):

* **Natural Noise**: Words are replaced by real typing errors of people. To automate this, a collection of word corrections performed by people in web platforms that keep track of edits history was used.
* **Swap Noise**: For each word in the text, one random pair of consecutive characters is swapped (e.g. *expression &#8594; exrpession*).
* **Middle Random Noise**: For each word in the text, all characters are shuffled, except for the first and last characters. (e.g. *expression &#8594; esroxiespn*).
* **Fully Random Noise**: For each word in the text, all characters are shuffled (e.g. *expression &#8594; rsnixpoees*)
* **Keyboard Typo Noise**: For each word in the text, one character is replaced by an adjacent character in traditional English  keyboards (e.g. *expression &#8594; exprwssion*).


