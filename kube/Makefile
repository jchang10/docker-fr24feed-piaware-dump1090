
create_cluster:
	k3d cluster create mycluster1 -p "80:80@loadbalancer"

kubectl_apply:
	kubectl apply -f kube/deployment.yml
	kubectl apply -f service.yml
	kubectl apply -f ingress.yml


