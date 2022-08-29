Installation
============

Installation Pre-requisites
---------------------------

Below are the Pre-requisites before installing Fire::

    JDK 1.8+ installed on the machine

    java and jar have to be in the PATH

    If running on an Apache Spark cluster, Apache Spark 2.3+ is needed on the cluster.

    8GB+ of RAM available on the machine.


With which user should Fire be installed
----------------------------------------

If Fire needs to be connected with an Apache Spark cluster the below is needed:

* Fire needs to be installed as a user which can ``impersonate other users``. Impersonation for this user has to be set up in ``HDFS configs``.
* If you disable impersonation in Fire, then the user with which Fire is installed needs to be able to submit jobs to the cluster.

More Details are available here : https://www.sparkflows.io/connecting-sparkflows-with-spark-cl

