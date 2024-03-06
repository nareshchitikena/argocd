# argocd
apiVersion: argoproj.io/v1alpha1
kind: Application
metadata:
  name: todo-app-argo
  namespace: argocd
spec:
  project: default
