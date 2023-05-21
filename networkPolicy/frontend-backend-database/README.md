# Frontend-Backend-Databse #
 ## Backend Pod should able to communicate database pod in namespace database
 
 ## Requirement: 
   1. Crate a Namespace database and add a lable in namespace  *ns=database* 
   2. Create a deployment of mysql
   3. create a default-deny networkpolicy in database namespace. 
   4. Now apply changes in backend networkpolicy ( created In default namespace ) to allow egress traffic in database namespace 
   5. Also create a database networkpolicy which allow ingress traffice from backend pod from the default namesace. 

