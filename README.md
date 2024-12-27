# Unhandled Undefined Value in JavaScript Function

This repository demonstrates a common JavaScript error where a function doesn't handle `undefined` values correctly, leading to a `TypeError`. The original code lacks a check for `undefined`, causing an error when an `undefined` value is passed. The solution provides a corrected version that handles both `null` and `undefined` gracefully, preventing unexpected errors.

## Bug
The bug lies in the `foo` function. It correctly handles `null` values but fails when passed an `undefined` value.  Attempting to access `.length` of `undefined` throws a `TypeError`.

## Solution
The solution adds a check for both `null` and `undefined` before attempting to access the `.length` property, preventing the `TypeError` and ensuring the function handles both cases.