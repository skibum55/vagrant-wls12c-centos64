vagrant-wls12c-ubuntu64
=======================

Based on Detailed steps can be found here:

http://vbatik.wordpress.com/2013/10/11/weblogic-12-1-2-00-with-vagrant/

For Mac Users.  The procedure has been and run tested on Mac.


Important: JDK7 Changes of Note as of 10/15/2013

Oracle released a new version of the JDK 1.7u45. This has been reflected and tested in the site.pp file. If you have an older JDK you will need to modify site.pp only. The JDK7 Puppet module does not need to be modified.

site.pp is located here:

https://github.com/skibum55/vagrant-wls12c-ubuntu64/blob/master/puppet/manifests/site.pp

You will need to modify this for your particular jdk that you downloaded and the location of the downloaded jar files. 
