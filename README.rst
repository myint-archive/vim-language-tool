============
LanguageTool
============

This plugin integrates the LanguageTool grammar checker into Vim.
Current version of LanguageTool can check grammar in many languages
See the list of supported languages: http://www.languagetool.org/languages/
or http://www.languagetool.org/ or more information about LanguageTool.

The script defines 2 commands:

- Use ``:LanguageToolCheck`` to check grammar in current buffer.
  This will check for grammar mistakes in text of current buffer
  and highlight the errors. It also opens a new scratch window with the
  list of grammar errors with further explanations for each error.
  Pressing <Enter> in scratch buffer will jump to that error. The
  location list for the buffer being checked is also populated.
  So you can use location commands such as :lopen to open the location
  list window, :lne to jump to the next error, etc.

- Use ``:LanguageToolClear`` to remove highlighting of grammar mistakes,
  close the scratch window containing the list of errors, clear and
  close the location list.

See screenshots of grammar checking in English and French at:

- http://dominique.pelle.free.fr/pic/LanguageToolVimPlugin_en.png
- http://dominique.pelle.free.fr/pic/LanguageToolVimPlugin_fr.png


Installation
============
::

    $ pip install git+https://github.com/myint/language-tool

Then copy the contents of ``plugin`` into ``~/.vim/plugin``.


License
=======

The VIM LICENSE applies to ``LanguageTool.vim`` plugin.
