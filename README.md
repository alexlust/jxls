# JXLS

[![Java CI with Maven](https://github.com/jxlsteam/jxls/workflows/Java%20CI%20with%20Maven/badge.svg)](https://github.com/jxlsteam/jxls/actions?query=workflow%3A%22Java+CI+with+Maven%22) [![codecov](https://codecov.io/gh/jxlsteam/jxls/branch/master/graph/badge.svg)](https://codecov.io/gh/jxlsteam/jxls)

## News

New release 2.10.0 RC2 comes with support for JSR310, multi-line SQL, formula recalculation etc. Thank you for the contributions.

JXLS has moved from BitBucket to Github. Please use the Github issue tracker for bugs and the Github [Discussions](https://github.com/jxlsteam/jxls/discussions/categories/q-a) for questions.

## Overview

JXLS (see [homepage](http://jxls.sourceforge.net/)) is a small and simple to use Java library for Excel report generation using Excel template files.

JXLS abstracts Excel generation from underlying Java-to-Excel low-level processing library.
JXLS uses a special markup in Excel templates to define output formatting and data layout.

## How to use

**Maven**

    <dependency>
        <groupId>org.jxls</groupId>
        <artifactId>jxls-poi</artifactId>
        <version>2.10.0-rc2</version>
    </dependency>

**Gradle**

    implementation 'org.jxls:jxls-poi:2.10.0-rc2'


## Contributing

[see Contributing guide](CONTRIBUTING.md)
