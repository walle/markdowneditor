# Markdowneditor

Simple website to write down ideas. Like a text document in a texteditor but with live preview for markdown.
This is a development of the idea https://coderwall.com/p/lhsrcq but with preview and localStorage.
Only tested in Chrome so far.

Three versions exists:

* without localStorage - nice to use as a bookmarklet with data:text/html
* with localStorage - to save on your computer and able to save to localStorage
* hosted - hosted at http://markdowneditor.se good to save as a bookmark if you don't want to bother with handling local files

## Without localStorage

Easy to embed as a bookmark in your browser. Just add a new bookmark and save it as the url: data:text/html, {contents in index.html}.
This version is only usable as a scribbling tool and not able to save to loal storage because of security rules in the browser.

## With localStorage

Just save the html file localStorage/index.html somewere on your computer. On OS X you can open it using finder to get a editor to preview markdown.
This version is able to save to localStorage. Just give the file a name at the top and press Save. To load the file you enter the name of a previously saved file and press Load.

## Hosted

I host the app at http://markdowneditor.se. It's basicly the same version as localStorage/index.html but on the web. All files is still saved in your localStorage.
Usable as a bookmark in your browser.