## TDD

- [Bootiful TDD by Josh Long @ Spring I/O 2019](https://www.youtube.com/watch?v=E87XhgYBM-Y)

## Reactive Spring

- [Reactive Spring. Josh Long, Pivotal](https://www.youtube.com/watch?v=Z5q-CXbvM1E)

- [Spring tour - Spring tips and Reactive Spring Day 1 - with Josh Long](https://www.youtube.com/watch?v=_LR0Cxnn-kw)

## Logging

### `Logback` & `Log4j2` 

- [Get Log Output in JSON](https://www.baeldung.com/java-log-json-output)

### Logstash

- [Logstash Logback Encoder](https://github.com/logfellow/logstash-logback-encoder) allows easy key value logging message. Usage:

    ```java
    import static net.logstash.logback.argument.StructuredArguments.kv;

    logger.info("log message", kv("name", "value"));
    ```
