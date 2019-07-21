Tasks:
1.	Create a Highly available Kubernetes cluster manually using Google Compute Engines (GCE). Do not create a Kubernetes hosted solution using Google Kubernetes Engine (GKE). Use Kubeadm(preferred)/kubespray. Do not use kops.
2.	Create a CI/CD pipeline using Jenkins (or a CI tool of your choice) outside Kubernetes cluster (not as a pod inside Kubernetes cluster).
3.	Create a development namespace.
4.	Deploy guest-book application (or any other application which you think is more suitable to showcase your ability, kindly justify why you have chosen a different application) in the development namespace.
5.	Install and configure Helm in Kubernetes
6.	Use Helm to deploy the application on Kubernetes Cluster from CI server.
7.	Create a monitoring namespace in the cluster.
8.	Setup Prometheus (in monitoring namespace) for gathering host/container metrics along with health check status of the application. 
9.	Create a dashboard using Grafana to help visualize the Node/Container/API Server etc. metrices from Prometheus server. Optionally create a custom dashboard on Grafana
10.	Setup log analysis using Elasticsearch, Fluentd (or Filebeat), Kibana.
11.	Demonstrate Blue/Green and Canary deployment for the application (For e.g. Change the background color or font in the new version etc.,)
12.	Write a wrapper script (or automation mechanism of your choice) which does all the steps above.
13.	Document the whole process in a README file at the root of your repo. Mention any pre-requisites in the README.
