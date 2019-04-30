Hiptest publisher: samples
=======================

This repository is a meta-repository to link all hps-* repositories, which show tests generated from [Hiptest](https://hiptest.com), using [Hiptest publisher](https://github.com/hiptest/hiptest-publisher).


System under test
------------------

The SUT is a (not that much) simple coffee machine. You start it, you ask for a coffee and you get it, sometimes. But most of times you have to add water or beans, empty the grounds. You have an automatic expresso machine at work or at home? So you know how it goes :-)

Languages
----------

For each supported language and frameworks supported by hiptest-publisher, we have a dedicated Github repository which shows the tests generated. All repositories are connected to Travis to show how hiptest integrates with a CI tool.
If Travis does not show any status, that means that its an export we're working on and that should be available in the next release of hiptest-publisher.

### Ruby

| | Rspec  | Minitest  | Cucumber  |
|:-:|:-:|:-:|:-:|
| Repository   | [hps-ruby-rspec](https://github.com/hiptest/hps-ruby-rspec) | [hps-ruby-minitest](https://github.com/hiptest/hps-ruby-minitest) | [hps-cucumber-ruby](https://github.com/hiptest/hps-cucumber-ruby) |
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-ruby-rspec.svg?branch=master)](https://travis-ci.org/hiptest/hps-ruby-rspec) | [![Build Status](https://travis-ci.org/hiptest/hps-ruby-minitest.svg?branch=master)](https://travis-ci.org/hiptest/hps-ruby-minitest) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-ruby.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-ruby) |
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1354)](https://app.hiptest.com/projects/1512/test-runs/1354) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1356)](https://app.hiptest.com/projects/1512/test-runs/1356) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/3507)](https://app.hiptest.com/projects/1512/test-runs/3507) |


### Javascript

|  | qUnit | Jasmine | Mocha | Protractor | Cucumber-js |
|:-:|:-:|:-:|:-:|:-:|:-:|
| Repository | [hps-javascript-qunit](https://github.com/hiptest/hps-javascript-qunit) | [hps-javascript-jasmine](https://github.com/hiptest/hps-javascript-jasmine) | [hps-javascript-mocha](https://github.com/hiptest/hps-javascript-mocha) | [hps-protractor](https://github.com/hiptest/hps-protractor) | [hps-cucumber-javascript](https://github.com/hiptest/hps-cucumber-javascript) |
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-javascript-qunit.svg?branch=master)](https://travis-ci.org/hiptest/hps-javascript-qunit) | [![Build Status](https://travis-ci.org/hiptest/hps-javascript-jasmine.svg?branch=master)](https://travis-ci.org/hiptest/hps-javascript-jasmine) | [![Build Status](https://travis-ci.org/hiptest/hps-javascript-mocha.svg?branch=master)](https://travis-ci.org/hiptest/hps-javascript-mocha) | [![Build Status](https://travis-ci.org/hiptest/hps-protractor.svg?branch=master)](https://travis-ci.org/hiptest/hps-protractor) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-javascript.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-javascript) |
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1966)](https://app.hiptest.com/projects/1512/test-runs/1966) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1979)](https://app.hiptest.com/projects/1512/test-runs/1979) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/11085)](https://app.hiptest.com/projects/1512/test-runs/11085) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/52538)](https://app.hiptest.com/projects/1512/test-runs/52538) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/16534)](https://app.hiptest.com/projects/1512/test-runs/16534) |

### Java

|  | JUnit | TestNG | Cucumber/Java | JBehave |
|:-:|:-:|:-:|:-:| :-: |
| Repository | [hps-java-junit](https://github.com/hiptest/hps-java-junit) | [hps-java-testng](https://github.com/hiptest/hps-java-testng) | [hps-cucumber-java](https://github.com/hiptest/hps-cucumber-java) | [hps-jbehave](https://github.com/hiptest/hps-jbehave) |
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-java-junit.svg?branch=master)](https://travis-ci.org/hiptest/hps-java-junit) | [![Build Status](https://travis-ci.org/hiptest/hps-java-testng.svg?branch=master)](https://travis-ci.org/hiptest/hps-java-testng) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-java.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-java) | [![Build Status](https://travis-ci.org/hiptest/hps-jbehave.svg?branch=master)](https://travis-ci.org/hiptest/hps-jbehave) |
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1358)](https://app.hiptest.com/projects/1512/test-runs/1358) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1359)](https://app.hiptest.com/projects/1512/test-runs/1359) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/10248)](https://app.hiptest.com/projects/1512/test-runs/10248) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/162509)](https://app.hiptest.com/projects/1512/test-runs/162509/overview) |

### Python

|  | UnitTest | Behave |
|:-:|:-:|:-:|
| Repository | [hps-python-unittest](https://github.com/hiptest/hps-python-unittest) | [hps-behave](https://github.com/hiptest/hps-behave) |
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-python-unittest.svg?branch=master)](https://travis-ci.org/hiptest/hps-python-unittest) | [![Build Status](https://travis-ci.org/hiptest/hps-behave.svg?branch=master)](https://travis-ci.org/hiptest/hps-behave) |
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1357)](https://app.hiptest.com/projects/1512/test-runs/1357) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/16134)](https://app.hiptest.com/projects/1512/test-runs/16134) |

### PHP

|  | PHPUnit | Behat |
|:-:|:-:|:-:|
| Repository | [hps-php-phpunit](https://github.com/hiptest/hps-php-phpunit) | [hps-behat](https://github.com/hiptest/hps-behat) |
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-php-phpunit.svg?branch=master)](https://travis-ci.org/hiptest/hps-php-phpunit) | [![Build Status](https://travis-ci.org/hiptest/hps-behat.svg?branch=master)](https://travis-ci.org/hiptest/hps-behat) |
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/11084)](https://app.hiptest.com/projects/1512/test-runs/11084) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/16135)](https://app.hiptest.com/projects/1512/test-runs/16135) |

### C#

|  | NUnit | Specflow |
|:-:|:-:|:-:|
| Repository | [hps-csharp-nunit](https://github.com/hiptest/hps-csharp-nunit) | [hps-specflow](https://github.com/hiptest/hps-specflow) |
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-csharp-nunit.svg?branch=master)](https://travis-ci.org/hiptest/hps-csharp-nunit) | [![Build Status](https://travis-ci.org/hiptest/hps-specflow.svg?branch=master)](https://travis-ci.org/hiptest/hps-specflow) |
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/9861)](https://app.hiptest.com/projects/1512/test-runs/9861) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/9941)](https://app.hiptest.com/projects/1512/test-runs/9941) |

### Groovy

|   | Spock | Cucumber |
|:-:|  :-:  |    :-:   |
| Repository   | [hps-groovy-spock](https://github.com/hiptest/hps-groovy-spock) | [hps-cucumber-groovy](https://github.com/hiptest/hps-cucumber-groovy)
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-groovy-spock.svg?branch=master)](https://travis-ci.org/hiptest/hps-groovy-spock) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-groovy.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-groovy)
| Hiptest      | [![Hiptest Status](https://app.hiptest.com/badges/test_run/81415)](https://app.hiptest.com/projects/1512/test-runs/81415) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/185700)](https://app.hiptest.com/projects/1512/test-runs/185700/overview)

### Robot framework

|  | Robot framework |
|:-:|:-:|
| Repository | [hps-robotframework](https://github.com/hiptest/hps-robotframework) |
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-robotframework.svg?branch=master)](https://travis-ci.org/hiptest/hps-robotframework) |
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/1360)](https://app.hiptest.com/projects/1512/test-runs/1360) |

### All Gherkin-based

|  | Cucumber/Ruby | Cucumber/Java | Specflow | Behave | Behat | Cucumber-js | Cucumber/Groovy | Cucumber/Typescript
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Repository | [hps-cucumber-ruby](https://github.com/hiptest/hps-cucumber-ruby) | [hps-cucumber-java](https://github.com/hiptest/hps-cucumber-java) | [hps-specflow](https://github.com/hiptest/hps-specflow) | [hps-behave](https://github.com/hiptest/hps-behave) | [hps-behat](https://github.com/hiptest/hps-behat) | [hps-cucumber-javascript](https://github.com/hiptest/hps-cucumber-javascript) | [hps-cucumber-groovy](https://github.com/hiptest/hps-cucumber-groovy) | [hps-cucumber-typescript](https://github.com/hiptest/hps-cucumber-typescript)
| Build status | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-ruby.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-ruby) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-java.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-java) | [![Build Status](https://travis-ci.org/hiptest/hps-specflow.svg?branch=master)](https://travis-ci.org/hiptest/hps-specflow) | [![Build Status](https://travis-ci.org/hiptest/hps-behave.svg?branch=master)](https://travis-ci.org/hiptest/hps-behave) | [![Build Status](https://travis-ci.org/hiptest/hps-behat.svg?branch=master)](https://travis-ci.org/hiptest/hps-behat) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-javascript.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-javascript) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-groovy.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-groovy) | [![Build Status](https://travis-ci.org/hiptest/hps-cucumber-typescript.svg?branch=master)](https://travis-ci.org/hiptest/hps-cucumber-typescript)
| Hiptest | [![Hiptest Status](https://app.hiptest.com/badges/test_run/3507)](https://app.hiptest.com/projects/1512/test-runs/3507) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/10248)](https://app.hiptest.com/projects/1512/test-runs/10248) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/9941)](https://app.hiptest.com/projects/1512/test-runs/9941) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/16134)](https://app.hiptest.com/projects/1512/test-runs/16134) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/16135)](https://app.hiptest.com/projects/1512/test-runs/16135) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/16534)](https://app.hiptest.com/projects/1512/test-runs/16534) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/185700)](https://app.hiptest.com/projects/1512/test-runs/185700/overview) | [![Hiptest Status](https://app.hiptest.com/badges/test_run/258520)](https://app.hiptest.com/projects/1512/test-runs/258520/overview)


Releasing a new version of hiptest-publisher
--------------------------------------------

When a new release of hiptest-publisher is done, it is important to run the tests again on the ``hps-*`` repositories. To do so:
 - check that you have read/write access to all ``hps-*`` repositories
 - from this repository, run:

```shell
bin/clone-all
bin/update-hps-version 0.10.0 # Or whatever version has just been released
```

That will make a new commit in each repositories and trigger the Travis build.

When a new language is added, also ensure that the file ``hps/repos-list`` contains the name of the repository showing the samples.
