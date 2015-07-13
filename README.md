Kitchensink - binary WAR artifact deployment
============================================

OpenShift Create -> Template -> eap-basic-sti -> GIT_URI, GIT_REF, GIT_CONTEXT_DIR 

Commmand line  
`oc new-app --template=eap6-basic-sti --param=GIT_URI=https://github.com/kenthua/kitchensink-war.git --param=GIT_REF=master --param=GIT_CONTEXT_DIR=""`

References EAP builder image  
Binary WAR artifact in deployments folder will get copied to the EAP standalone/deployments folder
