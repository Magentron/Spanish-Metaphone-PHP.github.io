# Magentron\ApiLogger\Tests\TestCase  

Class TestCase

## Implements:
Orchestra\Testbench\Contracts\TestCase, PHPUnit_Framework_SelfDescribing, Countable, PHPUnit_Framework_Test

## Extend:

Orchestra\Testbench\TestCase

## Methods

| Name | Description |
|------|-------------|

## Inherited methods

| Name | Description |
|------|-------------|
|__construct|Constructs a test case with the given name.|
|actingAs|Set the currently logged in user for the application.|
|addToAssertionCount|Adds a value to the assertion counter.|
|any|Returns a matcher that matches when the method is executed
zero or more times.|
|anything|Returns a PHPUnit_Framework_Constraint_IsAnything matcher object.|
|arrayHasKey|Returns a PHPUnit_Framework_Constraint_ArrayHasKey matcher object.|
|artisan|Call artisan command and return code.|
|assertArrayHasKey|Asserts that an array has a specified key.|
|assertArrayNotHasKey|Asserts that an array does not have a specified key.|
|assertArraySubset|Asserts that an array has a specified subset.|
|assertAttributeContains|Asserts that a haystack that is stored in a static attribute of a class
or an attribute of an object contains a needle.|
|assertAttributeContainsOnly|Asserts that a haystack that is stored in a static attribute of a class
or an attribute of an object contains only values of a given type.|
|assertAttributeCount|Asserts the number of elements of an array, Countable or Traversable
that is stored in an attribute.|
|assertAttributeEmpty|Asserts that a static attribute of a class or an attribute of an object
is empty.|
|assertAttributeEquals|Asserts that a variable is equal to an attribute of an object.|
|assertAttributeGreaterThan|Asserts that an attribute is greater than another value.|
|assertAttributeGreaterThanOrEqual|Asserts that an attribute is greater than or equal to another value.|
|assertAttributeInstanceOf|Asserts that an attribute is of a given type.|
|assertAttributeInternalType|Asserts that an attribute is of a given type.|
|assertAttributeLessThan|Asserts that an attribute is smaller than another value.|
|assertAttributeLessThanOrEqual|Asserts that an attribute is smaller than or equal to another value.|
|assertAttributeNotContains|Asserts that a haystack that is stored in a static attribute of a class
or an attribute of an object does not contain a needle.|
|assertAttributeNotContainsOnly|Asserts that a haystack that is stored in a static attribute of a class
or an attribute of an object does not contain only values of a given
type.|
|assertAttributeNotCount|Asserts the number of elements of an array, Countable or Traversable
that is stored in an attribute.|
|assertAttributeNotEmpty|Asserts that a static attribute of a class or an attribute of an object
is not empty.|
|assertAttributeNotEquals|Asserts that a variable is not equal to an attribute of an object.|
|assertAttributeNotInstanceOf|Asserts that an attribute is of a given type.|
|assertAttributeNotInternalType|Asserts that an attribute is of a given type.|
|assertAttributeNotSame|Asserts that a variable and an attribute of an object do not have the
same type and value.|
|assertAttributeSame|Asserts that a variable and an attribute of an object have the same type
and value.|
|assertClassHasAttribute|Asserts that a class has a specified attribute.|
|assertClassHasStaticAttribute|Asserts that a class has a specified static attribute.|
|assertClassNotHasAttribute|Asserts that a class does not have a specified attribute.|
|assertClassNotHasStaticAttribute|Asserts that a class does not have a specified static attribute.|
|assertContains|Asserts that a haystack contains a needle.|
|assertContainsOnly|Asserts that a haystack contains only values of a given type.|
|assertContainsOnlyInstancesOf|Asserts that a haystack contains only instances of a given classname|
|assertCount|Asserts the number of elements of an array, Countable or Traversable.|
|assertDirectoryExists|Asserts that a directory exists.|
|assertDirectoryIsReadable|Asserts that a directory exists and is readable.|
|assertDirectoryIsWritable|Asserts that a directory exists and is writable.|
|assertDirectoryNotExists|Asserts that a directory does not exist.|
|assertDirectoryNotIsReadable|Asserts that a directory exists and is not readable.|
|assertDirectoryNotIsWritable|Asserts that a directory exists and is not writable.|
|assertEmpty|Asserts that a variable is empty.|
|assertEqualXMLStructure|Asserts that a hierarchy of DOMElements matches.|
|assertEquals|Asserts that two variables are equal.|
|assertFalse|Asserts that a condition is false.|
|assertFileEquals|Asserts that the contents of one file is equal to the contents of another
file.|
|assertFileExists|Asserts that a file exists.|
|assertFileIsReadable|Asserts that a file exists and is readable.|
|assertFileIsWritable|Asserts that a file exists and is writable.|
|assertFileNotEquals|Asserts that the contents of one file is not equal to the contents of
another file.|
|assertFileNotExists|Asserts that a file does not exist.|
|assertFileNotIsReadable|Asserts that a file exists and is not readable.|
|assertFileNotIsWritable|Asserts that a file exists and is not writable.|
|assertFinite|Asserts that a variable is finite.|
|assertGreaterThan|Asserts that a value is greater than another value.|
|assertGreaterThanOrEqual|Asserts that a value is greater than or equal to another value.|
|assertInfinite|Asserts that a variable is infinite.|
|assertInstanceOf|Asserts that a variable is of a given type.|
|assertInternalType|Asserts that a variable is of a given type.|
|assertIsReadable|Asserts that a file/dir is readable.|
|assertIsWritable|Asserts that a file/dir exists and is writable.|
|assertJson|Asserts that a string is a valid JSON string.|
|assertJsonFileEqualsJsonFile|Asserts that two JSON files are equal.|
|assertJsonFileNotEqualsJsonFile|Asserts that two JSON files are not equal.|
|assertJsonStringEqualsJsonFile|Asserts that the generated JSON encoded object and the content of the given file are equal.|
|assertJsonStringEqualsJsonString|Asserts that two given JSON encoded objects or arrays are equal.|
|assertJsonStringNotEqualsJsonFile|Asserts that the generated JSON encoded object and the content of the given file are not equal.|
|assertJsonStringNotEqualsJsonString|Asserts that two given JSON encoded objects or arrays are not equal.|
|assertLessThan|Asserts that a value is smaller than another value.|
|assertLessThanOrEqual|Asserts that a value is smaller than or equal to another value.|
|assertNan|Asserts that a variable is nan.|
|assertNotContains|Asserts that a haystack does not contain a needle.|
|assertNotContainsOnly|Asserts that a haystack does not contain only values of a given type.|
|assertNotCount|Asserts the number of elements of an array, Countable or Traversable.|
|assertNotEmpty|Asserts that a variable is not empty.|
|assertNotEquals|Asserts that two variables are not equal.|
|assertNotFalse|Asserts that a condition is not false.|
|assertNotInstanceOf|Asserts that a variable is not of a given type.|
|assertNotInternalType|Asserts that a variable is not of a given type.|
|assertNotIsReadable|Asserts that a file/dir exists and is not readable.|
|assertNotIsWritable|Asserts that a file/dir exists and is not writable.|
|assertNotNull|Asserts that a variable is not null.|
|assertNotRegExp|Asserts that a string does not match a given regular expression.|
|assertNotSame|Asserts that two variables do not have the same type and value.|
|assertNotSameSize|Assert that the size of two arrays (or `Countable` or `Traversable` objects)
is not the same.|
|assertNotTrue|Asserts that a condition is not true.|
|assertNull|Asserts that a variable is null.|
|assertObjectHasAttribute|Asserts that an object has a specified attribute.|
|assertObjectNotHasAttribute|Asserts that an object does not have a specified attribute.|
|assertRegExp|Asserts that a string matches a given regular expression.|
|assertSame|Asserts that two variables have the same type and value.|
|assertSameSize|Assert that the size of two arrays (or `Countable` or `Traversable` objects)
is the same.|
|assertStringEndsNotWith|Asserts that a string ends not with a given suffix.|
|assertStringEndsWith|Asserts that a string ends with a given suffix.|
|assertStringEqualsFile|Asserts that the contents of a string is equal
to the contents of a file.|
|assertStringMatchesFormat|Asserts that a string matches a given format string.|
|assertStringMatchesFormatFile|Asserts that a string matches a given format file.|
|assertStringNotEqualsFile|Asserts that the contents of a string is not equal
to the contents of a file.|
|assertStringNotMatchesFormat|Asserts that a string does not match a given format string.|
|assertStringNotMatchesFormatFile|Asserts that a string does not match a given format string.|
|assertStringStartsNotWith|Asserts that a string starts not with a given prefix.|
|assertStringStartsWith|Asserts that a string starts with a given prefix.|
|assertThat|Evaluates a PHPUnit_Framework_Constraint matcher object.|
|assertTrue|Asserts that a condition is true.|
|assertXmlFileEqualsXmlFile|Asserts that two XML files are equal.|
|assertXmlFileNotEqualsXmlFile|Asserts that two XML files are not equal.|
|assertXmlStringEqualsXmlFile|Asserts that two XML documents are equal.|
|assertXmlStringEqualsXmlString|Asserts that two XML documents are equal.|
|assertXmlStringNotEqualsXmlFile|Asserts that two XML documents are not equal.|
|assertXmlStringNotEqualsXmlString|Asserts that two XML documents are not equal.|
|at|Returns a matcher that matches when the method is executed
at the given index.|
|atLeast|Returns a matcher that matches when the method is executed
at least N times.|
|atLeastOnce|Returns a matcher that matches when the method is executed at least once.|
|atMost|Returns a matcher that matches when the method is executed
at most N times.|
|attribute|Returns a PHPUnit_Framework_Constraint_Attribute matcher object.|
|attributeEqualTo|Returns a PHPUnit_Framework_Constraint_IsEqual matcher object
that is wrapped in a PHPUnit_Framework_Constraint_Attribute matcher
object.|
|be|Set the currently logged in user for the application.|
|call|Call the given URI and return the Response.|
|callback|Returns a PHPUnit_Framework_Constraint_Callback matcher object.|
|classHasAttribute|Returns a PHPUnit_Framework_Constraint_ClassHasAttribute matcher object.|
|classHasStaticAttribute|Returns a PHPUnit_Framework_Constraint_ClassHasStaticAttribute matcher
object.|
|contains|Returns a PHPUnit_Framework_Constraint_TraversableContains matcher
object.|
|containsOnly|Returns a PHPUnit_Framework_Constraint_TraversableContainsOnly matcher
object.|
|containsOnlyInstancesOf|Returns a PHPUnit_Framework_Constraint_TraversableContainsOnly matcher
object.|
|count|Counts the number of test cases executed by run(TestResult result).|
|countOf|Returns a PHPUnit_Framework_Constraint_Count matcher object.|
|createApplication|Creates the application.|
| [dataDescription](https://secure.php.net/manual/en/phpunit_framework_testcase.datadescription.php) | - |
|delete|Visit the given URI with a DELETE request.|
|deleteJson|Visit the given URI with a DELETE request, expecting a JSON response.|
|directoryExists|Returns a PHPUnit_Framework_Constraint_DirectoryExists matcher object.|
| [doesNotPerformAssertions](https://secure.php.net/manual/en/phpunit_framework_testcase.doesnotperformassertions.php) | - |
|doesntExpectEvents|Specify a list of events that should not be fired for the given operation.|
|dontSeeCredentials|Assert that the given credentials are invalid.|
|dontSeeIsAuthenticated|Assert that the user is not authenticated.|
|equalTo|Returns a PHPUnit_Framework_Constraint_IsEqual matcher object.|
|exactly|Returns a matcher that matches when the method is executed
exactly $count times.|
| [expectException](https://secure.php.net/manual/en/phpunit_framework_testcase.expectexception.php) | - |
| [expectExceptionCode](https://secure.php.net/manual/en/phpunit_framework_testcase.expectexceptioncode.php) | - |
| [expectExceptionMessage](https://secure.php.net/manual/en/phpunit_framework_testcase.expectexceptionmessage.php) | - |
| [expectExceptionMessageRegExp](https://secure.php.net/manual/en/phpunit_framework_testcase.expectexceptionmessageregexp.php) | - |
| [expectOutputRegex](https://secure.php.net/manual/en/phpunit_framework_testcase.expectoutputregex.php) | - |
| [expectOutputString](https://secure.php.net/manual/en/phpunit_framework_testcase.expectoutputstring.php) | - |
|expectsEvents|Specify a list of events that should be fired for the given operation.|
|fail|Fails a test with the given message.|
|fileExists|Returns a PHPUnit_Framework_Constraint_FileExists matcher object.|
|get|Visit the given URI with a GET request.|
| [getActualOutput](https://secure.php.net/manual/en/phpunit_framework_testcase.getactualoutput.php) | - |
|getAnnotations|Returns the annotations for this test.|
|getCount|Return the current assertion count.|
| [getExpectedException](https://secure.php.net/manual/en/phpunit_framework_testcase.getexpectedexception.php) | - |
| [getGroups](https://secure.php.net/manual/en/phpunit_framework_testcase.getgroups.php) | - |
|getJson|Visit the given URI with a GET request, expecting a JSON response.|
|getMockBuilder|Returns a builder object to create mock objects using a fluent interface.|
|getName|Gets the name of a TestCase.|
|getNumAssertions|Returns the number of assertions performed by this test.|
|getObjectAttribute|Returns the value of an object's attribute.|
| [getResult](https://secure.php.net/manual/en/phpunit_framework_testcase.getresult.php) | - |
|getSize|Returns the size of the test.|
|getStaticAttribute|Returns the value of a static attribute.|
|getStatus|Returns the status of this test.|
|getStatusMessage|Returns the status message of this test.|
| [getTestResultObject](https://secure.php.net/manual/en/phpunit_framework_testcase.gettestresultobject.php) | - |
|greaterThan|Returns a PHPUnit_Framework_Constraint_GreaterThan matcher object.|
|greaterThanOrEqual|Returns a PHPUnit_Framework_Constraint_Or matcher object that wraps
a PHPUnit_Framework_Constraint_IsEqual and a
PHPUnit_Framework_Constraint_GreaterThan matcher object.|
|hasDependencies|Returns true if the tests has dependencies|
| [hasExpectationOnOutput](https://secure.php.net/manual/en/phpunit_framework_testcase.hasexpectationonoutput.php) | - |
|hasFailed|Returns whether or not this test has failed.|
| [hasOutput](https://secure.php.net/manual/en/phpunit_framework_testcase.hasoutput.php) | - |
| [hasPerformedExpectationsOnOutput](https://secure.php.net/manual/en/phpunit_framework_testcase.hasperformedexpectationsonoutput.php) | - |
| [hasSize](https://secure.php.net/manual/en/phpunit_framework_testcase.hassize.php) | - |
|identicalTo|Returns a PHPUnit_Framework_Constraint_IsIdentical matcher object.|
|isEmpty|Returns a PHPUnit_Framework_Constraint_IsEmpty matcher object.|
|isFalse|Returns a PHPUnit_Framework_Constraint_IsFalse matcher object.|
|isFinite|Returns a PHPUnit_Framework_Constraint_IsFinite matcher object.|
| [isInIsolation](https://secure.php.net/manual/en/phpunit_framework_testcase.isinisolation.php) | - |
|isInfinite|Returns a PHPUnit_Framework_Constraint_IsInfinite matcher object.|
|isInstanceOf|Returns a PHPUnit_Framework_Constraint_IsInstanceOf matcher object.|
|isJson|Returns a PHPUnit_Framework_Constraint_IsJson matcher object.|
| [isLarge](https://secure.php.net/manual/en/phpunit_framework_testcase.islarge.php) | - |
| [isMedium](https://secure.php.net/manual/en/phpunit_framework_testcase.ismedium.php) | - |
|isNan|Returns a PHPUnit_Framework_Constraint_IsNan matcher object.|
|isNull|Returns a PHPUnit_Framework_Constraint_IsNull matcher object.|
|isReadable|Returns a PHPUnit_Framework_Constraint_IsReadable matcher object.|
| [isSmall](https://secure.php.net/manual/en/phpunit_framework_testcase.issmall.php) | - |
|isTrue|Returns a PHPUnit_Framework_Constraint_IsTrue matcher object.|
|isType|Returns a PHPUnit_Framework_Constraint_IsType matcher object.|
|isWritable|Returns a PHPUnit_Framework_Constraint_IsWritable matcher object.|
|json|Call the given URI with a JSON request.|
|lessThan|Returns a PHPUnit_Framework_Constraint_LessThan matcher object.|
|lessThanOrEqual|Returns a PHPUnit_Framework_Constraint_Or matcher object that wraps
a PHPUnit_Framework_Constraint_IsEqual and a
PHPUnit_Framework_Constraint_LessThan matcher object.|
|logicalAnd|Returns a PHPUnit_Framework_Constraint_And matcher object.|
|logicalNot|Returns a PHPUnit_Framework_Constraint_Not matcher object.|
|logicalOr|Returns a PHPUnit_Framework_Constraint_Or matcher object.|
|logicalXor|Returns a PHPUnit_Framework_Constraint_Xor matcher object.|
| [markAsRisky](https://secure.php.net/manual/en/phpunit_framework_testcase.markasrisky.php) | - |
|markTestIncomplete|Mark the test as incomplete.|
|markTestSkipped|Mark the test as skipped.|
|matches|Returns a PHPUnit_Framework_Constraint_StringMatches matcher object.|
|matchesRegularExpression|Returns a PHPUnit_Framework_Constraint_PCREMatch matcher object.|
|never|Returns a matcher that matches when the method is never executed.|
|objectHasAttribute|Returns a PHPUnit_Framework_Constraint_ObjectHasAttribute matcher object.|
| [onConsecutiveCalls](https://secure.php.net/manual/en/phpunit_framework_testcase.onconsecutivecalls.php) | - |
|once|Returns a matcher that matches when the method is executed exactly once.|
|patch|Visit the given URI with a PATCH request.|
|patchJson|Visit the given URI with a PATCH request, expecting a JSON response.|
|post|Visit the given URI with a POST request.|
|postJson|Visit the given URI with a POST request, expecting a JSON response.|
|put|Visit the given URI with a PUT request.|
|putJson|Visit the given URI with a PUT request, expecting a JSON response.|
|readAttribute|Returns the value of an attribute of a class or an object.|
| [registerMockObject](https://secure.php.net/manual/en/phpunit_framework_testcase.registermockobject.php) | - |
|resetCount|Reset the assertion counter.|
| [returnArgument](https://secure.php.net/manual/en/phpunit_framework_testcase.returnargument.php) | - |
| [returnCallback](https://secure.php.net/manual/en/phpunit_framework_testcase.returncallback.php) | - |
|returnSelf|Returns the current object.|
| [returnValue](https://secure.php.net/manual/en/phpunit_framework_testcase.returnvalue.php) | - |
| [returnValueMap](https://secure.php.net/manual/en/phpunit_framework_testcase.returnvaluemap.php) | - |
|run|Runs the test case and collects the results in a TestResult object.|
|runBare|Runs the bare test sequence.|
|runLaravelDefaultMigrations|Migrate Laravel's default migrations.|
|seeCredentials|Assert that the given credentials are valid.|
|seeIsAuthenticated|Assert that the user is authenticated.|
|seeIsAuthenticatedAs|Assert that the user is authenticated as the given user.|
|seed|Seed a given database connection.|
|setBackupGlobals|Calling this method in setUp() has no effect!|
|setBackupStaticAttributes|Calling this method in setUp() has no effect!|
| [setBeStrictAboutChangesToGlobalState](https://secure.php.net/manual/en/phpunit_framework_testcase.setbestrictaboutchangestoglobalstate.php) | - |
|setDependencies|Sets the dependencies of a TestCase.|
|setDependencyInput|Sets|
| [setExpectedException](https://secure.php.net/manual/en/phpunit_framework_testcase.setexpectedexception.php) | - |
| [setExpectedExceptionRegExp](https://secure.php.net/manual/en/phpunit_framework_testcase.setexpectedexceptionregexp.php) | - |
| [setGroups](https://secure.php.net/manual/en/phpunit_framework_testcase.setgroups.php) | - |
| [setInIsolation](https://secure.php.net/manual/en/phpunit_framework_testcase.setinisolation.php) | - |
|setName|Sets the name of a TestCase.|
| [setOutputCallback](https://secure.php.net/manual/en/phpunit_framework_testcase.setoutputcallback.php) | - |
| [setPreserveGlobalState](https://secure.php.net/manual/en/phpunit_framework_testcase.setpreserveglobalstate.php) | - |
| [setRegisterMockObjectsFromTestArgumentsRecursively](https://secure.php.net/manual/en/phpunit_framework_testcase.setregistermockobjectsfromtestargumentsrecursively.php) | - |
| [setResult](https://secure.php.net/manual/en/phpunit_framework_testcase.setresult.php) | - |
| [setRunTestInSeparateProcess](https://secure.php.net/manual/en/phpunit_framework_testcase.setruntestinseparateprocess.php) | - |
| [setTestResultObject](https://secure.php.net/manual/en/phpunit_framework_testcase.settestresultobject.php) | - |
|setUpBeforeClass|This method is called before the first test of this test class is run.|
| [setUseErrorHandler](https://secure.php.net/manual/en/phpunit_framework_testcase.setuseerrorhandler.php) | - |
|stringContains|Returns a PHPUnit_Framework_Constraint_StringContains matcher object.|
|stringEndsWith|Returns a PHPUnit_Framework_Constraint_StringEndsWith matcher object.|
|stringStartsWith|Returns a PHPUnit_Framework_Constraint_StringStartsWith matcher object.|
|tearDownAfterClass|This method is called after the last test of this test class is run.|
| [throwException](https://secure.php.net/manual/en/phpunit_framework_testcase.throwexception.php) | - |
|toString|Returns a string representation of the test case.|
| [usesDataProvider](https://secure.php.net/manual/en/phpunit_framework_testcase.usesdataprovider.php) | - |
|withServerVariables|Define a set of server variables to be sent with the requests.|
|withoutMiddleware|Disable middleware for the test.|


