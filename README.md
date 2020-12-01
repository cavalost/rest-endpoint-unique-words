# Unique words project

## Description

The application has two REST endpoints: 

* The first takes a string parameter and responds with the reversed string.
* The second counts the unique words in a string. The endpoint should take a single string input parameter and 
 return a JSON object of key-value pairs. Each key should be a unique word from the input string. The value should be
 the number of times that word occurs in the input string. The order of the keys match the order that the words 
 first occur in the input string.

## Factsheet

| **Category**              | **Value**                                 |
| ------------------------- | ---------------------------------------- |
| **Contact**               | @cavalost 
| **Language / Framework**  | Java / Spring Boot / Gradle

## Requirements

* JDK (version 8 or above)
* Gradle

## Project setup

* Start the application: `gradlew bootRun`
* To run the tests, use `gradlew test`

### Example

For the input string:

`when you finish you can check your results`

The output is:

```json
{
  "when": 1,
  "you": 2,
  "finish": 1,
  "can": 1,
  "check": 1,
  "your": 1,
  "results": 1
}
```
