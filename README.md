pkg-cryptsetup-debian
=====================

This is a clone of Debian's SVN repository for cryptsetup package (http://anonscm.debian.org/viewvc/pkg-cryptsetup/cryptsetup/trunk/).

Init script is patched - password is asked once and multiple LUKS volumes are
decrypted (unless first failed luksOpen action).

Read my blogpost for quick shell one-liner:
http://blog.hostname.sk/2014/05/12/make-cryptsetup-ask-the-same-password-only-once-at-boot/

