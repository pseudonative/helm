### challenge 1
1: create a new chart called challenge.
  helm create challenge 

2: Remove all the files except service and deployment

3. Labels - app apache

4. Template the deployment name; image; and version

   deployment name - challenge 
   image httpd version 2.4 

5. template the service 
   name - challengesvc
   type  nodeport
   nodeport port 31234

6. deploy the chart 

check the default apache page - gcloud commpute ssh node its on

tear it down 

service and container ports are 80

