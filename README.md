# List of WYSIWYG editors

My requirements:

* open source (not GPL or AGPL)
* easy to use is more important than many fancy features
* Optional feature: Start a unordered list by just entering `* ` (without using buttons of the editor). This would be great.
* No need to support old browsers. IE11 is dead.


Good:

* https://github.com/outline/rich-markdown-editor BSD License. Used by commercial company used-by=220. Supports `* ` and `1. `. menuless.
* https://github.com/benweet/stackedit Markdown Supports `* ` (lists without using the menu. Even with sub-lists)
* https://ui.toast.com/tui-editor Markdown. Supports `* `.

Comparing above:

https://www.githubcompare.com/xdan/jodit+codex-team/editor.js+neilj/squire+quilljs/quill

Something is missing:
* https://quilljs.com/ no tables [dev staled](https://github.com/quilljs/quill/graphs/contributors) used-by=50k history-support.
* https://github.com/Alex-D/Trumbowyg based on jquery.
* https://github.com/codex-team/editor.js (Apache License) Nice TAB feature. With tables. Nice inline menu. used-by=1.6k output=json. No "* ...." support
* https://xdsoft.net/jodit/ (supports tables), MIT License, looks good. But menu on top (inline menu like editor.js is more clean) used-by=440 not "* ...." support
* https://github.com/neilj/Squire MIT License, Supports arbitrary HTML (to forward HTML mail in Fastmail). Strong company support. used-by=1k output=html [not "* ..." support](https://github.com/neilj/Squire/issues/408)
* https://github.com/sparksuite/simplemde-markdown-editor Looks fine, but no updates since 2016
* https://github.com/ianstormtaylor/slate (can show, but not edit tables. See [tables Example](https://www.slatejs.org/examples/tables)) [Why We Moved From Quill to Slate](https://medium.com/the-lead/why-we-moved-from-quill-to-slate-94f42aa54fec) used-by=55k. Does not feel fluent for me.
* https://github.com/basecamp/trix (MIT License, from Basecamp, the creators of Ruby on Rails, no tables). No more much development: [graph](https://github.com/basecamp/trix/graphs/contributors) used-by=5k output=html
* https://github.com/tinymce/tinymce (oldest, LGPL, 21k commits. Started 2006. too old)
* https://ckeditor.com/ckeditor-4/ ([License](https://github.com/ckeditor/ckeditor4/blob/master/LICENSE.md) LGPL, compatible with closed source code. But future is unclear)
* https://ckeditor.com/ckeditor-5/ ([License](https://github.com/ckeditor/ckeditor5/blob/master/LICENSE.md) GPL, not compatible with closed source code)
* https://github.com/facebook/draft-js (from Facebook, but no tables support)
* https://www.draftail.org/ (used by [wagtail](https://wagtail.io/)). No support for tables. Based on Draft.js
* https://wordpress.org/plugins/gutenberg/ Editor of WordPress. But AFAIK can't be used outside Wordpress
* https://summernote.org/ (supports tables, but only limited. Started 2013)
* http://jejacks0n.github.io/mercury/documentation/ MIT License. No updates since 2014
* https://github.com/yabwe/medium-editor/graphs/contributors no progress in the last year
* https://github.com/nextcloud/text (AGPL License)
* https://github.com/ueberdosis/tiptap/ v2 is coming soon: https://github.com/ueberdosis/tiptap/issues/547

Commercial:

* https://handsontable.com/examples
* https://froala.com/wysiwyg-editor/
* https://imperavi.com/redactor/

Related List: 

* https://en.wikipedia.org/wiki/Category:JavaScript-based_HTML_editors
* https://djangopackages.org/grids/g/wysiwyg/
* https://github.com/topics/wysiwyg-editor

Related Questions:

* https://www.reddit.com/r/reactjs/comments/eqdxpu/best_react_wysiwyg_editor_in_2020_quilljs_vs/

# Star trend

![image](https://user-images.githubusercontent.com/414336/115287795-f7b19c80-a150-11eb-950f-7589c0413546.png)


# More

[Thomas WOL: Working out Loud](https://github.com/guettli/wol)
