# Redmine Scrum plugin

## Main features

Take a look to https://redmine.ociotec.com/projects/redmine-plugin-scrum or
https://redmine.ociotec.com/projects/redmine-plugin-scrum/wiki for further
details.

## Access to plugin source code

This project is a copy of the initial plugin from 
https://www.patreon.com/ociotec 

You can  download the original version from:
https://redmine.ociotec.com/projects/redmine-plugin-scrum.

The main point of this copy is to fix the calendar issue and not to modify anything on the project

## Installation instructions


```sh
    cd <redmine-path>/plugins
    git clone https://github.com/de-poltorasky/redmine-scrum/redmine-scrum.git
    mv redmine-scrum scrum
    cd ..
    bundle exec rake redmine:plugins:migrate
````

Finally restart your Redmine installation.
