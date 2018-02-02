# kxml2

## Changes in this fork

- Using Java 1.6 as target
- Using newline instead of comma as implementation separator in META-INF/services/org.xmlpull.v1.XmlPullParserFactory

To build a fat JAR with the `kxml` implementation and the `xmlpull` API, run:

```
ant build
```

The generated fat JAR will be: `dist/kxml2-2.5.0.jar`

You should have `xmlpull-1.1.3.4c-SNAPSHOT.jar` in your Maven repo.
Please, see: https://github.com/alexandreaquiles/xmlpull-api-v1



