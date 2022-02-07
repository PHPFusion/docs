# Upgrading

Upgrading your system from previous PHPFusion versions.

---

Before you start doing something, turn on maintenance mode (in Security Settings) and make a full copy of your site and your database.

If your site is version 9.00.00 and a new 9.10.00 is released, you can download the latest PHPFusion 9.10.00 version and upgrade directly to this version.

You can download all versions from our [Archive](https://github.com/PHPFusion/Archive).

## General upgrade procedure

**The backup procedure**

You can back up database using our Backup tool in System Admin section, or you can phpMyAdmin or any other tool for managing databases. 

Once you have the database backed up, open the FTP program and log in to your server. Select all the files and folders and transfer them to your local computer.

**The upgrade process**

1 Upload and replace all files and folders with new pack.

2 Download the latest locale pack for your site's locale. If you only use English, skip this step.

3 Start `https://yourdomain.com/install.php` and follow the instructions, click, click and click until done.

4 Remove install.php from your root.

Your site should now be running on the latest PHPFusion version, you can verify this by entering your Administration > System Admin > Server Info and see the version number there.

## Upgrading from 7 or 8 to PHPFusion 9

This upgrade procedure is written to work from PHPFusion 7.02.07 and PHPFusion 8 to PHPFusion 9.xx.xx

If you do not have your 7 installation upgraded to 7.02.07 you must first upgrade to 7.02.07. And we recommend removing old infusions and panels written for v7, as they can cause a lot of php errors later after the upgrade.

Because v9 has a better upgrade mechanism, you can upgrade directly to the latest v9.

To upgrade your site start `https://yourdomain.com/install.php` and follow the instructions, click, click and click until done.

---

For questions, please visit our [Upgrade Support Forum](https://phpfusion.com/infusions/forum/index.php?viewforum&forum_id=154).
