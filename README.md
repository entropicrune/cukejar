# cukejar

This project creates a Java jar containing ruby Cucumber-related code.

To build this jar:

* Install rvm & JRuby (see https://rvm.io/rvm/install)
* Use Jruby:   "rvm jruby-9.1.7.0"
* Create a new gemset:   "rvm gemset create myCukeJar"
* Use the gemset:   "rvm gemset use myCukeJar"
* cd into the root folder of this repository
* Run the install_gems.sh script:    "./install_gems.sh"
* Execute "warble gemjar jar"
* You should find cukejar.jar in the current directory

If you modify the versions specified in "install_gems.sh", you will also need
to modify mri.gemspec and possibly the contents of bin.
