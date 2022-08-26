# helm-gui-generator
Helm gui generator
This project meant to acclrate you helming process by let you insert ui componenet and then get as resault zip of helm chart , which you can install to
get all the resources on you kuberentes cluster.

TO do
ui wise(order by pirority):
  - Add the other resosource such as config map, services, ingress, and presistent volume claim.
  - Add tree map of the services of the current helm eg deployment related resource pods
  - Add init container to deployment screen
  - replace promts with pop up box
  - make nicer ui with react?
  
  backed wise:
  
  Create backend that recv all data and let you download helm chart that create the resource on k8s
  
