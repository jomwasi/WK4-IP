# YOLO KUBERNATICS ORCHASTRATION
  CHOICE OF OBJECTS USED

  This project uses services,deployment, config maps, and persistent volume. There are two files - client and backend.

    Both client and backend are set to ensure that they are exposed externally.

   STORAGE SOLUTIONS
   MongoDB database; to ensure persistent storage for data integrity it will use Kubernetes PersistentVolume (PV) and PersistentVolumeClaim (PVC). The PersistentVolume is a cluster-wide resource that represents a physical storage device, while the PersistentVolumeClaim is a request for storage by a pod. The PVC binds to the PV, providing a reliable storage solution for MongoDB data.

   GIT WORKFLOW
   The Kubernetics files are version-controlled using Git alongside other project files, and changes are be committed and pushed to a Git repository.