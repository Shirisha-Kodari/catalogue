// @Library('jenkins-shared-library') _

// def configMap = [
//     project: "roboshop",
//     component: "catalogue"
// ]

// if(env.BRANCH_NAME != "main"){
//     nodejsEKSPipeline(configMap)
// }
// else{
//     echo "Please proceed with PROD process"
// }



// @Library('jenkins-shared-library') _

// def configMap = [
//     // greeting : "hello Jenkins"
//     project: "roboshop",
//     component: "catalogue"
// ]
// if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ // if not equals to main

//     nodejsEKSPipeline(configMap) // by deafauult fntion 
// }
// else{
//     echo "Please proceed with PROD process"
// }




@Library('jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "catalogue"
]

nodejsEKSPipeline(configMap)