Reading from Big Query
============

Fire Insights has processor for reading from Big Query Tables.

1. Create a new workflow
++++++++++++++++++++++++++++++++

Create a new workflow or edit an existing one. This would take you to the workflow editor.

2. Create the ``Read BigQuery`` Node
++++++++++++++++++++++++++++++++

Search for the ``Read BigQuery`` Node, in the data connectors, drag and drop it to the workflow editor.

.. figure:: ../_assets/gcp/read-bigquery.png
   :alt: Read BigQuery Node
   :width: 40%
   
3. Configure the ``Read BigQuery`` Node
++++++++++++++++++++++++++++++++

Double click on the ``Read BigQuery`` Node, to configure the table connection. Once you've configured, make sure to click on the ``Refresh Schema`` button to fetch the schema. 


.. figure:: ../_assets/gcp/configure-bigquery.png
   :alt: Configure BigQuery Node
   :width: 40%
