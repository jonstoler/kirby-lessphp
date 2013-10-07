kirby-lessphp
=============

Lessphp for KirbyCMS.

This is a processor for LESS files. Note: not a preprocessor!  
Built using the lessphp library by Leaf Corcoran.  
This plugin will automatically process LESS-Files.

1. Copy the lessc.inc.php in the subfolder "lessphp" inside Kirby's plugin folder. 
2. Call the compiler with `<?php echo less('file.less') ?>`, much like you would use kirby's `css` function for css files. 

Original by bueroexit (http://bueroexit.github.io/kirby-lessphp)  
Forked by jonstoler (http://github.com/jonstoler)
