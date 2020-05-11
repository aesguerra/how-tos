# how-tos

## How to install JAVA 8
Using root or sudoer account

### Update yum
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

### Link java home to /usr/local
```
ln -snf /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.191.b12-1.el7_6.x86_64/jre /usr/local/jdk1.8
```

### Setting Java Path on your Environment
```
vi .bashrc

export JAVA_HOME=/usr/local/jdk1.8

# refresh file
. .bashrc

# echo java home
echo $JAVA_HOME
```

