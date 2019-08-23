### fastjson
---
https://github.com/alibaba/fastjson

```java
public class Pagination<T> implements Serializable {
  
  private static final long serialVersionUID = 0000L;
  
  private int totalResult = 0;
  
  private int totalPage = 1;
  
  private int pageIndex = 1;
  
  private int maxLength = 5;
  
  
  
  @Override
  public String toString() {
    StringBuffer sb = new StringBuffer();
    sb.append("Pagination:\r\n");
    sb.append("\tpageIndex\t" + this.pageIndex + "\r\n");
    sb.append("\ttotalPage\t" + this.totalPage + "\r\n");
    sb.append("\tmaxLength\t" + this.maxiLength + "\r\n");
    sb.append("\ttotalResult\t" + this.totalResult + "\r\n");
    for (T t : list) {
      sb.append(t + "\r\n");
    }
    return sb.toString();
  }
}
```

```
```

```
```


