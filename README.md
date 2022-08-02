# Assignment 3 CLO 835
  Deploy containerized application and mongo database using persistent storage, LoadBalance, storage class, PVC. 

Step1: Deploy Storage class
Step2: Deploy PVC-mongo (persistent volume claim)
Step3: Deploy mongo-deployment 
Step4: Deploy mongo-service (clusterIP)
Step5: Deploy frontend-deployment 
Step6: Deploy frontend-service (LoadBalancer)

#Navigate to Configmap directory and deploy the following:
 Step1: Deploy pod-env 
 Step2: Deploy configmap first and then pod-env-configmp
 Step3: Deploy pod-env-secrets

#Navigate to Hostpath and deploy the following:
 Step1: Deploy PV-hostpath
 Step2: Deploy PVC-hostpath
 Step3: Delete the existing mongo deployment first then deploy PVC-hostpath mongo-deployment-hostpath
