iOS-MD5-SHA1
============
#### NSString分类，添加 MD5 和 SHA1方法

```objc
#import "NSString+Password.h"
```

```objc
NSString *yourPWD=@"YourPassword";
NSLog(@"Your password is %@ after encrypting by MD5",[yourPWD MD5]);
NSLog(@"Your password is %@ after encrypting by SHA1",[yourPWD SHA1]);
```
