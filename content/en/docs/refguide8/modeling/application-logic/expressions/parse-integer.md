---
title: "Parse Integer"
url: /refguide8/parse-integer/
weight: 140
description: "Describes the function for parsing integer from strings in Mendix."
tags: ["studio pro", "expressions", "parse", "integer"]
---

{{% alert color="info" %}}
<img src="/attachments/china.png" class="d-inline-block" /> For the Simplified Chinese translation, click [中文译文](https://cdn.mendix.tencent-cloud.com/documentation/refguide8/parse-integer.pdf).
{{% /alert %}}

## 1 Introduction

This document describes the function that converts a string to a value that is of data type [Integer/Long](/refguide8/data-types/#integer-long).

## 2 parseInteger

Takes a string and parses it to an Integer/Long.

### 2.1 Input Parameters

The input parameters are described in the table below:

| Value                        | Type         |
| ---------------------------- | ------------ |
| The string to parse          | String       |
| Default value **(optional)** | Integer/Long |

{{% alert color="info" %}}
A default value can be specified to handle parsing errors. If no default value is provided, an error will occur if the string is not a number or if the parsed value is not within the range of valid values for an Integer/Long. The range of valid values for an Integer/Long can be found in this [table of supported data types](/refguide8/data-types/#supported-data-types).
{{% /alert %}}

### 2.2 Output

The output is described in the table below:

| Value                                                        | Type    |
| ------------------------------------------------------------ | ------- |
| An Integer/Long if it is possible to parse it from the string. If the string cannot be parsed to an Integer/Long, the default value will be returned. If no default value is provided, an error will occur. | Integer/Long |

### 2.3 Examples

The examples below illustrate which value the expression returns:

* If you use the following input:

    ```java
    parseInteger('42')
    ```

    the output is:

    ```java
    42
    ```

* If you use the following input:

    ```java
    parseInteger('not_an_integer', 42)
    ```

    the output is:

    ```java
    42
    ```
