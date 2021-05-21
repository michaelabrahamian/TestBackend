todo

- include export CYPRESS_BASE_URL=http://xxx in acceptance script
- makefile
- acceptance test

nice-to-have

- reactive js
- admin view

Done

- Skeleton express js app
  - controllers
  - services
  - routes
  - models
- git hook
  - lint
  - prettier
  - test
- dockerfile
- version (via actuator)
- health check (via actuator)

---

kubectl port-forward helmchart-test-backend-677f5c59bd-jlfsm 8080:3000
kubectl get pods --no-headers -o custom-columns=":metadata.name" | grep test-backend
POD_NAME=`cat temp_pod_name.txt`

- here's an update!
