Trying to get ODBC working with Vectorworks

Starting out:

    # get this repo
    $ git clone git@github.com:rgm/vectorworks-postgres.git

    # installing postgres, odbc driver into this folder
    $ script/bootstrap

    # start the postgres server listening on port 5555
    $ script server

Vectorworks 2011 looks for iODBC in /usr/lib/libiodbc.dylib, and
I haven't yet figured out how to make it look for ours.

