Waarp Shaded external projects
==============================

This project hosts dependencies needed for Waarp to run and compile in the context of JDK6.

- Selenium for Java: this includes all jar needed for Selenium, including those for Java 8, encapsulated into a single jar for test only.

Tests are in JDK 8 and above in Waarp, while the main code is in Java 6 (for compatibility with old systems).
This jar includes all dependencies for Selenium, even those already in Waarp but in different versions to fit Java 6 compatibility.

- Netty-Http: https://github.com/cdapio/netty-http

This package is used by Waarp to provide REST API using Netty and Netty-Http in Java 6 environment. Netty-Http is build for Java 8 and above, so this minimal fork to allow Java6 compatibility.

This was submitted to the main project from CDAPIO, but still not validated as a new branch for Java 6 compatibility, so this fork.

