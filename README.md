
# Hello Eclipse World

![Eclipse Tutorial](Hello-eclipse-world-tutorial.png)

## Project files
```
[~/workspace/HelloEclipseWorld] # ls -aR .
.:
.  ..  .classpath  .git  .gitignore  Hello-eclipse-world-tutorial.png  .project  README.md  .settings  src

./.git:
.  ..  branches  COMMIT_EDITMSG  config  description  FETCH_HEAD  HEAD  hooks  index  info  logs  objects  ORIG_HEAD  packed-refs  refs

./.git/branches:
.  ..

...

./.settings:
.  ..  org.eclipse.jdt.core.prefs

./src:
.  ..  HelloWorld.java

```

## Inspect .classpath and .settings/org.eclipse.jdt.core.prefs
```
[~/workspace/HelloEclipseWorld] # cat .classpath 
<?xml version="1.0" encoding="UTF-8"?>
<classpath>
	<classpathentry kind="src" path="src"/>
	<classpathentry kind="con" path="org.eclipse.jdt.launching.JRE_CONTAINER/org.eclipse.jdt.internal.debug.ui.launcher.StandardVMType/OSGi%Minimum-1.2"/>
	<classpathentry kind="output" path="bin"/>
</classpath>
[~/workspace/HelloEclipseWorld] # cat .settings/org.eclipse.jdt.core.prefs 
eclipse.preferences.version=1
org.eclipse.jdt.core.compiler.codegen.inlineJsrBytecode=disabled
org.eclipse.jdt.core.compiler.codegen.targetPlatform=1.2
org.eclipse.jdt.core.compiler.codegen.unusedLocal=preserve
org.eclipse.jdt.core.compiler.compliance=1.4
org.eclipse.jdt.core.compiler.debug.lineNumber=generate
org.eclipse.jdt.core.compiler.debug.localVariable=generate
org.eclipse.jdt.core.compiler.debug.sourceFile=generate
org.eclipse.jdt.core.compiler.problem.assertIdentifier=warning
org.eclipse.jdt.core.compiler.problem.enumIdentifier=warning
org.eclipse.jdt.core.compiler.source=1.3
cat .settings/org.eclipse.jdt.core.prefs 
eclipse.preferences.version=1
org.eclipse.jdt.core.compiler.codegen.inlineJsrBytecode=disabled
org.eclipse.jdt.core.compiler.codegen.targetPlatform=1.2
org.eclipse.jdt.core.compiler.codegen.unusedLocal=preserve
org.eclipse.jdt.core.compiler.compliance=1.4
org.eclipse.jdt.core.compiler.debug.lineNumber=generate
org.eclipse.jdt.core.compiler.debug.localVariable=generate
org.eclipse.jdt.core.compiler.debug.sourceFile=generate
org.eclipse.jdt.core.compiler.problem.assertIdentifier=warning
org.eclipse.jdt.core.compiler.problem.enumIdentifier=warning
org.eclipse.jdt.core.compiler.source=1.3
```