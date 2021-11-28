# helm-charts
Used for Devops Experts project

Can do:
	helm repo add helm-charts https://okless71.github.io/helm-charts
	helm install --name ohad --namespace ohadnamespce helm-charts/deployk8
Test:
	kubectl -n test get all