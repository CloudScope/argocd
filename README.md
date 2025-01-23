z8if9jMGa3JPF765
$ kubectl create ns argo
$ helm repo add argo https://argoproj.github.io/argo-helm
"argo" has been added to your repositories

$ helm install argo-cd argo/argo-cd -n argo
NAME: argo-cd
