## Download JAVA
Oracle [Download](https://www.oracle.com/java/technologies/java-se-glance.html)

- Minecraft Server Start Batch Script With Code Examples

Replace your launch.bat file's content with this. Go to %ProgramFiles%\Java\ and see what java 16's folder is called, replace <java16foldername> with that.
```bash
@Echo OFF
SET BINDIR=%~dp0
CD /C "%BINDIR%"
"%ProgramFiles%\Java\<java16foldername>\bin\java.exe" -Xmx8G -Xms8G -jar server.jar nogui
PAUSE
```
```bash
"C:\Program Files\Java\jre1.8.0_291\bin\java.exe" -Xmx1024M -Xms512M -jar spigot-1.12.2.jar
PAUSE
```
- without selecting the java version
```bash
@echo off
title My MC server
java -Xms2G -Xmx32G -jar paper-1.17.1-90.jar nogui
```
