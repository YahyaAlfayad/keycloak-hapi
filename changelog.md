## 4.0.0

* Update hapi dependencies

## 3.0.0

* Update keycloak-connect

## 2.1.0

* Add api logout endpoint for non-browser invocation (without redirection)

## 1.2.2

* Pass locale query (kc_locale or ui_locale) in logout redirect uri to login page

## 1.2.1

* Returning `401` response to AJAX requests instead of sending a redirect

## 1.2.0

* Add possibility to specify a base url to cover cases where we can't relay on `x-forwarded-*` headers
* Expose `loginUrl` in principal

## 1.1.0

* Add support for [Back-Channel Logout](https://openid.net/specs/openid-connect-backchannel-1_0.html) procedure

## 1.0.3

* Add possibility to specify a base path of reverse proxy

## 1.0.0 - initial release