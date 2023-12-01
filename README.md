# backstage-demo-k8-sample-component

This project is used to demo the backstage application. This project is going to have sample kubernetes application. We will map this project component on the demo backstage application.


Proxy request failed with 403 Forbidden, { "kind": "Status", "apiVersion": "v1", "metadata": {}, "status": "Failure", "message": "pods \"appeng-backstage-5774884cbd-sg4gz\" is forbidden: User \"system:serviceaccount:backstage:backstage-k8-plugin-sa\" cannot get resource \"pods/log\" in API group \"\" in the namespace \"backstage\"", "reason": "Forbidden", "details": { "name": "appeng-backstage-5774884cbd-sg4gz", "kind": "pods" }, "code": 403 }