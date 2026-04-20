@Library(jenkins-shared-libraries)_ 

def configMap = [
    project = "roboshop",
    component = "payment"
]
if(! env.BRANCH_NAME.equalsIgnoreCase('main')){
    pythonEkspipeline.call(configMap)

}
else {
    echo 'proced with prod deployment'
}
