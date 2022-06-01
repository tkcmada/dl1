
```
mvn dependency:resolve
cp -nrp /workspace/m2-repository/* .m2/repository/
find .m2/repository -type f -and -not -name "*.jar" -and -not -name "*.pom"  -and -not -name "*.xml" | xargs rm -v

```