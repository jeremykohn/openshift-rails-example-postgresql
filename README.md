# Sample Rails App on OpenShift (with PostgreSQL)#
Quickstart rails application for openshift based on
https://github.com/openshift/rails-example.

Do read the above.

## Manual Installation ##

1. Create an account at http://openshift.redhat.com/

1. Set up command line tools: `gem install rhc`

1. Create a rails application

    ```
    rhc app create railsapp ruby-1.9 postgresql-9.2 \
    --from-code https://github.com/BanzaiMan/openshift-rails-example-postgresql.git
    ```

1. That's it! Enjoy your new Rails application!

License
-------

This code is dedicated to the public domain to the maximum extent permitted by applicable law, pursuant to CC0 (http://creativecommons.org/publicdomain/zero/1.0/)
