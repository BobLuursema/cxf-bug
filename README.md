# cxf-bug

```sh
git clone https://github.com/BobLuursema/cxf-bug.git
cd cxf-bug
mvn generate-sources
```

Observe in the target folder that an invalid package name is generated for GetCase1.java and GetCaseInterface1.java, but valid package names for the other objects.
