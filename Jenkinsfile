def workspace
node {
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/srinivaspettigadi/DevOpsClassCodes.git']]])
        workspace =pwd()
    }
    stage('code analysis')
    {
        echo "code analysisss"
    }
    stage('build')
    {
        echo "building"
    
    }
    stage('unt testng')
    {
        echo "testing"
    }
    stage('delivered')
    {
        echo "delivered"
    }
}
