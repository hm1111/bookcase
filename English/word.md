You can use generics to reduce code **duplication**.
**duplication** - n，重复，冗余。<br>
Dart generic types are **reified**, which means that they carry their type information around at runtime.
**reified** - adj，具体化的，reify。<br>
When implementing a generic type, you might want to limit the types that can be provided as arguments, so that the argument must be a subtype of a **particular** type. You can do this using extends.
**particular** - adj，特别的。<br>
You can also call an instance of a Dart class **as if** it were a function. 
**as if** - 好像...一样。<br>
Although Effective Dart recommends type annotations for public APIs, the function still works if you **omit** the types.
**omit** - 忽略