nmodl.vim
=======

Syntax file for `nmodl <https://www.neuron.yale.edu/neuron/static/docs/help/neuron/nmodl/nmodl.html>`__. It's the language used in the `NEURON simulator <http://neuron.yale.edu/neuron/>`__ to add new components.

Taken from https://github.com/achilleas-k/vimconfig/blob/master/syntax/nmodl.vim. Feel free to update/imporve it. Pull requests welcome.


Installation
------------

Place in :code:`~/.vim/syntax` or use :code:`pathogen` and the rest - you know what to do :)

At the end of your :code:`vimrc` file, add:

.. code:: vim

    au BufRead,BufNewFile *.mod set filetype=nmodl

