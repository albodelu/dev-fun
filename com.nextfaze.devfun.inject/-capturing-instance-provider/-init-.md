[gh-pages](../../index.md) / [com.nextfaze.devfun.inject](../index.md) / [CapturingInstanceProvider](index.md) / [&lt;init&gt;](.)

# &lt;init&gt;

`CapturingInstanceProvider(instanceClass: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>, instance: () -> T?)`

An instance provider that requests an instance of a class from a captured lambda.

Be aware of leaks! The lambda could implicitly hold a local `this` reference.

**See Also**

[captureInstance](../capture-instance.md)
