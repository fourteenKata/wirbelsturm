# 0.6.1 (unreleased)

IMPROVEMENTS

* WIRBELSTURM-2: `bootstrap` now supports the `--skip-ruby` parameter.  If set, `bootstrap` will skip the installation of
* Update puppet-storm to 1.0.5, which e.g. supports running the new
  [logviewer](http://storm.incubator.apache.org/2013/12/08/storm090-released.html) daemon.
  Ruby/rvm/bundler/gems. (thanks bzz)

BUG FIXES

* `deploy` now correctly writes its log files to the directory `provisioning-logs/` in the base Wirbelsturm directory,
  even when `deploy` is executed from within sub-directories of Wirbelsturm.


# 0.6.0 (March 17, 2014)

* Initial release
