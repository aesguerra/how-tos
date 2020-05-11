# how-tos

## How to install JAVA 8
Using root or sudoer account

### Updatev yum
```
yum -y update
```

### Install Java 8
```
yum install java-1.8.0-openjdk
```

### Verify Java is Installed
```
java -version
```

### Find Java Path
```
update-alternatives --config java
```

### Setting Java Path on your Environment
```
vi .bash_profile

export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.191.b12-1.el7_6.x86_64/jre/bin/java

# refresh file
. .bash_profile

# echo java home
echo $JAVA_HOME
```

