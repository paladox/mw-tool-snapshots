ts-krinkle-mwSnapshots
======================

## Install:
* Create cache directory (chmod 755)
* Create local.php (must )
* Run updateSnaphots.php
* Symlink ./cache/snapshots to ./public_html/snapshots
* Schedule updateSnaphots.php to run bi-hourly<br>
   `0 * * * * php $HOME/externals/ts-krinkle-mwSnapshots/scripts/updateSnaphots.php > $HOME/externals/ts-krinkle-mwSnapshots/scripts/updateSnaphots.log 2>&1`
* Symlink ./public_html to ~/public_html/mwSnapshots
