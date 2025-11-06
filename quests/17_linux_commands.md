PS C:\> mkdir commands


    디렉터리: C:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:45                commands


PS C:\> cd .\commands\
PS C:\commands> pwd

Path
----
C:\commands


PS C:\commands> ls
PS C:\commands> mkdir projects, logs


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:46                projects
d-----      2025-11-06   오후 5:46                logs


PS C:\commands> cd .\logs\
PS C:\commands\logs> pwd

Path
----
C:\commands\logs


PS C:\commands\logs> cd ../
PS C:\commands> mkdir daata, Reports, Backup


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:47                daata
d-----      2025-11-06   오후 5:47                Reports
d-----      2025-11-06   오후 5:47                Backup


PS C:\commands> ls


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:47                Backup
d-----      2025-11-06   오후 5:47                daata
d-----      2025-11-06   오후 5:46                logs
d-----      2025-11-06   오후 5:46                projects
d-----      2025-11-06   오후 5:47                Reports


PS C:\commands> cd .\Backup\
PS C:\commands\Backup> cd ../
PS C:\commands> ls


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:47                Backup
d-----      2025-11-06   오후 5:47                daata
d-----      2025-11-06   오후 5:46                logs
d-----      2025-11-06   오후 5:46                projects
d-----      2025-11-06   오후 5:47                Reports


PS C:\commands> mkdir test


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:48                test


PS C:\commands> ls


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:47                Backup
d-----      2025-11-06   오후 5:47                daata
d-----      2025-11-06   오후 5:46                logs
d-----      2025-11-06   오후 5:46                projects
d-----      2025-11-06   오후 5:47                Reports
d-----      2025-11-06   오후 5:48                test


PS C:\commands> mkdir Notes cd Notes
mkdir : 'cd' 인수를 허용하는 위치 매개 변수를 찾을 수 없습니다.
위치 줄:1 문자:1
+ mkdir Notes cd Notes
+ ~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [mkdir], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,mkdir

PS C:\commands> mkdir Notes


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:49                Notes


PS C:\commands> cd .\Notes\
PS C:\commands\Notes> pwd

Path
----
C:\commands\Notes


PS C:\commands\Notes> cd ../
PS C:\commands> mkdir Images, Videos, Docs


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:50                Images
d-----      2025-11-06   오후 5:50                Videos
d-----      2025-11-06   오후 5:50                Docs


PS C:\commands> ls


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:47                Backup
d-----      2025-11-06   오후 5:47                daata
d-----      2025-11-06   오후 5:50                Docs
d-----      2025-11-06   오후 5:50                Images
d-----      2025-11-06   오후 5:46                logs
d-----      2025-11-06   오후 5:49                Notes
d-----      2025-11-06   오후 5:46                projects
d-----      2025-11-06   오후 5:47                Reports
d-----      2025-11-06   오후 5:48                test
d-----      2025-11-06   오후 5:50                Videos


PS C:\commands> cd .\Docs\
PS C:\commands\Docs> cd ../
PS C:\commands> ls


    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:47                Backup
d-----      2025-11-06   오후 5:47                daata
d-----      2025-11-06   오후 5:50                Docs
d-----      2025-11-06   오후 5:50                Images
d-----      2025-11-06   오후 5:46                logs
d-----      2025-11-06   오후 5:49                Notes
d-----      2025-11-06   오후 5:46                projects
d-----      2025-11-06   오후 5:47                Reports
d-----      2025-11-06   오후 5:48                test
d-----      2025-11-06   오후 5:50                Videos


PS C:\commands>
