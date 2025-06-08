**Download Android source with local_manifests**

Refer to http://source.android.com/source/downloading.html

```shell
$ repo init -u git://github.com/LineageOS/android.git -b lineage-17.1
$ git clone https://github.com/realme-trinket-organization/local_manifests.git .repo/local_manifests -b lineage-17.1
$ repo sync
```