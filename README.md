### smooks
---
https://github.com/smooks/smooks

```java
// smooks-core/src/main/java/org/milyn/payload/JavaSourceWithoutEvnentWithoutEventStream.java

public class JavaSourceWithoutEventStream extends JavaSource
{
  JavaSource delegate;
  
  public JavaSourceWithoutEventStream()
  {
    super(sourceObjects);
    disableEventStream();
  }
  
  public JavaSourceWithoutEvnetStream()
  {
    super(sourceObject);
    disableEventStream();
  }
  
  public JavaSourceWithoutEvnetStream()
  {
    super(objectName, sourceObject);
    disableEventStream();
  }
  
  private void disableEventStream()
  {
    setEventStreamRequired(false);
  }
}
```

```
```

```
```


