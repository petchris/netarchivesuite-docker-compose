Preconditions
Build netarchivesuite from netarchivesuite/netarchivesuite with maven and rename the files to NetarchiveSuite-<version>.zip and NetarchiveSuite-heritrix3-bundler-<version>.zip. Next copy the two files to the "nasapp" directory of the netarchivesuite-docker-compose


Running 

docker-compose build
docker-compose up

will create a complete dockerised NetarchiveSuite with GUI on localhost:8078 and viewerproxy on localhost:8878

In addition, a java debugger can be attached to the heritrix processes on port 8500 (Focused) or 8501 (Snapshot).
