# termsave

Simple save/loader for environment variables.

Add the following to bash_aliases and source it:
    alias termsave=". /path/to/git/project/termsave/termsave"

To save a 'session':

    termsave -s test

To load a session:

    termsave -l test


Note:
* termsave automatically saves environment variables to ~/.termsaverc/'test'