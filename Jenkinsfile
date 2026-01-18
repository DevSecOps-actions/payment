@Library('jenkins-shared-library') _

def configmap = [
    project: "roboshop",
    component: "payment"
]

if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    pythonEKSpipeline(configmap)
}
else{
    echo "Please follow the CR(change release) process"
}
