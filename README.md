Limited-Resource-Estimated-NK-Model
===================================

This program simulates a limited-resource model of germinal center selection in an estimated NK fitness landscape.  To run, open a command prompt window and go to the directory ..\NK Fitness Model\bin\Release and use the command '"NK Fitness Model.exe" -p youroutputpath'.  The following additional options are available:

-h: heavy chain lenght (default=110)
-l: light chain length (default=110)
-k: nk model k parameter (default=0)
-d: seeding (default=1 for seeding on, use 0 for seeding off) 
-s: initial seed rate if d=1 or initial cell count if d=0 (default=10)
-q: initial quantile (default=1E-4)
-c: initial resource quantity (default=1E5)
-m: mutation rate (default=1.5E-3)
-o: output file name (default="test")
-a: lambda/selection strength (default=100)
-e: end step (default=1000)
-t: terminal capacity (default=0)
-r: detailed cell report (default=1 creates report, use 0 to skip detailed report)
-w: random walk mode (default=0 to use limited resource selection, use 1 to turn selection off)
