Siddhi Execution Json
======================================

  [![Jenkins Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-json/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-json/)
  [![GitHub (pre-)Release](https://img.shields.io/github/release/siddhi-io/siddhi-execution-json/all.svg)](https://github.com/siddhi-io/siddhi-execution-json/releases)
  [![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/siddhi-io/siddhi-execution-json.svg)](https://github.com/siddhi-io/siddhi-execution-json/releases)
  [![GitHub Open Issues](https://img.shields.io/github/issues-raw/siddhi-io/siddhi-execution-json.svg)](https://github.com/siddhi-io/siddhi-execution-json/issues)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/siddhi-io/siddhi-execution-json.svg)](https://github.com/siddhi-io/siddhi-execution-json/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The **siddhi-execution-json extension** is a <a target="_blank" href="https://siddhi.io/">Siddhi</a> extension that provides capability to retrieve, insert, and modify JSON elements.

For information on <a target="_blank" href="https://siddhi.io/">Siddhi</a> and it's features refer <a target="_blank" href="https://siddhi.io/redirect/docs.html">Siddhi Documentation</a>. 

## Download

* Versions 1.x and above with group id `io.siddhi.extension.*` from <a target="_blank" href="https://mvnrepository.com/artifact/io.siddhi.extension.execution.json/siddhi-execution-json/">here</a>.
* Versions 2.x and lower with group id `org.wso2.extension.siddhi.*` from <a target="_blank" href="https://mvnrepository.com/artifact/org.wso2.extension.siddhi.execution.json/siddhi-execution-json">here</a>.

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3">5.0.3</a>.

## Features

* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#groupconcat-aggregate-function">groupConcat</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#aggregate-function">Aggregate Function</a>)*<br> <div style="padding-left: 1em;"><p>This function aggregates the received events by concatenating the keys in those events using a separator, e.g.,a comma (,) or a hyphen (-), and returns the concatenated key json.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#charat-function">charAt</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the 'char' value that is present at the given index position. of the input json.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#coalesce-function">coalesce</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p> This returns the first input parameter value of the given argument, that is not null.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#concat-function">concat</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns a json value that is obtained as a result of concatenating two or more input json values.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#contains-function">contains</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns <code>true</code> if the<code>input.json</code> contains the specified sequence of char values in the <code>search.json</code>. </p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#equalsignorecase-function">equalsIgnoreCase</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This returns a boolean value by comparing two jsons lexicographically without considering the letter case.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#filltemplate-function">fillTemplate</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This extension replaces the templated positions that are marked with an index value in a specified template with the jsons provided.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#hex-function">hex</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns a hexadecimal json by converting each byte of each character in the input json to two hexadecimal digits.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#length-function">length</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns the length of the input json.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#lower-function">lower</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Converts the capital letters in the input json to the equivalent simple letters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#regexp-function">regexp</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a boolean value based on the matchability of the input json and the given regular expression.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#repeat-function">repeat</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Repeats the input json for a specified number of times.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#replaceall-function">replaceAll</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Finds all the subjsons of the input json that matches with the given expression, and replaces them with the given replacement json.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#replacefirst-function">replaceFirst</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Finds the first subjson of the input json that matches with the given regular expression, and replaces itwith the given replacement json.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#reverse-function">reverse</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns the input json in the reverse order character-wise and json-wise.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#split-function">split</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Splits the  <code>input.json</code> into subjsons using the value parsed in the <code>split.json</code> and returns the subjson at the position specified in the <code>group.number</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#strcmp-function">strcmp</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Compares two jsons lexicographically and returns an integer value. If both jsons are equal, 0 is returned. If  the first json is lexicographically greater than the second json, a positive value is returned. If the first json is lexicographically greater than the second json, a negative value is returned.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#substr-function">substr</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a subjson of the input json by considering a subset or all of the following factors: starting index, length, regular expression, and regex group number.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#trim-function">trim</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a copy of the input json without the leading and trailing whitespace (if any).</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#unhex-function">unhex</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a json by converting the hexadecimal characters in the input json.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#upper-function">upper</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Converts the simple letters in the input json to the equivalent capital/block letters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-json/api/5.0.3/#tokenize-stream-processor">tokenize</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#stream-processor">Stream Processor</a>)*<br> <div style="padding-left: 1em;"><p>This function splits the input json into tokens using a given regular expression and returns the split tokens.</p></div>

## Dependencies 

There are no other dependencies needed for this extension. 

## Installation

For installing this extension on various siddhi execution environments refer Siddhi documentation section on <a target="_blank" href="https://siddhi.io/redirect/add-extensions.html">adding extensions</a>.

## Support and Contribution

* We encourage users to ask questions and get support via <a target="_blank" href="https://stackoverflow.com/questions/tagged/siddhi">StackOverflow</a>, make sure to add the `siddhi` tag to the issue for better response.

* If you find any issues related to the extension please report them on <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-json/issues">the issue tracker</a>.

* For production support and other contribution related information refer <a target="_blank" href="https://siddhi.io/community/">Siddhi Community</a> documentation.
