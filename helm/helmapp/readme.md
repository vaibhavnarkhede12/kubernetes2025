helm create helmapp
helm install vaibhav-app ./helmapp
helm uninstall vaibhav-app
helm upgrade vaibhav-app ./helmapp
helm rollback vaibhav-app 1