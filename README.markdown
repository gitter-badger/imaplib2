Threaded Python IMAP4 client
============================

[![Join the chat at https://gitter.im/bcoe/imaplib2](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/bcoe/imaplib2?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

About
-----

Based on RFC 3501 and original imaplib module.

This is a version of imaplib that uses threads to allow full use of the
IMAP4 concurrency features, and to de-couple a user of imaplib from i/o
lags, except where explicitly allowed.

About this Fork
---------------

This is a fork of Piers Lauder's imaplib2 library hosted here: http://sourceforge.net/projects/imaplib2/

I created this fork because I wanted to submit the library to PyPi. An attempt will be made to keep it up-to-date with the original.