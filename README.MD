## Short tutorial for openshift integration

### Openshift login
1. Add custom dns server ke windows settings taruh di priority no 1
    >10.20.212.230 
    
1. pastikan bisa ping devmasteros.gsit.co.id
1. di terminal ketik 
    > oc login https://devmasteros.gsit.co.id:8443
    
### Openshift basic command
* `oc projects <project_name>` -> see currenct project
* `oc get projects` -> see all available project
* `oc get all` -> see all object in current namespace


### Adding dependencies to enable spring kubernetes integration
* import `org.springframework.cloud:spring-cloud-kubernetes-config` dependencies
* create configmap in openshift
* add `spring.application.name=<configmap>` in application.properties
* 

 
    
    
