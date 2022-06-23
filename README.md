# color-discrimination-task_different-training

## About

A Javascript-based implementation of a 2AFC color discrimination task.

To run, download the repository and open **index.html** in a web browser.

This codebase is built off the [original repository](https://github.com/nikolasmcneal/color-discrimination-task), with two significant modifications:

1. The value-based training block still returns the values of the two objects, but the fixed-reward training block returns a fixed score for the correct response and 0 for the incorrect response.
2. The original experiment consists of identical training blocks for both the value-based and fixed-reward conditions, followed by unique practice trials. Since the training blocks in this experiment are unique, the practice trials are removed and instructions are changed. 

![blocks-rainbow-newest](/img/misc/image4.png)
![blocks-rainbow-newest2](/img/misc/image5.png)
