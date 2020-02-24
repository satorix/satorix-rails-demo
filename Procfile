# This Procfile defines the types of process that Flynn will run.
# For more information, please see the documentation at http://gitlab.iexposure.com/satorix/satorix

web: bundle exec passenger start -p $PORT --nginx-config-template config/passenger_standalone/nginx.conf.erb --log-file /dev/stdout
# worker: rake jobs:work
# clock: bundle exec clockwork config/clock.rb
