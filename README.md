Trying to get ODBC working with Vectorworks

Starting out:

    # installing postgres, odbc driver into this folder
    $ script/bootstrap

    # start the postgres server listening on port 5555
    $ script server

Vectorworks 2011 looks for iODBC in /usr/bin/iodbc-config

The stock Mac OS X install of iODBC looks under ~/Library/ODBC/obdc.ini
for user datasource configs

For 2011, all has to be compiled as 32-bit (i386) to work with the
system-supplied version of iODBC
