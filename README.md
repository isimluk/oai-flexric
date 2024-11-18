# Demo: OAI with Flexric

 - install oai core using standard charts
 - install flexric from this repo with
   ```
   containerImage:
     repository: oaisoftwarealliance/oai-flexric
   ```
 - install gnb from this repo with
   ```
   kubernetesType: Vanilla  #Vanilla for community kubernetes distribution else Openshift for Openshift
   
   nfimage:   # image name either locally present or in a public/private repository
     version: 2024.w45 # image tag or develop
   
   config:
     flexrichost: "flexric-oai-flexric.oai.svc.cluster.local"
   ```
 - install nr-ue simulator from standard charts
   

