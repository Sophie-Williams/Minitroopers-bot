Automatic minitroopers script
=============================

Automatic script for running the minitroopers game (see [minitroopers.com](http://hjulle.minitroopers.com "My page on minitroopers")).
Runs assults, raids and missions automatically.
Detects which troopers can be upgraded and launches browser for them.

How to run:
-----------

1. Costumize config:

     *  `minitroopers.txt`   -- Contains list of all the troopers you want to add
     *  `script.sh`          -- Contains hard-coded password.  Contains name of the opponent
                                you want your to fight (preferably an easy one)
     *  `run_all.sh`        -- Runs the main list of troopers and uses special config for some troopers

2. Add the `run_all.sh` to a daily cronjob to do the fights.

3. Run `upgrade.sh` to automatically launch firefox for troopers which can be upgraded
