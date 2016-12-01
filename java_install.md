1) Add new java alternative: <link> <name> <path> <priority>
update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk1.8.0_112/bin/java 0
update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk1.8.0_112/bin/javac 0
2) Change default java
update-alternatives --config java
3) Remove alternative
update-alternatives --remove java /usr/lib/jvm/jdk1.8.0_112/bin/java
