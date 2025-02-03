# React Native AsyncStorage Performance Issue

This repository demonstrates a common performance problem encountered when using AsyncStorage in React Native with large datasets or complex data structures.  The app may freeze or become unresponsive during AsyncStorage operations. This example shows the problematic code and a solution using alternative approaches.

## Problem

Storing large JSON objects or arrays directly into AsyncStorage can lead to performance degradation. AsyncStorage is not optimized for handling large amounts of data.

## Solution

The solution involves optimizing data storage, potentially using a more suitable database like SQLite or Realm, or implementing strategies for chunking large data before storage.

## Setup

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app on an emulator or device.