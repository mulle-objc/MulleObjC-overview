# NSContainer

The NSContainer protocols define the fundamental interfaces for collection classes in mulle-objc.

## Array Protocols

### NSArray <NSObject, NSFastEnumeration>

Required methods:
- [`-count`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+count+of+NSArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Returns number of objects
- [`-objectAtIndex:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+objectAtIndex+of+NSArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Retrieves object at index

### NSMutableArray <NSArray>

Required methods:
- [`-insertObject:atIndex:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+insertObject:atIndex+of+NSMutableArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Inserts object at index
- [`-removeObjectAtIndex:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+removeObjectAtIndex+of+NSMutableArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Removes object at index
- [`-addObject:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+addObject+of+NSMutableArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Appends object
- [`-removeLastObject`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+removeLastObject+of+NSMutableArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Removes last object
- [`-removeAllObjects`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+removeAllObjects+of+NSMutableArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Clears array
- [`-replaceObjectAtIndex:withObject:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+replaceObjectAtIndex:withObject+of+NSMutableArray+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Replaces object at index

## Dictionary Protocols

### NSDictionary <NSObject, NSFastEnumeration>

Required methods:
- [`-count`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+count+of+NSDictionary+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Returns number of entries
- [`-objectForKey:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+objectForKey+of+NSDictionary+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Retrieves value for key (key must conform to NSObject and MulleObjCImmutableCopying)

### NSMutableDictionary <NSDictionary>

Required methods:
- [`-setObject:forKey:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+setObject:forKey+of+NSMutableDictionary+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Associates object with key
- [`-removeObjectForKey:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+removeObjectForKey+of+NSMutableDictionary+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Removes entry for key
- [`-removeAllObjects`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+removeAllObjects+of+NSMutableDictionary+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Clears dictionary

## Set Protocols

### NSSet <NSObject, NSFastEnumeration>

Required methods:
- [`-count`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+count+of+NSSet+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Returns number of objects
- [`-member:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+member+of+NSSet+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Tests for object membership

### NSMutableSet <NSSet>

Required methods:
- [`-addObject:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+addObject+of+NSMutableSet+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Adds object to set
- [`-removeObject:`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+removeObject+of+NSMutableSet+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Removes object from set
- [`-removeAllObjects`](https://www.perplexity.ai/search?q=Please+create+some+detailed+API+documentation+for+the+method+removeAllObjects+of+NSMutableSet+of+the+MulleObjC+project+https://github.com/mulle-objc/MulleObjC.+You+will+find+source+code+probably+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.m+and+the+header+at+https://raw.githubusercontent.com/mulle-objc/MulleObjC/refs/heads/master/src/protocol/NSContainer.h+and+there+may+also+be+tests+for+it+in+the+test/+folder) - Clears set

Note: All container protocols require NSFastEnumeration for iteration. Dictionary keys must conform to both NSObject and MulleObjCImmutableCopying.
