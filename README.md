part 1 showed the repition of previous task 
part 2 is a new version tag and applied same commands and updated the deployment file
docker build -t bhanu0000/calculator.v2 .
docker push bhanu0000/calculator:v2
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
applied kubectl get services to get ports.
