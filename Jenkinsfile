@Library('jenkins-shared-libraries')_ 

def configMap = [
    project: "roboshop",
    component: "payment"
]
 pythonEkspipeline.call(configMap)
// if(! env.BRANCH_NAME.equalsIgnoreCase('main')){
//     pythonEkspipeline.call(configMap)

// }
// else {
//     echo 'proced with prod deployment'
// }
