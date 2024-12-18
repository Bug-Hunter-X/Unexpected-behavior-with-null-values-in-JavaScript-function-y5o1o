# Unexpected behavior with null values in JavaScript function

This repository demonstrates a common JavaScript error related to handling null values in functions. The `foo` function is intended to increment a numerical input. However, it exhibits unexpected behavior when encountering `null`.

## Bug Description

The `foo` function incorrectly handles null values. Instead of returning 0 as intended, it attempts to perform arithmetic on `null`, leading to unexpected results.

## Bug Solution

The solution adds explicit null checks to ensure the function gracefully handles null values, returning 0 when x is null and proceeds with incrementation otherwise.