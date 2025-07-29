# C++ Logging System

A lightweight and modular logging system for C++ projects. This logger supports separate functions for different log levels — making it easy to organize and filter logs.

## Features

- Separate functions for each log type:
  - `info_log()` for informational messages
  - `warning_log()` for warnings
  - `error_log()` for error messages
- Timestamps included in each log
- Easy to integrate into any C++ project
- Output to a specified log file

## Example Usage

```cpp
#include "Logger.h"  // Replace with your actual header

Logger logger("log.txt"); // Create a logger with a log file path

logger.info_log("Application started successfully.");
logger.warning_log("Low memory warning.");
logger.error_log("File not found.");
