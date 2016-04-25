#kate-snippets

Some PHP/HTML development [snippets](http://docs.kde.org/stable/en/applications/kate/kate-application-plugin-snippets.html) to use with [Kate editor](http://kate-editor.org).

To use them simply copy the XML files to `~/.kde/share/apps/ktexteditor_snippets/data/`

Or use the provided `make-symlink.sh` script to link the snippets from your git working copy.
- link one snippet:  
  `./make-symlink.sh snippet.xml`
- link all snippets:  
  `ls | grep .xml | xargs -n 1 ./make-symlink.sh`
