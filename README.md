Common Lisp REST Server
=======================

*rest-server* is a library for writing REST Web APIs in Common Lisp

[![Build Status](https://travis-ci.org/mmontone/cl-rest-server.svg?branch=master)](https://travis-ci.org/mmontone/cl-rest-server)

Purpose of the library:

* Method matching
  - Based on HTTP method (GET, PUT, POST, DELETE)
  - Based on Accept request header
  - URL parsing (argument types)
  - Matching based on "extension": i.e. /users.json or /users.xml, etc
  - Method combinations?

* Serialization
  - Different serialization types (JSON, XML, S-expressions)

* Materialization (unserialization)
  - Types

* Error handling
  - Condition serialization
  - Error codes configuration

* Validation
  - Types
  - Schemas (JSON, XML schemas)

* Versioning
  - Support for api versioning?

* Logging

* Cache handling

* Extensible
  - Backends (JSON, XML, etc)
  - Types
  - Validation

* Authentication
  - Different methods (token based, oauth)
  - Avoid changing the api interface spec because of this

* Modes
  - Debugging mode -> outputs full error serialization/backtrace
  - Production -> 500 internal server error

* Documentation
  - For the (lisp) developer
  - For the api consumer:
     - https://github.com/mashery/iodocs
     - http://swagger.wordnik.com/

* Resources
  - Good source of ideas:
    - http://django-rest-framework.org/
