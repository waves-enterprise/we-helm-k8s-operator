# We Node K8s Operator Helm

create namespace & install operator

helm upgrade --install we-mainnet-operator . -n we-mainnet-operator
Folder manifests contains examples

 
cd manifests and choose install type
fill the blanks in config files , like /ADDRESS/ /PASSWORD/ etc. 


kubectl apply -f . -n namespace_name
 
