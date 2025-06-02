# ness_26thMay_kubernetes

```
Welcome to OpenDev Etherpad!

ubuntu ami latest...
t2.medium : master ...
t2.micro
t2.micro

raman khanna

https://github.com/ramannkhanna2/ness_26thMay_kubernetes.git


https://github.com/ramannkhanna2/kubernetes_end2end_front-backend.git

===============================================================




-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEA5YBKTWA9xiOSnAesuNRE9c4rYNO0JogBo9Ro0ghFFOzyvLpH
k09xc/RvyXrC0jozS/lP0H5Su2cpd0Pne473k+49A9XJ/1IA61e39pWbtOTkD1Iv
Vmbmt9LvrJExiSejBw1XZS02ggNktlog6v65eZeU2cn4zyQQcpl8ERo1sSc63X0y
xsYW0MqkWasHMsJJzvN5Feg0HOD+sOwyyHa8/wDIXDcIHwt8TKRndoJldNvnUFx8
oqnIVdoF6D4D1YdQXWGyXcz5/L4PKiC+p9/H3+IU6GJxKFAbKimeA7aqF6yC/NR5
ipFyhDXJVC/iD1c4xq38uzMr/k1xFVWD2ReqTwIDAQABAoIBAQCeDJye7tF7+5GC
zLJBU0Xudb5f30uoYW+nsKdDRZi1kXyVRj/2jfZW4ZZ+jYFPn+8luhsiPWyiTKg8
z1HCQLH1eVMhqgCDSakCahVxxpRFnoAEoReijBkFrUmLcS5JAzf9qk1uixWHseiQ
wD79NtDqkN5cogAsPuzozxSm/oLNbSXN1P+krBkxQCOqKKZTr4903D8hJaOXVShu
U+PhQGN6MUkVPYSUsEfnRg4qxjuwKajOzOvaZ7bN4ZV0TdKpLOpTD6l5VU2Z08uu
edybbrkAqzje0szBNH4a3PvC501NkIsVtP3PZX05LjAVM1rvp/i0P/3v2iPMVjIG
lFhCyXRJAoGBAPqX5lOVcb8bOa9zRYDBtg0aQi6QBGfv7mSAUNN9nQPVJOaPRBXJ
IJxo4ox3dpj+iWvGPO8ETnzh1feMsWc//btywe3SMjseFXiZ9pBYx49E8xIY5e6y
/rrELOAyT3xYyl/bb+djGFv0e1D6u2Ibg3ilk0cs5WH3S3h04Idq/h1TAoGBAOpz
5FslwoHkDwrzlpG7nq9WSwXTX1Oad2qb/WEz/YQUmeQW0cEeDyZuRVDXX3uKmo71
UoCPO0TL4Wodv/kS5M8vtez7X/0JFucD2Dw4lIAlP0NHlBXZMPVnMHNgrjiLzoZn
DUHIncn3iYvqgvIpHgZiC9SFWN5qfEb0VZGuEOOVAoGAXIaVjqsRUqS0yelf8kiT
9YaKhTK7zbyzYvxV26D3xqB+fXrMgta+acH4VDEP4zGof9i0SvRmHoosPLkAD8V6
5CldHXiM/3L+Lod6mJWPKYEl1rrGuznv//nLMASjgKAwKPCXAvJ93gYJOj85zOGn
y3YnSRJ0p5Vtkk5lUNradO0CgYEAs0SAJE2gB2+ZLPeKds4uDMV/wemYZzWh/6tc
t7loLFkQPn5QTkisrub8K08zHCSj/5GHTvO2DumR53Dt/AY9XEqP4a9n+vO7RlMD
QTDGI6HXWJtfmMEklVAclOwk6unDtbMQSO+b7vVOf+SF0aIs6haIEy0PAaoMcria
wTSGh20CgYBNTXf1pxCV19nQwHsMQQbs2rMmQf4Qcth1+sQ+0q2DO6eRQ4OtQ/Fz
WW4pPG2ZHRg/l80Xz6UGsbb6MOMsv2RFmtSVhIcDszaP/2uIG6Ht5Rvi5tIj8j9o
2PYu27k0VyZD5M0cyNbUbZRjGT+XqiMfwvq+9F3xFY4OMraJhmfGSw==
-----END RSA PRIVATE KEY-----








containerization :
    
   purpose :  to deploy our aplication properly on a platform 
   
physically on the host  >>> virtualization >>> containerization ??


vmware : i can bifercate my host >> logically separate my cluster into multiole logical parts >> vms

resource utlization is far less wrt to each container ..
have more containers than vms in the same space .
lightweight 
portable 
boot time of the app is high in vms as copared to contaners
less downtime for the app  users ...


==============================================

tool :
container runtime ~ docker , podman , crio , containerd , rockt , etc

docker is the most famous and used...

lifecycle ::: 
code of my application >>>    dockerfile  >>>         docker build  >>>         custom image      >>>>>. container deployed 


========================

only docker ~~>>> docker +orchestrtor (kubernetes , mesos , docker swarm) :
    
    
    
    
    kubectl run ramanapp --image httpd ...  >>> apiserver >>>>>> etcd >>>>  apiserver
    
    
    
    7  k api-resources
  358  clear
  359  k get pods
  360  k api-resources | grep -i con
  361  k get containers
  362  clear
  363  k delete pods --all
  364  clear
  365  k get pods
  366  k delete deploy --all
  367  clear
  368  k get pods
  369  clear
  370  k get pods -A
  371  clear
  372  kubectl run ramanapp --image httpd
  373  k get pods
  374  k get pods -o wide
  375  clear
  376  k get pods -o wide
  377  k get pods -A
  378  clear
  379  k get pods -A -o wide
  380  docker ps
  381  clear
  382  history


=========================================================





 alias k=kubectl
  418  k get nodes
  419  k get pods -A
  420* c
  421  k get pods -A -o wide
  422  clear
  423  k get pods -o wide
  424  k delete pod ramanapp
  425  clear
  426  k create ns raman
  427  k api-resources | grep -i namespace
  428  k get ns
  429  clear
  430  k run ramanapp --image httpd -n raman
  431  k get pods
  432  k get pods -n raman
  433  k get pods -A
  434  clear
  435  k get pods -A -o wide
  436  clear
  437  ls
  438  mkdir raman
  439  cd raman/
  440  ls
  441  k get pods -A -o wide
  442  vi pod.yml
  443  cat pod.yml
  444  k api-resources
  445  clear
  446  cat pod.yml
  447  k get pods
  448  k get pods -n raman
  449  k get pods -n raman -o wide
  450  curl 192.168.190.103:80
  451  clear
  452  cat pod.yml
  453  vi pod.yml
  454  k create -f pod.yml
  455  k get pods
  456  k get pods -nr aman
  457  k get pods -n raman
  458  k describe pod ramanapp2 -n raman


root@master:~/raman# cat pod.yml
apiVersion: v1
kind: Pod
metadata:
  name: ramanapp2
  namespace: raman   # 👈 This ensures the pod is created in 'raman' namespace
spec:
  containers:
  - name: ramancon
    image: nginx:1.14.2
    ports:
    - containerPort: 80


===============================================



 k get pods -A -o wide
  472  k api-resources | grep -i deploy
  473  k api-resources | grep -i rs
  474  clear
  475  k create -h
  476  clear
  477  k create deploy ramandep1 --image httpd --replicas 5
  478  k delete deploy ramandep1
  479  k create deploy ramandep1 --image httpd --replicas 5 -n raman
  480  k get pods
  481  k get pods -n raman
  482  clear
  483  k get deploy -n raman
  484  k get pods -n raman
  485  k delete ramanapp2 -n raman
  486  k delete pod ramanapp2 -n raman
  487  k get pods -n raman
  488  k get rs -n raman
  489  k delete pod ramandep1-559bb87ff6-8nst5
  490  k delete pod ramandep1-559bb87ff6-8nst5 -n raman
  491  k get pods -n raman
  492  k scale deploy ramandep1 --replicas 1
  493  k scale deploy ramandep1 --replicas 1 -n raman
  494  k get pods
  495  k get pods -n raman
  496  k scale deploy ramandep1 --replicas 5 -n raman
  497  k get pods -n raman
  498  history
  499  k get pods
  500  k get pods -n raman
  501  k scale deploy ramandep1 -n raman --replicas 10
  502  k get pods -n raman
  503  k scale deploy ramandep1 -n raman --replicas 11


=======================================================


 k get all -n raman
  508  k delete deploy -n raman ramandep1
  509  k get pods
  510  k get pods -n raman
  511  k get rs -n raman
  512  cleafr
  513  clear
  514  ls
  515  vi deploy.yml
  516  k get pods -A
  517  clear
  518  k get deploy -A
  519  clear
  520  k api-resources
  521  clear
  522  k get pods -n raman
  523  k get pods -A
  524  k describe pod sunitapp -n sunit
  525  clear
  526  k describe pod sunitapp -n sunit | grep -i label
  527  k describe deploy -n sunit | grep -i label
  528  k describe deploy | grep -i label
  529  k get pods -A --selector run=sunitapp
  530  clear
  531  k create ramanadep1 -n raman --replicas 3
  532  k create deploy ramanadep1 -n raman --replicas 3
  533  k create deploy ramanadep1 -n raman --image httpd --replicas 3
  534  k get pods -n raman
  535  k describe pod -n raman | grep -i label
  536  k get pods -A selector app=ramanadep1
  537  k get pods -A --selector "app=ramanadep1"
  538  k get rs -n raman
  539  k describe rs ramanadep1-7b6858cbc5 -n raman | grep -i label
  540  k describe deploy -n raman | grep -i label

==================================================================

28th :
    
     alias k=kubectl
 1012  k get nodes
 1013  k get pods -A
 1014  clear
 1015  k get deploy -A
 1016  clear
 1017  k create -h
 1018  clear
 1019  ls
 1020  cd raman/
 1021  ls
 1022  cat deploy.yml
 1023  vi deploy.yml
 1024  ls
 1025  vi deploy.yml
 1026  k create -f deploy.yml
 1027  vi deploy.yml
 1028  k create -f deploy.yml
 1029  k get pods
 1030  clear
 1031  k get pods -n raman
 1032  k describe pods -n raman | grep -i image
 1033  clear
 1034  k get deploy -n raman
 1035  k describe deploy -n raman
 1036  clear
 1037  k describe deploy -n raman
 1038  clear
 1039  k get rs -n raman
 1040  k describe rs -n raman
 1041  clear
 1042  k get pods -n raman
 1043  k describe pod ramandep1-7f85cb66f7-7vdm7 -n raman


root@master:~/raman# cat deploy.yml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: ramandep1
  namespace: raman
  labels:
    app: nginx
spec:
  replicas: 3
  selector:
    matchLabels:
      name: rk
  template:
    metadata:
      labels:
        name: rk
    spec:
      containers:
      - name: nginx
        image: nginx:1.14.2
        ports:
        - containerPort: 80


===============================================================


having multiple replicasets under same deployment ( same app ) :
    
    deployment.apps/ramandep1
REVISION  CHANGE-CAUSE
1         kubectl create --filename=deploy.yml --record=true

    
    
    
    
    -- nginx:1.14.1 :
        
        ramandep1
        
        ramandep1-58bfb65d5d
        
        ramandep1-58bfb65d5d-cx8fx   1/1     Running   0          26s
ramandep1-58bfb65d5d-glh5z   1/1     Running   0          26s
ramandep1-58bfb65d5d-jfchj   1/1     Running   0          26s
ramandep1-58bfb65d5d-lc4n5   1/1     Running   0          26s
ramandep1-58bfb65d5d-pj4bz   1/1     Running   0       




-- nginx:1.14.2

ramandep1

ramandep1-7f85cb66f7 

NAME                         READY   STATUS    RESTARTS   AGE
ramandep1-7f85cb66f7-555kt   1/1     Running   0          2m10s
ramandep1-7f85cb66f7-7qxpx   1/1     Running   0          2m11s
ramandep1-7f85cb66f7-mjq25   1/1     Running   0          2m12s
ramandep1-7f85cb66f7-nhj7n   1/1     Running   0          2m12s
ramandep1-7f85cb66f7-tqt5p   1/1     Running  




k get pods -n raman
 1049  vi deploy.yml
 1050  k apply -f deploy.yml
 1051  k get pods -n raman
 1052  k get rs -n raman
 1053  clear
 1054  k delete -f deploy.yml
 1055  clear
 1056  vi deploy.yml
 1057  k create -f deploy.yml --record=true
 1058  k get [pods -n raman
 1059  k get pods -n raman
 1060  k rollout status deploy ramandep1 -n raman
 1061  k rollout history deploy ramandep1 -n raman
 1062  k rollout history deploy ramandep1 -n raman --revision 1
 1063  clear
 1064  k get rs -n raman
 1065  vi deploy.yml
 1066  k apply -f deploy.yml --record=true
 1067  clear
 1068  k get deploy -n raman
 1069  k get rs -n raman
 1070  k rollout history deploy ramandep1 -n raman
 1071  k rollout history deploy ramandep1 -n raman --revision 2
 1072  clear
 1073  k get deploy -n raman
 1074  k get rs -n raman
 1075  k get pods -n raman
 1076  k describe pods -n raman | grep -i image
 1077  clear
 1078  k get rs -n raman
 1079  k rollout undo deploy ramandep1 -n raman --revision 1
 1080  k rollout undo deploy ramandep1 -n raman --to-revision 1
 1081  k get pods
 1082  clear
 1083  k get pods -n raman
 1084  k get rs -n raman
 1085  k describe pods -n raman | grep -i image
 1086  clear


root@master:~/raman# cat deploy.yml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: ramandep1
  namespace: raman
  labels:
    app: nginx
spec:
  replicas: 5
  selector:
    matchLabels:
      name: rk
  template:
    metadata:
      labels:
        name: rk
    spec:
      containers:
      - name: nginx
        #image: nginx:1.14.1   #first version of my app
        image: nginx:1.14.2
        ports:
        - containerPort: 80


=========================================================

nodeport svc 
loadblancer svc
clusterip svc 



cat deploy.yml
 1089  clear
 1090  k delete -f deploy.yml
 1091  clear
 1092  k api-resources | grep -i- service
 1093  k api-resources | grep -i service
 1094  clear
 1095  k get pods -A
 1096  clear
 1097  k get pods -n raman
 1098  vi deploy.yml
 1099  k create -f deploy.yml
 1100  k get pods -n raman
 1101  clear
 1102  k get pods -n raman -o wide
 1103  clear
 1104  vi service.yml
 1105  cat deploy.yml
 1106  vi deploy.yml
 1107  vi service.yml
 1108  cat service.yml
 1109  k create -f service.yml
 1110  clear
 1111  k get pods -n raman
 1112  k get svc -n raman
 1113  k scale deploy ramandep1 --replicas 1 -n raman
 1114  k get pods
 1115  k get pods -n raman
 1116  k get pods -n raman -o wide
 1117  clear
 1118  vi service.yml
 1119  k expose deploy ramandep1 -n raman --type LoadBalancer --port 80 --target-port 80 --name lbsvc
 1120  k get svc -n raman


root@master:~/raman# cat service.yml
apiVersion: v1
kind: Service
metadata:
  name: raman-service
  namespace: raman
spec:
  type: NodePort
  selector:
    name: rk
  ports:
    - port: 80
      # By default and for convenience, the `targetPort` is set to
      # the same value as the `port` field.
      targetPort: 80
      # Optional field
      # By default and for convenience, the Kubernetes control plane
      # will allocate a port from a range (default: 30000-32767)
      nodePort: 30007


==========================================================================

29th :



SECRETS

    encrypt the data first of all
password :
   echo 'ramankhanna123' | base64
   
   
cmFtYW5raGFubmExMjMK

username :
   echo 'ramankhanna' | base64
   
   
   cmFtYW5raGFubmEK
   
   

secret.yml :

apiVersion: v1
kind: Secret
metadata:
  name: my-secrets
  namespace: raman
type: Opaque
data:
  username: cmFtYW5raGFubmEK
  password: cmFtYW5raGFubmExMjMK
  
  
  
  
  
  
  
root@master:~/raman# cat deploy2.yml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: myapp-deployment
  namespace: raman
  labels:
    app: myapp
    type: front-end
spec:
  replicas: 3
  selector:
    matchLabels:
      app: myapp
      type: front-end
  template:
    metadata:
      labels:
        app: myapp
        type: front-end
    spec:
      containers:
      - name: httpd-container
        image: httpd
        env:
        - name: SECRET_USERNAME
          valueFrom:
            secretKeyRef:
              name: my-secrets
              key: username
        - name: SECRET_PASSWD
          valueFrom:
            secretKeyRef:
              name: my-secrets
              key: password



  
  
  alias k=kubectl
 1379  k get nodes
 1380  k get pods -A
 1381  clear
 1382  k api-resources |grep -i p
 1383  clear
 1384  k api-resources |grep  p
 1385  clear
 1386  k api-resources |grep  pv
 1387  k api-resources |grep  secrets
 1388  clear
 1389  ls
 1390  cd raman/
 1391  ls
 1392  vi secret.yml
 1393  k create -f secret.yml
 1394  k get secrets
 1395  k get secrets -n raman
 1396  k describe secrets -n raman
 1397  ls
 1398  rm -rf secret.yml
 1399  k get secrets-n raman
 1400  k get secrets -n raman
 1401  ls
 1402  vi deploy2.yml
 1403  cat deploy2.yml
 1404  k create -f deploy2.yml
 1405  k get pods -n raman
 1406  k get secrets -n raman
 1407  k exec -it myapp-deployment-58c6b5c57c-rntlk -n raman -- /bin/bash

  
  =======================================================================
  
  application developers 
  
  100gb : pv , 20gb pv , 30gb , pv , etc etc 
  
  
  
  
  pv : kubernetes adminstrator
  
  100gb : pv , 20gb pv , 30gb , pv , etc etc 
  
  
  LAB : Implementing pv +pvc with nfs ...(awsEfs)

apiVersion: v1
kind: PersistentVolume
metadata:
  name: nfs-pv-raman
spec:
  capacity:
    storage: 11Mi
  accessModes:
    - ReadWriteMany    #pods are on multiple nodes , they will accesible to a centralized storage i.e : nfs-raman-pv
  mountOptions:
    - hard
    - nfsvers=4.1
  nfs:
    path: /
    server: 172.31.12.142

---
apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: nfs-raman-pvc
spec:
  accessModes:
  - ReadWriteMany
  resources:
    requests:
      storage: 5Mi    #nearest higher storage
  volumeName: nfs-pv-raman
---
apiVersion: apps/v1
kind: Deployment
metadata:
  name: nfs-raman
spec:
  replicas: 10
  selector:
    matchLabels:
      role: nfs-raman
  template:
    metadata:
      labels:
        role: nfs-raman
    spec:
      containers:
      - name: nginx
        image: nginx:1.14.2
        ports:
        - containerPort: 80
        volumeMounts:
        - name: nfs
          mountPath: /usr/share/nginx/deploydata      # 
      volumes:
      - name: nfs
        persistentVolumeClaim:
          claimName: nfs-raman-pvc

---
kubectl expose deploy nfs-raman --name nfs-svc --type NodePort --target-port 80 --port 80


 kubectl get pv
 kubectl get pods

 note : make sure to check security group of mount target if traffic opened or not

 apt install -y nfs-server       or    apt-get install nfs-common    (ubuntu)
 mkdir /efs
 cd /
 sudo mount -t nfs4 -o nfsvers=4.1,rsize=1048576,wsize=1048576,hard,timeo=600,retrans=2,noresvport 172.31.12.142:/ efs
 df -h
 cd /efs
 ls -l

** Browse : publicip:port asisgned


  =====================================

  - bob wants to reach the production floor of his company : production floor access :

- bob wnts to get access to lets read pods in raman ns : permissions (rbac)


- bob have to the acces to the building complex (Kubernetes cluster):


- bob got a badge which will have all details of bob ( bob.key)

- bob will go to the reception (Kubernetes admin) and than bob will give the details to the reception..

-- bob details will than be set to the security officer ( api-server compnet) and than security officer will verify ; they will give bob an id with a chip inside ...

--------------------------

🧪 Lab: Creating and Managing Users in Kubernetes

-- Kubernetes does not store user objects like traditional Linux systems. Instead, authentication is handled externally (e.g., via certificates, tokens, or external identity providers), and authorization is handled inside Kubernetes using RBAC.

Authentication: Validates the identity (e.g., certificates, tokens).

Authorization: Grants permissions (e.g., Roles, ClusterRoles, RoleBindings).


                           Kubernetes Cluster
                              (API Server)
                                   │
                        ┌──────────┴──────────┐
                        │                     │
              Trusts this CA cert       Rejects others
               (ca.crt public key)
                        │
                        ▼
           ┌────────────────────────┐
           │ Certificate Authority  │
           │ (ca.crt + ca.key)      │
           └────────────────────────┘
                       ▲
                       │
       ┌─────────────────────────────┐
       │ You generate a CSR for Bob │
       │    (bob.csr from bob.key)   │
       └─────────────────────────────┘
                       │
   Sign bob.csr with ca.crt + ca.key
                       ▼
          🔏 You get bob.crt (signed cert)
                       │
                       ▼
  Add to kubeconfig:
  - user: bob
  - cert: bob.crt
  - key:  bob.key
                       │
                       ▼
     🔒 Bob runs `kubectl` ➝ API Server checks:
     - Is cert signed by trusted CA? ✅
     - Does Bob have permission? 🔒 RBAC


----------------------------------------------------------------

🧠 What’s Happening in Kubernetes
👤 Bob uses kubectl to connect to the Kubernetes API server.

He provides:

bob.crt (his certificate)

bob.key (his private key)

The API server checks:

“Was bob.crt signed by someone I trust — my CA (ca.crt)?”

If yes → ✅ Bob is authenticated.
----------------------------------------------------------------




🔧 Prerequisites
kubectl and openssl installed


Step 1: 🔐 Generate a Certificate for a New User
1.1 Create a private key and CSR (Certificate Signing Request)

openssl genrsa -out bob.key 2048

openssl req -new -key bob.key -out bob.csr -subj "/CN=bob"


#openssl req -new -key bob.key -out bob.csr -subj "/CN=bob/O=developers"    
# above one if want to add bob in a group called developers to which u can assign a role afterwards just like a user

-- CN=bob: The username
-- O=developers: Group

Step 2: 🖋️ Sign the CSR with Kubernetes CA
Find your Kubernetes CA cert and key. Usually found in:

/etc/kubernetes/pki/ca.crt
/etc/kubernetes/pki/ca.key

-- Use them to sign the certificate:

openssl x509 -req -in bob.csr -CA /etc/kubernetes/pki/ca.crt -CAkey /etc/kubernetes/pki/ca.key -CAcreateserial \
-out bob.crt -days 365

-- This generates bob.crt, the signed certificate.


Step 3 : Create a backup of config file:  (JustIn Case)

root@master:~# cd .kube/
root@master:~/.kube# ls
cache  config
root@master:~/.kube# cp config config_bak
root@master:~/.kube# ls
cache  config  config_bak



🛠️ Step 4: Add User and Context to Existing Kubeconfig
3.1 Add user

kubectl config set-credentials bob \
  --client-certificate=bob.crt \
  --client-key=bob.key

-- This updates ~/.kube/config and adds a new user entry named bob.

3.2 Add a context for the new user
-- Find your current cluster name:


kubectl config get-clusters
kubectl config get-users

-- dont do it with me after tis step :

-- Use that cluster name in the context:


kubectl config set-context bob-context \
  --cluster=<your-cluster-name> \
  --user=bob \
  --namespace=default


-- Set the context:

kubectl config use-context bob-context


-- Check your current context:

kubectl config current-context

🧪 Step 4: Test Access (Should Be Forbidden)

kubectl get pods

-- Expected result:

Error from server (Forbidden): User "bob" cannot list resource "pods" in API group "" in the namespace "default"

Try adding RBAC and see the user responding accordingly ...
--------

-- Delete the user and related objects :

kubectl config delete-context bob-context
kubectl config delete-user bob
rm -rf bob.key bob.crt bob.csr

kubectl config view 
kubectl config use-context kubernetes-admin@kubernetes
kubectl config view 


================================================================================
RBAC :


Lab Activity: Enforce Namespace-Specific Permissions and Test Access
Step 1: Create a Namespace
Create a new namespace for testing:

bash
Copy
kubectl create namespace test-namespace
Verify the namespace:

bash
Copy
kubectl get namespaces
Step 2: Create a Role
Create a Role that allows read-only access to Pods in the test-namespace:

Write the following YAML to a file (pod-reader-role.yaml):


apiVersion: rbac.authorization.k8s.io/v1
kind: Role
metadata:
  namespace: test-namespace
  name: pod-reader
rules:
- apiGroups: [""]
  resources: ["pods"]
  verbs: ["get", "list", "watch", "create"]
Apply the Role:

bash
Copy
kubectl apply -f pod-reader-role.yaml
Verify the Role:

bash
Copy
kubectl get roles -n test-namespace
Step 3: Create a ServiceAccount
Create a ServiceAccount in the test-namespace:

bash
Copy
kubectl create serviceaccount test-sa -n test-namespace
Verify the ServiceAccount:

bash
Copy
kubectl get serviceaccounts -n test-namespace
Step 4: Create a RoleBinding
Bind the pod-reader Role to the test-sa ServiceAccount:

Write the following YAML to a file (pod-reader-rolebinding.yaml):


apiVersion: rbac.authorization.k8s.io/v1
kind: RoleBinding
metadata:
  name: pod-reader-binding
  namespace: test-namespace
subjects:
- #kind: ServiceAccount
  kind: User
  #kind: Group
  #name: developers
  name: bob
  #namespace: raman
roleRef:
  kind: Role
  name: pod-reader
  apiGroup: rbac.authorization.k8s.io


Apply the RoleBinding:

bash
Copy
kubectl apply -f pod-reader-rolebinding.yaml
Verify the RoleBinding:

bash
Copy
kubectl get rolebindings -n test-namespace
Step 5: Test Access Using kubectl auth can-i
Authenticate as the ServiceAccount:

Use the --as flag to impersonate the test-sa ServiceAccount and test access.

Test Permissions:

Check if the ServiceAccount can list Pods in the test-namespace:

bash
Copy
kubectl auth can-i list pods --namespace test-namespace --as system:serviceaccount:test-namespace:test-sa
Expected Output: yes.

Check if the ServiceAccount can create Pods in the test-namespace:

bash
Copy
kubectl auth can-i create pods --namespace test-namespace --as system:serviceaccount:test-namespace:test-sa
Expected Output: no (since the Role only allows get, list, and watch).

Check if the ServiceAccount can list Pods in the default namespace:

bash
Copy
kubectl auth can-i list pods --namespace default --as system:serviceaccount:test-namespace:test-sa
Expected Output: no (since the Role is namespace-specific).


=======================================================================



  
  configmap :


=====================================================

CONFIG MAPS:



echo "hell from prod" > prod.html
 2061  ls
 2062  k get cm -n raman
 2063  k create cm prod.cmap -h
 2064  clear
 2065  k create cm prod.cmap --from-file=prod.html
 2066  ls
 2067  cat prod.html
 2068  k delete cm prod.cmap
 2069  k create cm prod.cmap --from-file=prod.html -n raman
 2070  k get cm -n raman
 2071  k describe cm -n raman prod.cmap
 2072  k get cm -n raman
 2073  k get cm prod.cmap -n raman
 2074  k get cm prod.cmap -n raman -o yaml
 2075  k get cm prod.cmap -n raman -o yaml > prod-cmap.yml
 2076  ls
 2077  cat prod-cmap.yml
 2078  clear
 2079  ls
 2080  clear
 2081  k get cm -n raman
 2082  k get pods -n raman
 2083  k delete deploy --all -n raman
 2084  vi podcm.yml
 2085  cat podcm.yml
 2086  k create -f podcm.yml
 2087  k get pods -n raman
 2088  k get cm -n raman
 2089  k get pods -n raman-o wide
 2090  k get pods -n raman -o wide
 2091  curl 192.168.190.105:80
 2092  k expose pod nginx -n raman --type NodePort -port 80 --target-port 80 --name cmsvc
 2093  k expose pod nginx -n raman --type NodePort --port 80 --target-port 80 --name cmsvc
 2094  clear
 2095  k get cm -n raman
 2096  k get pods -n raman
 2097  k get svc -n raman
 2098  echo "hell from dev" > dev.html
 2099  ls
 2100  k create cm dev.cmap --from-file=dev.html -n raman
 2101  k get cm -n raman
 2102  ls
 2103  vi podcm.yml
 2104  k apply -f podcm.yml
 2105  k get pods
 2106  k get pods -n raman
 2107  clear
 2108  k replace --force -f podcm.yml




root@master:~/raman# cat prod.html
hell from prod

root@master:~/raman# cat dev.html
hell from dev

root@master:~/raman# cat podcm.yml
apiVersion: v1
kind: Pod
metadata:
  name: nginx
  namespace: raman
  labels:
    app: nginx
spec:
  containers:
  - name: nginx
    image: nginx:latest
    ports:
    - containerPort: 80
    volumeMounts:
    - name: rk
      mountPath: /usr/share/nginx/html
  volumes:
    - name: rk
      configMap:
        name: prod.cmap
        #name: dev.cmap
        items:
         - key: prod.html
       # - key: dev.html
          path: index.html


=========================================


root@master:~/raman# cat daemonset.yml
apiVersion: apps/v1
kind: DaemonSet
metadata:
  name: fluentd-elasticsearch
  namespace: kube-system
  labels:
    k8s-app: fluentd-logging
spec:
  selector:
    matchLabels:
      name: fluentd-elasticsearch
  template:
    metadata:
      labels:
        name: fluentd-elasticsearch
    spec:
      tolerations:
      # these tolerations are to have the daemonset runnable on control plane nodes
      # remove them if your control plane nodes should not run pods
      - key: node-role.kubernetes.io/control-plane
        operator: Exists
        effect: NoSchedule
      - key: node-role.kubernetes.io/master
        operator: Exists
        effect: NoSchedule
      containers:
      - name: fluentd-elasticsearch
        image: quay.io/fluentd_elasticsearch/fluentd:v2.5.2
        resources:
          limits:
            memory: 200Mi
          requests:
            cpu: 100m
            memory: 200Mi
        volumeMounts:
        - name: varlog
          mountPath: /var/log
      # it may be desirable to set a high priority class to ensure that a DaemonSet Pod
      # preempts running Pods
      # priorityClassName: important
      terminationGracePeriodSeconds: 30
      volumes:
      - name: varlog
        hostPath:
          path: /var/log

=========================================================================


helm ~ package manager of kubernetes componnets 

image ~ custom image ~ deploy image as container /pods on kubernetes 



https://helm.sh/docs/intro/install/#from-script

-----------------------------------------------------------------------

raman-tomcat :
first revison : persistence.enabled =false  , svc     LoadBalancer  , replica 1  (multiple kubernetes objects)
second revision : ?       persistence.enabled =false  , svc     NodepORT  , replica 3 , ETC                              (multiple kuberneets objects )



 alias k=kubectl
 1820  k get node
 1821  clear
 1822  k get pods -A
 1823  clear
 1824  curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
 1825  chmod 700 get_helm.sh
 1826  ./get_helm.sh
 1827  helm repo list
 1828  helm remove repo prometheus-community
 1829  helm repo remove  prometheus-community
 1830  helm repo list
 1831  helm repo add bitnami https://charts.bitnami.com/bitnami
 1832  helm install my-tomcat bitnami/tomcat --version 11.7.9
 1833  helm list
 1834  k get pods
 1835  clear
 1836  k get pods
 1837  helm -h
 1838  helm list
 1839  helm uninstall my-tomcat
 1840  clear
 1841  helm list
 1842  k get pods
 1843  helm install my-tomcat bitnami/tomcat --version 11.7.9 --dry-run
 1844  clear
 1845  helm install my-tomcat bitnami/tomcat --version 11.7.9 --debug
 1846  k get pods
 1847  clear
 1848  helm uninstall my-tomcat
 1849  k get pods
 1850  helm install my-tomcat bitnami/tomcat --version 11.7.9 --debug --dry-run
 1851  clear
 1852  helm install my-tomcat bitnami/tomcat --version 11.7.9
 1853  helm -h
 1854  helm template
 1855  helm template  my-tomcat bitnami/tomcat --version 11.7.9
 1856  helm list
 1857  helm install my-tomcat bitnami/tomcat --version 11.7.9
 1858  k get pods
 1859  k describe pod
 1860  k  get pv
 1861  k  get pvc
 1862  helm list
 1863  helm template my-tomcat
 1864  helm template  my-tomcat bitnami/tomcat --version 11.7.9
 1865  clear
 1866  vi cv.yml
 1867  helm list
 1868  helm upgrade my-tomcat bitnami/tomcat --values cv.yml
 1869  clear
 1870  helm list
 1871  helm history my-tomcat
 1872  k get all
 1873  clear
 1874  k get all
 1875  k describe po pod/my-tomcat-6d848b7bb9-4d78f
 1876  k describe po my-tomcat-6d848b7bb9-4d78f
 1877  k describe pod my-tomcat-6d848b7bb9-4d78f
 1878  clear
 1879  k get all
 1880  helm list
 1881  clear
 1882  helm list
 1883  helm uninstall my-tomcat
 1884  k get all
 1885  clear
 1886  helm create myapp-chart
 1887  ls
 1888  cd myapp-chart/
 1889  ls
 1890  cat Chart.yaml
 1891  cd templates/
 1892  ls
 1893  vi deployment.yaml
 1894  clear
 1895  alais k=kubectl
 1896  alias k=kubectl
 1897  k get nodes
 1898  k get pods -A
 1899  k delete daemonset -n kube-system kube-system
 1900  k delete daemonset -n kube-system fluentd-elasticsearch
 1901  clear
 1902  k delete deploy -n raman --all
 1903  clear
 1904  helm
 1905  clear
 1906  helm list
 1907  clear
 1908  helm list
 1909  helm repo
 1910  clear
 1911  helm repo list
 1912  helm repo rmeove bitnami
 1913  helm remove repo bitnami
 1914  helm remove repo bitnamiclear
 1915  clear
 1916  helm repo list
 1917  k get pods
 1918  k get pods -n raman
 1919  helm list
 1920  helm list -A
 1921  clear
 1922  helm repo add bitnami
 1923  helm repo add bitnami h
 
 1956  clear
 1957  helm repo add bitnami https://charts.bitnami.com/bitnami
 1958  helm repo list
 1959  helm search repo bitnami
 1960  clear
 1961  helm search repo bitnami/jenkins
 1962  helm search repo bitnami/tomcat
 1963  helm show values bitnami/tomcat
 1964  clear
 1965  helm show chart bitnami/tomcat
 1966  clear
 1967  helm show all bitnami/tomcat
 1968  clear
 1969  helm list
 1970  helm install raman-tomcat bitnami/tomcat
 1971  clear
 1972  helm remove raman-tomcat bitnami/tomcat
 1973  helm uninstall raman-tomcat bitnami/tomcat
 1974  clear
 1975  helm list
 1976  helm list -A
 1977  helm install raman-tomcat bitnami/tomcat -n raman
 1978  clear
 1979  helm list
 1980  helm list -n raman
 1981  k get all -n raman
 1982  clear
 1983  helm list
 1984  helm list -n ramna
 1985  helm list -n raman
 1986  helm status raman-tomcat
 1987  helm status raman-tomcat -n raman
 1988  clear
 1989  helm list
 1990  helm list -a
 1991  helm list -A
 1992  k get pods
 1993  k get pods -A
 1994  clear
 1995  k get pods -n raman
 1996  k logs raman-tomcat-c948c8dc-6lb6l
 1997  k logs raman-tomcat-c948c8dc-6lb6l -n raman
 1998  k describe pod -n raman raman-tomcat-c948c8dc-6lb6l
 1999  k get pvc -n raman
 2000  k get pv
 2001  clear
 2002  helm list
 2003  helm list -n raman
 2004  helm template -n raman raman-tomcat
 2005  helm template -n raman tomcat-11.7.9
 2006  helm template -n raman bitnami/tomcat-11.7.9
 2007  helm template -n raman bitnami/raman-tomcat
 2008  helm list
 2009  helm list -n raman
 2010  clear
 2011  helm template raman-tomcat bitnami/tomcat -n raman
 2012  k get svc -n raman
 2013  clear
 2014  helm list
 2015  helm template raman-tomcat bitnami/tomcat -n raman
 2016  k get pods -n raman
 2017  k get pvc -n raman
 2018  clear
 2019  helm list
 2020  helm list  -A
 2021  helm uninstall raman-tomcat
 2022  helm uninstall raman-tomcat -n raman
 2023  k get pods -n raman
 2024  k get all -n raman
 2025  clear
 2026  helm install raman-tomcat bitnami/tomcat --set persistence.enabled=false -n raman
 2027  clear
 2028  helm list
 2029  k get pods -n raman
 2030  k get all -n raman
 2031  helm list
 2032  helm list -n raman
 2033  ls
 2034  cd raman/
 2035  vi vaules.yml
 2036  clear
 2037  ls
 2038  helm list -n raman
 2039  k get svc -n raman
 2040  k get deploy -n raman
 2041  helm install -n raman bitnami/jenkins --dry-run --debug
 2042  clear
 2043  helm list
 2044  helm list -A
 2045  ls
 2046  vi values.yml
 2047  ls
 2048  vi vaules.yml
 2049  mv vaules.yml values.yml
 2050  vi values.yml
 2051  helm history raman-tomcat -n raman
 2052  helm upgrade raman-tomcat bitnami/tomcat --values values.yml
 2053  helm list
 2054  helm upgrade raman-tomcat bitnami/tomcat --values values.yml -n raman
 2055  clear
 2056  helm history raman-tomcat -n raman
 2057  k get all -n raman
 2058  k get rs -n raman
 2059  k get pods -n raman
 2060  k get svc
 2061  k get svc -n raman
 2062  clear
 2063  helm list
 2064  helm list -n raman
 2065  helm history raman-tomcat -n raman
 2066  helm rollback raman-tomcat 1
 2067  helm rollback raman-tomcat 1 -n raman
 2068  k get all -n raman
 2069  helm rollback raman-tomcat 2 -n raman
 2070  clear
 2071  k get all -n raman
 2072  clear
 2073  helm pull oci://registry-1.docker.io/bitnamicharts/tomcat --version 11.7.9
 2074  ls
 2075  tar -xvzf tomcat-11.7.9.tgz
 2076  ls
 2077  cd tomcat/



```
