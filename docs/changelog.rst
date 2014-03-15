.. changelog

===============
Release History
===============

0.6.2
-----
* Refactored ``NgFormValidationMixin``, so that potential AngularJS errors do not interfere with
  Django's internal error list. This now allows to use the same form definition for bound and
  unbound forms.

0.6.1
-----
* Bug fix for CRUD view.

0.6.0
-----
* Support for basic CRUD view.

0.5.0
-----
* Added three way data binding.

0.4.0
-----
* Removed @csrf_exempt on dispatch method for Ajax requests.

0.3.0
-----
Client side form validation for Django forms using AngularJS

0.2.2
-----
* Removed now useless directive 'auto-label'. For backwards compatibility
  see https://github.com/jrief/angular-shims-placeholder

0.2.1
-----
* Set Cache-Control: no-cache for Ajax GET requests.

0.2.0
-----
* added handler to mixin class for ajax get requests.
* moved unit tests into testing directory.
* changed request.raw_post_data -> request.body.
* added possibility to pass get and post requests through to inherited view class.

0.1.4
-----
* optimized CI process

0.1.3
-----
* added first documents

0.1.2
-----
* better packaging support

0.1.1
-----
* fixed initial data in NgModelFormMixin

0.1.0
-----
* initial revision