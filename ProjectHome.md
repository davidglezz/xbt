High-performance BitTorrent Tracker

# Installing under Linux #

Use the following commands to install the dependencies on Debian. The g++ version should be at least 4.7.

```
apt-get install cmake g++ libboost-dev libmysqlclient-dev make subversion zlib1g-dev
```

Use the following commands to install some of the dependencies on CentOS, Fedora Core and Red Hat. The g++ version should be at least 4.7.

```
yum install boost-devel cmake gcc-c++ mysql-devel subversion
```

Enter the following commands in a terminal. Be patient while g++ is running, it'll take a few minutes.

```
svn co http://xbt.googlecode.com/svn/trunk/xbt/misc xbt/misc
svn co http://xbt.googlecode.com/svn/trunk/xbt/Tracker xbt/Tracker
cd xbt/Tracker
./make.sh
cp xbt_tracker.conf.default xbt_tracker.conf
```