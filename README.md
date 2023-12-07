Redmine Holidays Plugin
=======================

This is a redmine plugin that displays holiday in the calendar.
![Calendar](https://www.diigo.com/item/p/qqbrsoozbsqdrrorezbcpraodr)

Prerequisites
-------------

* Redmine 5.0


Installations
-------------

1. Clone into the plugins directory

        $ cd REDMINE_ROOT/plugins
        $ git clone https://github.com/tnaka176/redmine_holidays_plugin.git

2. Install gems

        $ cd REDMINE_ROOT
        $ bundle install

3. Run Rake task

        $ bundle exec rake redmine:plugins:migrate RAILS_ENV=production

4. Restart Redmine


Settings
------------

You can change region on plugin configuration page.

