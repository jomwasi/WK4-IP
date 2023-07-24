# OCHASTRATING YOLO APP WITH KUBERNATES
# DESCRIPTION
This project uses Kubernetes to orchestrate the YOLO app. The YOLO app consists of both client and backend component. The project ensures seamless deployment and management of the app using Kubernetes.
# SET UP
 - To run and test kubernates - download minikube and kubectl on local machine
 - clone YOLO app repository to local machine by git clone command
 - Start minikube by entering command minikube start
 - Create necessary Kubernates manifests in each directory:client, backend & database
 - Deploy by defining the desired state and number of replicas for the client, backend and mongo components.
 - Service: Expose the client, backend and mongo components as Kubernetes services.
 - Secrets: Configure any environment-specific secrets or configuration required by the application as defined in the resctive directories secret files.
 - PVC (PersistentVolumeClaim): If applicable, set up persistent storage for the backend component. You can create the YAML files for these Kubernetes objects based on the requirements of your YOLO app.
Apply Kubernetes using the kubectl apply command.
