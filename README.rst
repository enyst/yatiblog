Hacking Yatiblog.

The following is yatiblog upstream description.

-------------------------------------------------------------------------

Yatiblog is the blog engine that runs `Tav's blog <http://tav.espians.com>`,
also used to create documentation for projects like `Ampify <http://ampify.it>`.
It generates static HTML files from source ``.txt`` files from:

* ``yatiblog.conf``
* Any triple-dashed YAML metadata header within the text files.

Layout templates can be specified in the `Genshi markup language
<http://genshi.edgewall.org/>`_ and the templates are looked for in the
``_layouts`` directory.

**Example**

For an example of yatiblog used to generate a blog, see:

* Source: https://github.com/tav/blog
* Output: http://tav.espians.com

For an example of yatiblog used to generate prettified source code
documentation, see:

* Source: https://github.com/tav/ampify/tree/master/doc
* Output: http://ampify.it/code.html

**Usage**

::

   Usage: yatiblog [options] [path/to/source/directory]

   Options:
     -h, --help           show this help message and exit
     -d DATA_FILE         Set the path for a data file (default: .articlestore)
     -o OUTPUT_DIRECTORY  Set the output directory for files (default: website)
     --clean              Flag to remove all generated output files
     --force              Flag to force regeneration of all files
     --quiet              Flag to suppress output

**Contribute**

Ideas for further development and pull requests are welcome, thanks!

**License**

The initial yatiblog code has been released into the `Public Domain
<https://github.com/tav/yatiblog/raw/master/UNLICENSE>`_. Do with it as you
please.

tav <tav@espians.com>
