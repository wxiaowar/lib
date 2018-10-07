libunwind: https://github.com/pathscale/libunwind.git
yum install autoconf automake libtool


   target_link_libraries (gamed game logic event common net protobuf log4cxx config++ tokyotyrant pthread m bson-1.0 mongoc-1.0 rt
+    target_link_libraries (worldd world logic event common net protobuf log4cxx config++ tokyotyrant pthread m bson-1.0 mongoc-1.0
+

Install cmake
Install libunwind/gperftools
Install configure_env
Modify cmakelist.txt

./buildmakelist
./switch_to_debug.sh
./make -j 4
