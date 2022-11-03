# hadoop-3-conf

This repository stores configuration files for Hadoop version 3.
The content must overwrite the default installation.

It is assumed in this repository that the Hadoop installation
directory is `/usr/local/hadoop-3.3.4` so if you decide to
install elsewhere you should update the files accordingly to
reflect your decision.

A minimalist approach was adopted in terms of configuration, as the objective is to use it with the Iceberg format and its APIs/Libraries. So there was, at first, no concern with adjustments in the YARN, for example.

In the `hadoop-3.3.4` directory we have the `xml` and `bash` scripts to overwrite in fresh installations of hadoop version 3.3.4

After overwriting the files in the `etc/hadoop` directory you should replace `/Volumes/dev/` in these files with the appropriate value in your installation. Also update the value of `JAVA_HOME` in `/usr/local/hadoop-3.3.4/etc/hadoop/hadoop-env.sh`
