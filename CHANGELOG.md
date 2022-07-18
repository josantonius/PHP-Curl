# CHANGELOG

## 1.1.7 - 2022-07-18

The repository was archived.

## 1.1.6 - 2018-01-05

* The tests were fixed.

* Changes in documentation.

## 1.1.5 - 2017-11-08

* Implemented `PHP Mess Detector` to detect inconsistencies in code styles.

* Implemented `PHP Code Beautifier and Fixer` to fixing errors automatically.

* Implemented `PHP Coding Standards Fixer` to organize PHP code automatically according to PSR standards.

* Deleted `Josantonius\Curl\Exception\CurlException` class.
* Deleted `Josantonius\Curl\Exception\Exceptions` abstract class.
* Deleted `Josantonius\Curl\Exception\CurlException->__construct()` method.

## 1.1.4 - 2017-10-25

* Implemented `PSR-4 autoloader standard` from all library files.

* Implemented `PSR-2 coding standard` from all library PHP files.

* Implemented `PHPCS` to ensure that PHP code complies with `PSR2` code standards.

* Implemented `Codacy` to automates code reviews and monitors code quality over time.

* Implemented `Codecov` to coverage reports.

* Added `Curl/phpcs.ruleset.xml` file.

* Deleted `Curl/src/bootstrap.php` file.

* Deleted `Curl/tests/bootstrap.php` file.

* Deleted `Curl/vendor` folder.

* Changed `Josantonius\Curl\Test\CurlTest` class to  `Josantonius\Curl\CurlTest` class .

## 1.1.3 - 2017-09-11

* Unit tests supported by `PHPUnit` were added.

* The repository was synchronized with Travis CI to implement continuous integration.

* Added `Curl/src/bootstrap.php` file

* Added `Curl/tests/bootstrap.php` file.

* Added `Curl/phpunit.xml.dist` file.
* Added `Curl/_config.yml` file.
* Added `Curl/.travis.yml` file.

* Deleted `Josantonius\Curl\Curl::getUrl()` method.

* Added `Josantonius\Curl\Curl::_getUrl()` method.
* Added `Josantonius\Curl\Curl::_setCurlOptions()` method.
* Added `Josantonius\Curl\Curl::_checkParams()` method.

* Deleted `Josantonius\Curl\Tests\CurlTest` class.
* Deleted `Josantonius\Curl\Tests\CurlTest::testGetRequest()` method.
* Deleted `Josantonius\Curl\Tests\CurlTest::testPostRequest()` method.
* Deleted `Josantonius\Curl\Tests\CurlTest::testPutRequest()` method.
* Deleted `Josantonius\Curl\Tests\CurlTest::testDeleteRequest()` method.
* Deleted `Josantonius\Curl\Tests\CurlTest::testResponseError()` method.
* Deleted `Josantonius\Curl\Tests\CurlTest::testUnknownTypeError()` method.

* Added `Josantonius\Curl\Test\CurlTest` class.
* Added `Josantonius\Curl\Test\CurlTest->testGetRequestArray()` method.
* Added `Josantonius\Curl\Test\CurlTest->testGetRequestObject()` method.
* Added `Josantonius\Curl\Test\CurlTest->testGetRequestWithParamsArray()` method.
* Added `Josantonius\Curl\Test\CurlTest->testGetRequestWithParamsObject()` method.
* Added `Josantonius\Curl\Test\CurlTest->testGetRequestError()` method.
* Added `Josantonius\Curl\Test\CurlTest->testPostRequestArray()` method.
* Added `Josantonius\Curl\Test\CurlTest->testPostRequestObject()` method.
* Added `Josantonius\Curl\Test\CurlTest->testPostRequestError()` method.
* Added `Josantonius\Curl\Test\CurlTest->testPostRequestArray()` method.
* Added `Josantonius\Curl\Test\CurlTest->testPutRequestArray()` method.
* Added `Josantonius\Curl\Test\CurlTest->testPutRequestObject()` method.
* Added `Josantonius\Curl\Test\CurlTest->testPutRequestError()` method.
* Added `Josantonius\Curl\Test\CurlTest->testDeleteRequestArray()` method.
* Added `Josantonius\Curl\Test\CurlTest->testDeleteRequestObject()` method.
* Added `Josantonius\Curl\Test\CurlTest->testDeleteRequestError()` method.
* Added `Josantonius\Curl\Test\CurlTest->testTypeRequestError()` method.

## 1.1.2 - 2017-06-21

* Error fixed in the `request()` method.

## 1.1.1 - 2017-03-18

* Some files were excluded from download and comments and readme files were updated.

## 1.1.0 - 2017-01-30

* Compatible with PHP 5.6 or higher.

## 1.0.0 - 2017-01-30

* Compatible only with PHP 7.0 or higher. In the next versions, the library will be modified to make it compatible with PHP 5.6 or higher.

## 1.0.0 - 2016-12-15

* Added `Josantonius\Curl\Curl` class.
* Added `Josantonius\Curl\Curl::request()` method.
* Added `Josantonius\Curl\Curl::getUrl()` method.

## 1.0.0 - 2016-12-15

* Added `Josantonius\Curl\Exception\CurlException` class.
* Added `Josantonius\Curl\Exception\Exceptions` abstract class.
* Added `Josantonius\Curl\Exception\CurlException->__construct()` method.

## 1.0.0 - 2016-12-15

* Added `Josantonius\Curl\Tests\CurlTest` class.
* Added `Josantonius\Curl\Tests\CurlTest::testGetRequest()` method.
* Added `Josantonius\Curl\Tests\CurlTest::testPostRequest()` method.
* Added `Josantonius\Curl\Tests\CurlTest::testPutRequest()` method.
* Added `Josantonius\Curl\Tests\CurlTest::testDeleteRequest()` method.
* Added `Josantonius\Curl\Tests\CurlTest::testResponseError()` method.
* Added `Josantonius\Curl\Tests\CurlTest::testUnknownTypeError()` method.
