MY_Migration
============================

CodeIgniter's development branch has configurable migration tables on the way. Until then, I really needed them, so I extended the migration library.

Setup
----------------------------

1. Drop ```MY_Migration.php``` in application/libraries
2. Replace your ```config/migration.php``` with the one from here
3. Edit ```config/migration.php``` with your migration setup, including the new ```migration_table``` config item.

[Migrations library documentation](http://codeigniter.com/user_guide/libraries/migration.html)