# raw data catalog (full annotation)

The raw data catalog GitHub is [here](https://github.com/EPFL-TOP/UPOATES_catalog). It runs on a virtual machine provided by SV-IT (sv-upoates.epfl.ch). Ask SV-IT to add you as user on that machine and login with ssh.
The machine runs a Maria DB database that hosts the raw data catalog. Phillippe Borel from SV-IT is the go-to person for this in case the DB fails or needs updates. The raw data catalog is installed in `/home/helsens/Software/UPOATES_catalog`, to run it in case it crashed or needs update (as it is often the case with Django) I do something like `./run.sh > out.out &`. Then the raw data catalog is available from the EPFL VPN at [this address](http://sv-upoates.epfl.ch:8000/rawdata_catalog/)

# quick annotation spread sheet

https://docs.google.com/spreadsheets/d/1Ln7mLvwA_yjecEsvndDsx8himvEw8ijISAGyyLYLbjc/edit?gid=1309253770#gid=1309253770


# VAST DS
dataset in `Y:\raw_data\microscopy\vast`
copy in raid 5 `D:\vast` for speed


# HIVES
Ask SV IT to receive notifications from the HIVEs
http://upoatespc6.epfl.ch/HIVE-3026
http://upoatespc5.epfl.ch/HIVE-3010

# Pontus, Tethys

Pontus and Tethys are the two linux machines we have close to the fridges. Pontus is mostly used by Cristina for single cell computing while we use now Tethys for remote GPU calculation using server kit.
To connect to Pontus, `ssh <USERNAME>@upoates-pontus.epfl.ch` <USERNAME> are set locally on the machine, we did not add that machine on the EPFL domain while it's needed by Cristina. But this could be done once she left and do not need the machine anymore.
To connect to Tethys, `ssh <USERNAME>@upoates-tethys.epfl.ch` <USERNAME> is the gaspar user name. 

# live tracking

Make sure server kit is still running on the machine, if it's not the following steps have to be done.


# Jetraw

temp files stored in
`D:\Clement\Temp`
this can be changed in the interface

on the NAS
Y:\common\JetRawCompressedFiles
