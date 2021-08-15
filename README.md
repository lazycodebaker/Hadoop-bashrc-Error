# Hadoop-bashrc-Error

If you are also getting error in terminal about HADOOP_OPTS then do the following ::

1. Open Terminal and type  => sudo nano .bashrc
2. Then replace the last line in Hadoop Variables With ::
    export HADOOP_OPTS="$HADOOP_OPTS-Djava.library.path=$HADOOP_HOME/lib/nativ"
    
3.Then Save
4.Configure the .bashrc with source .bashrc
