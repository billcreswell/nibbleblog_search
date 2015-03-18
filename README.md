nibbleblog_search
=================

Nibbleblog Search

First working version of a search plugin for Nibbleblog

Should be installed in /plugins/search.

Note: Nibbleblog may require a languages subfolder "languages" with a file called en_US.bit.
Languages have not yet been implemented.

<?php

$_PLUGIN_CONFIG['LANG'] = array(
	'NAME'=>'Hello world',
	'DESCRIPTION'=>'Show hello world.'
);

?>

===================

Nibbleblog
Easy, fast and free CMS Blog. All you need is PHP to work.

http://www.nibbleblog.com

https://github.com/dignajar/nibbleblog

===
1.1 
-Added empty language file
-Fix for file opening dir error (thanks Schlumpfuk)
-Fix for not searching drafts (thanks Schlumpfuk)