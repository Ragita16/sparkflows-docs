Dashboard
=======================

Fire allows creating of the dashboard.

Fire allows to create new dataset using JDBC data type from MYSQL DB & then uses the datasets in creating charts & dashboard.

Creating Dashboard
--------------------

- For creating dashboard, create JDBC datasets if not available.

You can define a new dataset by clicking on the ``Create Dataset`` button on the Dataset page.

It will bring up the dialog box below. Select the format of the file for which the new dataset is being created.

.. figure:: ../../../_assets/tutorials/dataset/jdbc_dataset.PNG
   :alt: Dataset
   :width: 80%

Entering Field Details
^^^^^^^^^^^^^^^^^^^^

Below are the details of the fields in the ``Create Dataset`` page:

- **NAME**: Name of the New Dataset we are creating.
- **DESCRIPTION**: Description of the New Dataset.
- **CATEGORY**: Category of the New Dataset.
- **JDBC DRIVER**: Enter JDBC DRIVER.
- **JDBC URL**: Enter JDBC URL for MYSQL DB.
- **USER**: Username for MYSQL DB.
- **PASSWORD**: Password for MYSQL DB.
- **DB**: Database for MYSQL DB.
- **TABLE**: Table for MYSQL.


.. figure:: ../../../_assets/tutorials/dataset/create_data.PNG
   :alt: Dataset
   :width: 80%

Updating the Schema of the Dataset
^^^^^^^^^^^^^^^^^^^^

You can update the Schema of the Dataset by clicking on ``Update Sample Data/Schema``. It would display sample data for the dataset followed by the Schema inferred by Fire Insights.

You can update the column names in the schema based on your data.
 
 .. figure:: ../../../_assets/tutorials/dataset/update_sampledata.PNG
   :alt: Dataset
   :width: 80%

Saving the New Dataset
^^^^^^^^^^^^^^^^^^^^

Click on the ``Save`` button to save the New Dataset created.

Dashboard
^^^^^^^^^^^^^^^^^^^^^^

Click on the ``Dashboard`` tab in the same application where you have created JDBC Dataset.


 .. figure:: ../../../_assets/tutorials/dataset/dashboard_tab.PNG
   :alt: Dataset
   :width: 80%

Click on the ``Chart`` tab & select Choose a JDBC dataset, there you will find all JDBC datasets created under your application.

.. figure:: ../../../_assets/tutorials/dataset/chart_create.PNG
   :alt: Dataset
   :width: 80%

Select any JDBC dataset for which you want to create ``Chart`` & select ``CREATE NEW``

It will take you to the new page, as below

.. figure:: ../../../_assets/tutorials/dataset/chart_1.PNG
   :alt: Dataset
   :width: 80%

Select the ``Chart Type``, you want to see chart

.. figure:: ../../../_assets/tutorials/dataset/chart_typ1.PNG
   :alt: Dataset
   :width: 80%

Selected ``Bar Chart`` & updated column for x & y axis and add some filter

Add NAME, DESCRIPTION & save it

.. figure:: ../../../_assets/tutorials/dataset/chart_filter.PNG
   :alt: Dataset
   :width: 80%

Once you save it, the chart will appear on the chart list page

Similarly, you can create a different chart using a specified chart type

.. figure:: ../../../_assets/tutorials/dataset/chart_list1.PNG
   :alt: Dataset
   :width: 80%

Now using an existing chart, you can create a new dashboard 

Select the ``Dashboard`` tab & Click on CREATE DASHBOARD

.. figure:: ../../../_assets/tutorials/dataset/dashboard_tab1.PNG
   :alt: Dataset
   :width: 80%

It will take you to the New Dashboard page

.. figure:: ../../../_assets/tutorials/dataset/chart-dash1.PNG
   :alt: Dataset
   :width: 80%

Using drag & drop you need to add a chart in canvas, Add NAME, DESCRIPTION & SAVE it.

.. figure:: ../../../_assets/tutorials/dataset/save-dashboard.PNG
   :alt: Dataset
   :width: 80%

Once the Dashboard got saved successfully, it will show on the dashboard list page from where you can view, edit & delete it.

.. figure:: ../../../_assets/tutorials/dataset/dashboard_list1.PNG
   :alt: Dataset
   :width: 80%
