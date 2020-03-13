### 3.0 (2020-03-14)

* Update the krunner image for `centos7.6` to Python 3.8.2 along with krunner dependencies.
* Deprecate the krunner image for `centos6.10`.
  - CentOS 6 is released in 2011 (9 years ago) and Python 3.7 and higher does *not* support building
    the SSL module as-is with the CentOS 6's default OpenSSL package.

### 2.1 (2019-10-01)

* Add the krunner image for `centos6.10` with Python 3.6.8.

### 2.0 (2019-09-22)

* Add `ttyd` as an intrinsic service binary.

### 1.0 (2019-07-25)

* Initial release for `centos7.6` with Python 3.6.8.
