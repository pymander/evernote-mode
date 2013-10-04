evernote-mode
=============

Emacs interface for Evernote which originally started on
[Google Code][1].  Then it was [updated][2] for working with Ruby
1.9.3 and Emacs 24.1.  Which was then updated to [work with OAuth][3].
Then just a little bit of Emacs customization niceness was added.

configuration
-------------

You'll need to get a production developer token from [Evernote][4] and
in Emacs set the custom variable `evernote-developer-token`.  If
`evernote-mode` is loaded this can be done easily with `M-x
customize-group evernote`.

[1]: http://code.google.com/p/emacs-evernote-mode/ "Original source"

[2]: https://github.com/rubbish/evernote-mode "rubbish/evernote-mode"

[3]: https://github.com/pymander/evernote-mode "pymander/evernote-mode"

[4]: http://dev.evernote.com/doc/articles/authentication.php#devtoken "Evernote Authentication"





