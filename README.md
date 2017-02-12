# Convolutional neural networks for artistic style transfer

This repository contains (TensorFlow and Keras) code that goes along
with a [related blog post][blog-post]. Together, they act as a
systematic look at convolutional neural networks from theory to
practice, using artistic style transfer as a motivating example. The
blog post provides context and covers the underlying theory, while the
working through the Jupyter notebooks in this repository offers a more
hands-on learning experience.

If you have any questions about any of this stuff, feel free to [open
an issue][support-issue] or tweet at me: [@copingbear][twitter].

## Setup

1. Install Python (2.7), pip and virtualenv on your machine. The
instructions to do this depend on your operating system (Linux, macOS,
Windows), but there are many tutorials on the internet that should
help you get started.

2. Once you have the above setup, it is quite easy to setup the
requirements for the notebooks in this repository. First you clone a
copy of this repository:

````
git clone https://github.com/hnarayanan/artistic-style-transfer.git
````

3. Navigate to this folder in your shell and then install the
requirements needed for the Jupyter notebooks.

````
cd artistic-style-transfer
virtualenv --distribute --no-site-packages venv
source venv/bin/activate
pip install -r requirements.txt
````

4. That's it! You can now start Jupyter and browse, open, run and
modify the notebooks.

````
jupyter notebook
````

## Contents

TODO

[blog-post]: https://harishnarayanan.org/writing/artistic-style-transfer/
[support-issue]: https://github.com/hnarayanan/artistic-style-transfer/issues
[twitter]: https://twitter.com/copingbear
