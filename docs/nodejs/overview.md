# Overview

## What is Node.js?

* Node.js is open-source 
* It is Cross-platform (Windows, Linux, Unix, Mac OS X, etc.)
* It is a JavaScript runtime environment

## Why use Node.js?

A common task for a web server can be to open a file on the server and return the content to the client.

Here is how **PHP** or **ASP** handles a file request:

1. Sends the task to the computer's file system.
2. Waits while the file system opens and reads the file.
3. Returns the content to the client.
4. Ready to handle the next request.

Here is how **Node.js** handles a file request:

1. Sends the task to the computer's file system.
2. Ready to handle the next request.
3. When the file system has opened and read the file, the server returns the content to the client.

Node.js removes the wait period, and continues with the next request.

Node.js runs single-threaded, it is non-blocking, asynchronous programming, which is very memory efficient.

## What can Node.js do?

* Node.js can generate dynamic page content
* Node.js can create, open, read, write, delete, and close files on the server
* Node.js can collect form data
* Node.js can add, delete, modify data in your database

## What are Node.js files?

* Node.js files contain tasks that will be executed on certain events
* A typical event is someone trying to access a port on the server
* Node.js files must be initiated on the server before having any effect
* Node.js files have extension ".js"