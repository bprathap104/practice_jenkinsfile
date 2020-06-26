node {
  stage('Get sources') {
       checkout scm
  }

def externMethod = load "${pwd()}/externalMethod.groovy"

externMethod.lookAtThis "saran"
//externMethod.lookAtMe "prathap"

def externCall = load "${pwd()}/externalCall.groovy"
externCall "saravanan"

}
