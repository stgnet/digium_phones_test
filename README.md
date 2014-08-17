digium_phones_test
==================

Configuration Build Test for digium_phones module

This is a very simple and basic test that checks
the generation of res_digium_phone*.conf files
to insure no features have been broken.

A carefully constructed set of mysql and file
configuration is loaded into the currently
running FrePBX installation (WARNING: this
overwrites any existing configuration!!!),
the configuration is rebuilt, and the output
files compared to the expected configuration.

To run the test, do:

    ./run-test

To update the saved mysql configuration
or sample files, use the save-mysql-config
or create-files-archive tools.

The configs directory contains a copy of
expected configuration in /etc/asterisk.
