# contentauditanalysis
Data Analysis and Visualization of the Content Audititrail. This helps for Data Analysis of CMS Audittrail data . 
The sample code is provided with the data extracted from Documentum . But similar approach could be performed for 
any CMS Data extract

1. Pull the jupyter Docker image 

      CMD > docker pull jupyter/datascience-notebook
      
2. Run the Jupyter Notebook .
 
     CMD > docker run -p 8888:8888 jupyter/scipy-notebook
      
3. Copy the Audittrail data CSV to the Jupyter container

     CMD > docker cp <CSV Source location> <ContainerID:Target location>
         
4. Get the Noterbook url from console logs and open in browser

5. Create a New Python file and copy the code into it and Execute it.


 
 
 
 


