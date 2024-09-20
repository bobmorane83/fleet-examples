kubectl get pod -n nginx
kubectl get pod xxxxxx -n nginx -o yaml
curl 10.42.0.20:80

sudo service nginx stop

# k3s server --snapshotter=native
# cat /var/lib/rancher/k3s/server/node-token
# k3s agent -s https://192.168.98.3:6443 --snapshotter=native --node-name=slave -t K103a063a4ab8321f8ad701adc9c27b71af901a49659f1216a7d2d312c81ead12ee::server:92cc3927d9ee963207c1cdd627d19e92
