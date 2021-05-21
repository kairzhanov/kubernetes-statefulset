# Kubernetes Statefulset



## Installation

Run commands to run the project

```bash
kubectl apply -f app-config.yaml
kubectl apply -f mongodb-statefulset.yaml
```

```
helm install --name nodejs ./nodeapp
```

## Migrations
Connect to pods and run following commands:
```bash

mongo

use kbtu-sa

db.users.insert({name: "Damir", lastname: "Kairzhanov", age: 23, email: "damir.kairzhanov at kaspi.kz"})
```

## Usage

```nodejs
localhost:3000/users/create with keys.
new CRUD operations will be added .
```
