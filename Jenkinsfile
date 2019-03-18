pipeline {
  agent any
  stages {
    stage('UnitTests') {
      parallel {
        stage('unit1') {
          steps {
            echo 'fdsa'
          }
        }
        stage('unit2') {
          steps {
            echo 'fdsa'
          }
        }
      }
    }
    stage('SettingUpNodes') {
      parallel {
        stage('client') {
          steps {
            echo 'ggfdsa'
          }
        }
        stage('Peer0') {
          steps {
            echo 'news'
          }
        }
        stage('Peer1') {
          steps {
            echo 'fdsa'
          }
        }
        stage('Peer2') {
          steps {
            echo 'fdsa'
          }
        }
        stage('Peer3') {
          steps {
            echo 'fdsa'
          }
        }
      }
    }
    stage('sendTx') {
      parallel {
        stage('toPeer0') {
          steps {
            echo 'txtxtx'
          }
        }
        stage('toPeer1') {
          steps {
            echo 'dsa'
          }
        }
        stage('toPeer2') {
          steps {
            echo 'txttrxtxtx'
          }
        }
      }
    }
    stage('LeaderComplaint') {
      steps {
        echo '...'
      }
    }
    stage('Success!') {
      steps {
        echo '...'
      }
    }
  }
}