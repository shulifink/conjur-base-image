# phusion-ruby-fips
 `phusion-ruby-fips` combines a [base Phusion image](https://hub.docker.com/r/phusion/baseimage) 
 with ruby compiled against the FIPS 140-2 compliant [OpenSSL module](https://www.openssl.org/docs/fips.html).  
This image includes the following packages:

* OpenSSL version: `1.0.2u` build with  FIPS 140-2 compliant OpenSSL module version: `2.0.16`
* Ruby version: `2.5` compiled against the FIPS 140-2 compliant OpenSSL module
* Postgres client version: `12-12.2` compiled against the FIPS 140-2 compliant OpenSSL module
* Bundler version: `2.1.4`
 
Source code: https://github.com/cyberark/conjur-base-image