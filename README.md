pkg-cryptsetup-debian
=====================

This is a clone of Debian's SVN repository for cryptsetup package (http://anonscm.debian.org/viewvc/pkg-cryptsetup/cryptsetup/trunk/).

Init script is patched - password is asked once and multiple LUKS volumes are
decrypted (unless first failed luksOpen action).


