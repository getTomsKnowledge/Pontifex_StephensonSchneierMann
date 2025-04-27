# Pontifex_StephensonSchneierMann
 The Pontifex Perl script analyzed by Alistair Mann as seen on p. 594 (paperback) of Cryptonomicon by Neal Stephenson derived from Bruce Schneier's Solitaire algorithm.

4/27/2025: Script shamelessly lifted from @Csi18nAlistairMann and reproduced here.  Recommend using the .ipynb for sources, background info.  Script is obfuscated Perl which makes it... challenging to read at face value.  Enjoy!

##To use the script, run a Perl shell with:
```
$echo "PLAINTEXT" | ./pontifex.pl <key> # encrypt plaintext, key optional
$echo "CIPHERTEXT" | ./pontifex.pl -d <key> # decrypt ciphertext, key required if encrypted w/ key
```
