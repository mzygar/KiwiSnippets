# KiwiSnippets
Xcode snippets set for Kiwi BDD testing


# Instalation
Run `install.sh` or copy the `CodeSnippets` folder manually to `~/Library/Developer/Xcode/UserData/`


# Usage
You can browse the snippets in Xcode in Utilities (right)pane. If you have troubles finding it, press `ctrl-alt-cmd-2`. From this list you can also edit the completion shortcuts to fit you preference.

This set contains following snippets:

###kspec###

Creates new *spec* template
```
  #import "Kiwi.h"
  #impor "<#class#>.h"
  SPEC_BEGIN(<#class#>Spec)

  describe(@"<#description#>", ^{

  });

  SPEC_END

```

###kdesc###

Creates new *descirbe* block

```
describe(@"<#descibe#>", ^{
    <#code#>
});
```

###kcon###

Creates new *context* block

```
 context(@"<#context#>", ^{
        
    });
  ```
  
###kit###

Creates new *it* block (test case)

```
it(@"should <#something#>", ^{
    <#code#>
});
```

###kbef###

Creates new *beforeEach* block

```
beforeEach(^{
    <#code#>
    });
```

###kaft###

Creates new *afterEach* block

```
 afterEach(^{
     <#code#>
    });
    
```
