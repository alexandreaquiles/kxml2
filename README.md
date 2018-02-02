# kxml2

## Changes in this fork

- Using Java 1.6 as target
- Using newline instead of comma as implementation separator in META-INF/services/org.xmlpull.v1.XmlPullParserFactory
- Mavenized

To build a fat JAR with the `kxml` implementation and the `xmlpull` API, run:

```
mvn package
```

The generated fat JAR will be: `target/kxml2-2.5.1-SNAPSHOT-jar-with-dependencies.jar`

You should have `xmlpull-1.1.3.4c-SNAPSHOT.jar` in your Maven repo.
Please, see: https://github.com/alexandreaquiles/xmlpull-api-v1



