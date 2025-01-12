# ath11k-firmware

Firmware files for ath11k, a mac80211 driver for Qualcomm Technologies
802.11ax devices

To install or update your firmware images:

```
wget https://github.com/qca/qca-swiss-army-knife/raw/master/tools/scripts/ath11k/ath11k-fw-repo
chmod 755 ath11k-fw-repo
./ath11k-fw-repo --install /lib/firmware
```

Or, if you copy `ath11k-fw-repo` in your $PATH, run `make install`.

For more info check the wiki page:

https://wireless.wiki.kernel.org/en/users/drivers/ath11k

Please send bug reports to bugzilla.kernel.org:

https://wireless.wiki.kernel.org/en/users/drivers/ath11k/bugreport

Questions, comments and feature requests to the ath11k mailing list:

https://wireless.wiki.kernel.org/en/users/drivers/ath11k/mailinglist

The list archive:

https://lore.kernel.org/ath11k/
