~ $ cd Commands/ && pwd
/home/node/Commands
~/Commands $ mkdir test && ls -l
total 4
-rw-r--r--    1 node     node             0 Nov  7 03:17 temp_01.txt
drwxr-sr-x    2 node     node          4096 Nov  7 03:46 test
~/Commands $ mkdir notes && cd notes && pwd
/home/node/Commands/notes
~/Commands/notes $ cd ../ && mkdir -p images videos docs && ls -l
total 20
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 docs
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 images
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 notes
-rw-r--r--    1 node     node             0 Nov  7 03:17 temp_01.txt
drwxr-sr-x    2 node     node          4096 Nov  7 03:46 test
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 videos
~/Commands $ cd docs/../ && ls -l
total 20
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 docs
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 images
drwxr-sr-x    2 node     node          4096 Nov  7 03:47 notes
-rw-r--r--    1 node     node             0 Nov  7 03:17 temp_01.txt
drwxr-sr-x    2 node     node          4096 Nov  7 03:46 test
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 videos
~/Commands $ 
