# TestSpringBoot
Spring Boot provide to Tomcat and build WAR file

Spring Boot は、Tomcat組み込みだから、既に稼働してるTomcatに載せたいような場合は、組み込みされてるTomcatを別けないといけない。
それには、
・Pom.xmlの編集
・Spring Bootのエントリポイントのクラスの修正が必要
が最低限必要。（Gradleのやり方は分からんっす）

