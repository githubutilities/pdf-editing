# A Collection of Tools for Editing PDF in Terminal

## spliting PDF

This script is from [UNIX Tips for Mac OS X---How do I split a PDF file into several from command-line?](http://www.cs.cmu.edu/~benhdj/Mac/unix.html#splitPDF). It utility utilize Apple CoreGraphics python module, please use `/usr/bin/python` instead of `/usr/local/bin/python` if you are using `homebrew` or you will get a `No module named CoreGraphics` error. For more info about `CoreGraphics`, please refer [here](https://pythonhosted.org/pyobjc/notes/quartz-vs-coregraphics.html).

Here is the usage:

```sh
/usr/bin/python splitPDF.py <the-number-of-page-you-want-to-extract>
```