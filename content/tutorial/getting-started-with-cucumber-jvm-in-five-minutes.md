---
title: Getting Started with Cucumber-JVM
menu: main
---
This page provides a brief introduction to get you started with Cucumber-JVM.

You will need the following:

* Java SE *<link
to download>*

* Maven *<link
to download>*

* Cucumber-JVM *<link
to download>*

* An IDE editor, for example IntelliJ  IDEA (which will be used in this
introduction) *<link to download> *

* *(cucumber
plug-in for every IDE?)*

# Concepts

Cucumber helps you define what your product should do, not how it should do it.

Definitions for terms can be found under the Reference section.

# Overview

The following diagram illustrates the structure when using Cucumber:

<Alsak's illustration of 
* Maven
* JUnit
* Cucumber
* Feature files
* Step definitions
* The application>


# Creating a Project

For this introductions, we will use the shouty project, [which is available from GitHub](https://slack-redir.net/link?url=http%3A%2F%2Fgithub.com%2Fcucumber-ltd%2Fshouty.java&v=3). 

## Project Structure

This will describe the structure of the project 

## Creating a Package

This will describe how to create the package for your first
Cucumber files

### Using POM.XML

This will describe the project object model (POM) and how to
edit the POM.XML file

### Adding Dependencies

This will describe adding dependencies to your package

# Testing the Setup (Maven)

This will describe running mvn clean test to ensure the structure
is valid 

# Creating a Clean Build

This will describe how to create a clean build from which to
start

# Specifying Behaviour (Cucumber-JVM)

This will introduce the location, hierarchy and structure of
the feature file

## Defining the Feature Directory

This will describe the feature directory and its creation

## Creating a Feature

This will describe how to write a feature 

*<if required, can
include information on adding Background, but I suggest that is left for the
next stage>*

## Creating a Scenario

This will describe how to write a scenario

*<if required, can
include information on adding code before and after a scenario or using
scenario outlines, but I suggest that is left for the next stage>*

## Running a Feature

This will describe how to run the feature file using mvn clean
test and what to expect

## Defining Steps

This will describe how to add steps from the three amigo discussions,
user stories or acceptance criteria

### Given/When/Then

This will describe the definition of each step and ensuring
correct coverage

*<if required, can
include information on using data tables, expressions and tags, but I suggest
that is left for the next stage>*

## Running the Tests (Maven)

This will describe how to run the Cucumber project in Maven
and explain the possible results, issues and resolutions

### Passed Tests

This will describe what it means if tests pass and what to
do next

### Failed Tests

This will describe what it means if tests fail and what to
do next

### Pending Tests

This will describe what it means if tests are not run and
what to do next

### Skipped Tests

This will describe when tests will be skipped and what to do
next

### Snippets for Missing Steps

This will describe the snippets produced by cucumber for
pending tests and how to use them

*<if required, can
include information on writing glue code, but I suggest that is left for the
next stage>*






