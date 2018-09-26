# Small scripts
Short utilities that I made and use often 

## javar
Use `javar filename` (without the .java extension) to compile and run (with lolcat output) a java program.

## print
Use `print filename` to print a text document with a printer. Add your printer's address in the script, either IP or hostname. Most printers have 80 char width and 60 char height. Most printers require CRLF line endings, so `print` requires gsed to convert LF to CRLF. If your printer doesn't work with CRLF (highly unlikely), remove the middle segment of the pipeline. If you don't have and/or don't want gsed, remove the middle segment of the pipeline and use `print` on files that already have CRLF line endings.
