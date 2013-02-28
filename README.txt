Webform Multiple (WFM)
======================
This extends the Drupal 7 Webform module, to allow components (including
fieldsets) to accept multiple values.


Development status
------------------
Currently components will render correctly and save data, provided that they
don't use a submit hook to flatten non-scalar values.

For this reason Date components will not work, if they are either multiple-value
themselves, or if they are children of multiple-value fieldsets. In these cases
the date information cannot be saved. A patch to the Date component is probably
the only way forward.

Multiple-value data is not displayed yet.

Much is subject to change.


Copyright
---------
Copyright 2012 UCLU (University College London Union)
25 Gordon St, London WC1H 0AY
http://uclu.org/


Author
-----
Patrick Dawkins (drupal.org username: pjcdawkins)
