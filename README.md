Kubernetes Project

install Minikube or Kind (Kubernetes in Docker) for local Kubernetes clusters.
# For AMD64 / x86_64
  [ $(uname -m) = x86_64 ] && curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.25.0/kind-linux-amd64
  chmod +x ./kind
  sudo mv ./kind /usr/local/bin/kind


