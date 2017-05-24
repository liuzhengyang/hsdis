# hsdis
Hotspot disassembler extracted from openjdk.

# Usage
## OSX
```
git clone https://github.com/liuzhengyang/hsdis
cd hsdis
tar -zxvf binutils-2.26.tar.gz
make BINUTILS=binutils-2.26 ARCH=amd64
```
And then copy hsdis build file to the target folder in JDK.

```
sudo cp build/macosx-amd64/hsdis-amd64.dylib /Library/Java/JavaVirtualMachines/jdk1.8.0_131.jdk/Contents/Home/jre/lib/server/
```
After that, you could add `-XX:+UnlockDiagnosticVMOptions -XX:+PrintAssembly ` in the Java Run Param to see the program's assebmle code.

