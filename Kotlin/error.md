# linkage error
```
Error: LinkageError occurred while loading main class calculator.ApplicationKt
	java.lang.UnsupportedClassVersionError: calculator/ApplicationKt has been compiled by a more recent version of the Java Runtime (class file version 65.0), this version of the Java Runtime only recognizes class file versions up to 61.0
```
JRM은 Java21이지만, JRE는 java17 또는 그 이전의 버전이기 때문에 java project의 설정을 변경하면 해결되는 문제였다.