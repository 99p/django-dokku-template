# hi there!

this is my dokku 1st app!!

## usage:
  remote:
    dokku apps:create <appname>
    dokku postgres:create <dbname>
    dokku postgres:link <dbname> <appname>
    dokku config:set --no-restart <appname> SECRET_KEY=<secret_key>
    dokku config:set --no-restart <appname> DOKKU_LETSENCRYPT_EMAIL=<email>
    dokku letsenctypt <appname>
  local:
    git remote add dokku dokku@<hostname>:<appname>
    git push dokku master
