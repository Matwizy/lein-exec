# Changes and TODO

## 0.3.7 / 2017-Oct-27

* Fix [#26](https://github.com/kumarshantanu/lein-exec/issues/26) - use HTTPS
  for Clojars repo.

## 0.3.6 / 2016-Jan-21

* Fix [#24](https://github.com/kumarshantanu/lein-exec/issues/21) - scripts in
  current directory (where CWD contains space chars) are not located.
* Print diagnostic path info on `java.io.FileNotFoundException` (possibly when
  script not found).

## 0.3.5 / 2015-05-27

* Fix [#21](https://github.com/kumarshantanu/lein-exec/issues/21) - support for 
  settings from user profiles.clj ([sashton](Steve Ashton))

## No release / 2014-08-03

* Fix incorrect in-project resolution of script path (Velrok)

## 0.3.4 / 2014-06-28

* Fix [#8](https://github.com/kumarshantanu/lein-exec/issues/8) - support for
  automatically running `-main` if present
  (Shantanu Kumar, with help from [@asimjalis](https://github.com/asimjalis))

## 0.3.3 / 2014-04-01

* Fix spurious error message due to premature termination:
[lein-exec + with-profile results in error](https://github.com/kumarshantanu/lein-exec/issues/13)
(Shantanu Kumar)

## 0.3.2 / 2014-02-18

* Fix typo in help text (kbaribeau)

## 0.3.1 / 2013-08-12

* Integrate command-line help switch (mneilsen)

## 0.3.0 / 2013-02-01

* `deps` accepts :repositories keyword (hikoz)
* Use `lein` executable in scripts

## 0.2.1 / 2012-08-17

* End evals with lein2's main/exit (geriatric)

## 0.2.0

* Execute script outside or inside of a project (Lein 2 and Lein 1.x)

## 0.1.0

* Execute script in a project (Lein 1.x only)
