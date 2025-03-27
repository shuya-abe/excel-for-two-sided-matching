# excel-for-two-sided-matching

This repository provides an Excel program for conducting two-sided matching experiments in experimental economics.

## Overview

This Excel program solves two-sided matching problems.

## Features

*   Compute a matching with the worker-proposing DA algorithm.
*   Compute a matching with the division-proposing DA algorithm.
*   Compute a matching with the worker-proposing Boston mechanism.
*   Examine efficiency of a matching.

## Usage

1.  Set the numbers of workers and divisions in the VBA window.
2.  Input numerical data on workers' preferences, divisions' evaluation, and quotas in the `man` sheet, the `group` sheet, and the `conf` sheet, respectively.
3.  Open the `result` sheet.
4.  Choose one button out of three in the result sheet to run the desired algorithm.
5.  View computation results in the `result` sheet.
6.  Click on the `eval` button for examining efficiency of a matching shown in the `result` sheet.
7.  Open the `analyze` sheet and view the examination result.

## Manual

For detailed usage instructions, please refer to the following manual.

*   [manualEnSh.pdf](https://github.com/shuya-abe/excel-for-two-sided-matching/blob/main/manualEnSh.pdf)

## Author

*   Shuya Abe
*   [Naoki Watanabe](https://naoki-watanabe50.github.io/index.html)