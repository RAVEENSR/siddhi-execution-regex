Siddhi Execution Regex
======================================

  [![Jenkins Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-regex/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-regex/)
  [![GitHub (pre-)Release](https://img.shields.io/github/release/siddhi-io/siddhi-execution-regex/all.svg)](https://github.com/siddhi-io/siddhi-execution-regex/releases)
  [![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/siddhi-io/siddhi-execution-regex.svg)](https://github.com/siddhi-io/siddhi-execution-regex/releases)
  [![GitHub Open Issues](https://img.shields.io/github/issues-raw/siddhi-io/siddhi-execution-regex.svg)](https://github.com/siddhi-io/siddhi-execution-regex/issues)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/siddhi-io/siddhi-execution-regex.svg)](https://github.com/siddhi-io/siddhi-execution-regex/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The **siddhi-execution-regex extension** is a <a target="_blank" href="https://siddhi.io/">Siddhi</a> extension that provides basic regex handling capabilities such as concat, length, replace all, etc.

For information on <a target="_blank" href="https://siddhi.io/">Siddhi</a> and it's features refer <a target="_blank" href="https://siddhi.io/redirect/docs.html">Siddhi Documentation</a>. 

## Download

* Versions 5.x and above with group id `io.siddhi.extension.*` from <a target="_blank" href="https://mvnrepository.com/artifact/io.siddhi.extension.execution.regex/siddhi-execution-regex/">here</a>.
* Versions 4.x and lower with group id `org.wso2.extension.siddhi.*` from <a target="_blank" href="https://mvnrepository.com/artifact/org.wso2.extension.siddhi.execution.regex/siddhi-execution-regex">here</a>.

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3">5.0.3</a>.

## Features

* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#groupconcat-aggregate-function">groupConcat</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#aggregate-function">Aggregate Function</a>)*<br> <div style="padding-left: 1em;"><p>This function aggregates the received events by concatenating the keys in those events using a separator, e.g.,a comma (,) or a hyphen (-), and returns the concatenated key regex.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#charat-function">charAt</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the 'char' value that is present at the given index position. of the input regex.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#coalesce-function">coalesce</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p> This returns the first input parameter value of the given argument, that is not null.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#concat-function">concat</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns a regex value that is obtained as a result of concatenating two or more input regex values.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#contains-function">contains</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns <code>true</code> if the<code>input.regex</code> contains the specified sequence of char values in the <code>search.regex</code>. </p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#equalsignorecase-function">equalsIgnoreCase</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This returns a boolean value by comparing two regexs lexicographically without considering the letter case.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#filltemplate-function">fillTemplate</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This extension replaces the templated positions that are marked with an index value in a specified template with the regexs provided.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#hex-function">hex</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns a hexadecimal regex by converting each byte of each character in the input regex to two hexadecimal digits.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#length-function">length</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns the length of the input regex.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#lower-function">lower</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Converts the capital letters in the input regex to the equivalent simple letters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#regexp-function">regexp</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a boolean value based on the matchability of the input regex and the given regular expression.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#repeat-function">repeat</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Repeats the input regex for a specified number of times.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#replaceall-function">replaceAll</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Finds all the subregexs of the input regex that matches with the given expression, and replaces them with the given replacement regex.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#replacefirst-function">replaceFirst</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Finds the first subregex of the input regex that matches with the given regular expression, and replaces itwith the given replacement regex.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#reverse-function">reverse</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns the input regex in the reverse order character-wise and regex-wise.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#split-function">split</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Splits the  <code>input.regex</code> into subregexs using the value parsed in the <code>split.regex</code> and returns the subregex at the position specified in the <code>group.number</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#strcmp-function">strcmp</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Compares two regexs lexicographically and returns an integer value. If both regexs are equal, 0 is returned. If  the first regex is lexicographically greater than the second regex, a positive value is returned. If the first regex is lexicographically greater than the second regex, a negative value is returned.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#substr-function">substr</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a subregex of the input regex by considering a subset or all of the following factors: starting index, length, regular expression, and regex group number.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#trim-function">trim</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a copy of the input regex without the leading and trailing whitespace (if any).</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#unhex-function">unhex</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Returns a regex by converting the hexadecimal characters in the input regex.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#upper-function">upper</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>Converts the simple letters in the input regex to the equivalent capital/block letters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-regex/api/5.0.3/#tokenize-stream-processor">tokenize</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#stream-processor">Stream Processor</a>)*<br> <div style="padding-left: 1em;"><p>This function splits the input regex into tokens using a given regular expression and returns the split tokens.</p></div>

## Dependencies 

There are no other dependencies needed for this extension. 

## Installation

For installing this extension on various siddhi execution environments refer Siddhi documentation section on <a target="_blank" href="https://siddhi.io/redirect/add-extensions.html">adding extensions</a>.

## Support and Contribution

* We encourage users to ask questions and get support via <a target="_blank" href="https://stackoverflow.com/questions/tagged/siddhi">StackOverflow</a>, make sure to add the `siddhi` tag to the issue for better response.

* If you find any issues related to the extension please report them on <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-regex/issues">the issue tracker</a>.

* For production support and other contribution related information refer <a target="_blank" href="https://siddhi.io/community/">Siddhi Community</a> documentation.
