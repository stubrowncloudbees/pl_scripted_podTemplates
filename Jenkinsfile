import com.foo.utils.PodTemplates

slaveTemplates = new PodTemplates()

slaveTemplates.dockerTemplate {
    slaveTemplates.mavenTemplate {
        node('label') {
            container('docker') {
                sh 'echo hello from docker'
            }
            container('maven') {
                sh 'echo hello from maven'
            }
        }
    }
}