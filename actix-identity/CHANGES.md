# Changes

## Unreleased - 2020-xx-xx
* Minimum supported Rust version (MSRV) is now 1.52.


## 0.4.0-beta.2 - 2020-06-27
* No notable changes.


## 0.4.0-beta.1 - 2020-04-02
* Rename `CookieIdentityPolicy::{max_age => max_age_secs}`. [#168]
* Rename `CookieIdentityPolicy::{max_age_time => max_age}`. [#168]
* Update `actix-web` dependency to 4.0.0 beta.
* Minimum supported Rust version (MSRV) is now 1.46.0.

[#168]: https://github.com/actix/actix-extras/pull/168


## 0.3.1 - 2020-09-20
* Add method to set `HttpOnly` flag on cookie identity. [#102]

[#102]: https://github.com/actix/actix-extras/pull/102


## 0.3.0 - 2020-09-11
* Update `actix-web` dependency to 3.0.0.
* Minimum supported Rust version (MSRV) is now 1.42.0.


## 0.3.0-alpha.1 - 2020-03-14
* Update the `time` dependency to 0.2.7
* Update the `actix-web` dependency to 3.0.0-alpha.1
* Minimize `futures` dependency


## 0.2.1 - 2020-01-10
* Fix panic with already borrowed: BorrowMutError #1263


## 0.2.0 - 2019-12-20
* Use actix-web 2.0


## 0.1.0 - 2019-06-xx
* Move identity middleware to separate crate


<!-- PR Links -->

[#102]: https://github.com/actix/actix-extras/pull/102
