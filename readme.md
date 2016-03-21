## mysql
- command login: mysql -h host -u username -ppassword dbname

## bash
- one line while loop:

## network
- nethogs, a tool which can help find how much bandwidth is occupied by process
    - sudo nethogs interface
- sbt maven source is slow

        vim ~/.sbt/repo

        [repositories]                                                               
        local
        osc: http://maven.oschina.net/content/groups/public/
        typesafe: http://repo.typesafe.com/typesafe/ivy-releases/, [organization]/[module]/(scala_[scalaVersion]/)(sbt_[sbtVersion]/)[revision]/[type]s/[artifact](-[classifier]).[ext], bootOnly
        sonatype-oss-releases
        maven-central
        sonatype-oss-snapshots
        ~                         

## python
- numpy

## ssh
断点续传 rsync -P --rsh=ssh home.tar 192.168.205.34:/home/home.tar
