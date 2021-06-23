@Library(['sharedlib@dev']) _
cicd {
    applicationName = 'petclinic'
    buildNode = 'docker'
    mvnGoals = 'clean package'
    pomFileLocation = 'pom.xml'
    executeMavenGoal = 'no

    junitReportLocation = 'target/surefire-reports/*.xml'
    executeUnitTest = 'no'
    
    executeSonar = 'no'
    sonarProjectName = ''
    sonarProjectKey = ''
    sonarProjectVersion = ''
    sonarProjectLanguage = ''
    sonarSources = ''
    sonarBinaries = ''
    sonarCoverageReportsPath = ''
    coverageExclusions = ''
    
    executeNexusIQ = 'no'
    nexusAppName = ''
    packaging = 'jar'
    packagePath = 'target/*.jar'

    emailRecipientList = ''
    }
