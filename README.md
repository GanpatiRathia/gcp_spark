# gcp_spark
Contains Jupyter Notebooks and  Procedure to interact with GCP spark jupyter 


## How to use Dataproc for creating spark cluster
<p>
goto "https://console.cloud.google.com/"
select project or create one
Then on search bar type Dataproc to create spark cluster
</p>
<div align="center">
<img src="/img/1.Dataproc/1.png">
<p>1. Select Dataproc as in figure</p>

<p>
Click on Create Cluster.
Google Cloud Dataproc lets you create Apache Hadoop Cluster without actually having to maintain different nodes in a cluster and underlying analytical tools.
</p>
<div align="center">
<img src="/img/1.Dataproc/2.png">
<p>2. Create Cluster</p>

<p>
Select Cluster on Compute Engine and Click on Create
</p>
<div align="center">
<img src="/img/1.Dataproc/3.png">
<p>
3. Selecting Cluster on Compute Engine or GKE
</p>

<p>
Setup the cluster as shown :
</p>
<div align="center">
<img src="/img/1.Dataproc/4.png">
<p>4. Setup the cluster</p>

<p>
Change the image type and version for different tools needed all image and version does not support specific tools and service.
</p>
<div align="center">
<img src="/img/1.Dataproc/5.png">
<p>5. Change of image type and version from the list</p>

<p>
Select optional components i.e. Anaconda and Jupyter Notebook etc.
</p>
<div align="center">
<img src="/img/1.Dataproc/6.png">
<p>6. Components</p>

<p>
Enable Component Gateway.
</p>
<div align="center">
<img src="/img/1.Dataproc/7.png">
<p>7. Component Gateway</p>

<p>
Aftere selecting components and leaving others to default option, Click on Create.
</p>
<div align="center">
<img src="/img/1.Dataproc/8.png">
<p>8. Create Cluster</p>

<p>
It can show error if your quota for a specific type of compute service is exhausted by you like in the image.Then we need to configure nodes.
</p>
<div align="center">
<img src="/img/1.Dataproc/9.png">
<p>9. Error : Compute Resource Exhausted</p>

<p>
We need to configure our nodes which is available i.e. N1 series with 2 nodes. 
</p>
<div align="center">
<img src="/img/1.Dataproc/10.png">
<p>10. Node Configuration</p>

<p>
Rest all leaving it to default, set up the cluster by selecting appropriate components i.e. Anaconda, Jupyter Notebook etc. according to our needs and also Enable component gateway.
</p>
<div align="center">
<img src="/img/1.Dataproc/11.png">
<p>11. Components</p>

<p>
After setting all configuration apache hadoop cluster will be created and you will see success status.
</p>
<div align="center">
<img src="/img/1.Dataproc/12.png">
<p>12. Successfully created cluster</p>

<p>
You can go to web interfaces to see different components to interact with apache hadoop cluster on GCP.
</p>
<div align="center">
<img src="/img/1.Dataproc/13.png">
<p>13. Web Interfaces</p>

<p> 
Jupyter Interface where you can create new pyspark notebook.
</p>
<div align="center">
<img src="/img/1.Dataproc/14.png">
<p>14. Jupyter</p>

<p>
Notebook creation
</p>
<div align="center">
<img src="/img/1.Dataproc/15.png">
<p>15. Notebook creation</p>

## Q1

<div align="center">
<img src="/img/Q1/1.png">
<p>1</p>

<div align="center">
<img src="/img/Q1/2.png">
<p>2</p>

<div align="center">
<img src="/img/Q1/3.png">
<p>3</p>

<div align="center">
<img src="/img/Q1/4.png">
<p>4</p>

<div align="center">
<img src="/img/Q1/5.png">
<p>5</p>

<div align="center">
<img src="/img/Q1/6.png">
<p>6</p>

<div align="center">
<img src="/img/Q1/7.png">
<p>7</p>

<div align="center">
<img src="/img/Q1/8.png">
<p>8</p>

<div align="center">
<img src="/img/Q1/9.png">
<p>9</p>

<div align="center">
<img src="/img/Q1/10.png">
<p>10</p>

## Q2

<div align="center">
<img src="/img/Q2/1.png">
<p>1</p>

<div align="center">
<img src="/img/Q2/2.png">
<p>2</p>


<div align="center">
<img src="/img/Q2/3.png">
<p>3</p>

<div align="center">
<img src="/img/Q2/4.png">
<p>4</p>

## Q3

<div align="center">
<img src="/img/Q3/1.png">
<p>1</p>

<div align="center">
<img src="/img/Q3/2.png">
<p>2</p>

<div align="center">
<img src="/img/Q3/3.png">
<p>3</p>

## Q3

<div align="center">
<img src="/img/Q4/1.png">
<p>1</p>

<div align="center">
<img src="/img/Q4/2.png">
<p>2</p>

<div align="center">
<img src="/img/Q4/3.png">
<p>3</p>
