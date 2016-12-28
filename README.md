[![Build Status](https://travis-ci.org/Spedge/hangar-index.svg?branch=master)](https://travis-ci.org/Spedge/hangar-index) [![Documentation Status](https://readthedocs.org/projects/hangar/badge/?version=latest)](http://hangar.readthedocs.io/en/latest/?badge=latest) 
[![](https://images.microbadger.com/badges/image/spedge/hangar-index.svg)](https://microbadger.com/images/spedge/hangar-index "* hangar-index Get your own image badge on microbadger.com")

hangar-index
============

hangar-index is a Docker image containing an Zookeeper instance that will self-discover it's cluster using S3.

It's used primarily by [hangar](https://github.com/Spedge/hangar) to power it's distributed index.

Originally built from [mbabineau/docker-zk-exhibitor](https://github.com/mbabineau/docker-zk-exhibitor)
