tig4605246@tig4605246-tb /tmp/tmp.dJU1TCAzCb/gateway-ha 2025-02-04 23:47:19 CST
$ date "+%Y%m%d%H%M%S"
20250204235048
tig4605246@tig4605246-tb /tmp/tmp.dJU1TCAzCb/gateway-ha 2025-02-04 23:50:49 CST
$ cd gateway-ha-jar-with-dependencies/
tig4605246@tig4605246-tb /tmp/tmp.dJU1TCAzCb/gateway-ha/gateway-ha-jar-with-dependencies 2025-02-05 00:05:15 CST
$ jar cf ../gateway-ha-jar-with-dependencies.jar *

build.sh is a script to build the trino gateway jar file. I've made it use custom version of mina-core by untar jar and repack jar. See more details in build.sh.