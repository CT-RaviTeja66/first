// pipeline {
//     agent { label 'ravi10.100.30.83' }
//     stages {
//         stage('Clone repository') {
//             environment {
//                 GIT_SSH_COMMAND="ssh -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no"
//             }
//             steps {
//                 dir('/home/raviteja/test1/') {
//                     echo "started"
//                     git branch: 'myrepo', credentialsId: '1c3fe346-10e7-4dc5-b55c-b6d40ff50124', url: 'https://github.com/CT-RaviTeja66/first.git'
//                     echo "completed"
//                 } 
//             }
//         }       
//           stage('Build') {
//             steps {

//                sh """ 
//                pwd
//                   cp /home/raviteja/test1/* /home/raviteja/test2/
//                 """
//             }
//         }
        
//         // Add more stages for your pipeline
//         // ...
//     }
// }
