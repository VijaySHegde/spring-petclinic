@Library(['sharedlib@dev']) _
cicd {
    applicationName = 'petclinic'
    buildNode = 'docker'
    mvnGoals = 'clean package'
    pomFileLocation = 'pom.xml'
    executeMavenGoal = 'yes'
    executeCoverage = 'YES'

    junitReportLocation = 'target/surefire-reports/*.xml'
    executeUnitTest = 'yes'
    
    executeSonar = 'no'
    sonarProjectName = 'petclinic'
    sonarProjectKey = 'org.petclinic'
    sonarProjectVersion = '1.0'
    sonarProjectLanguage = 'java'
    sonarSources = 'src'
    sonarBinaries = 'target/classes'
    sonarCoverageReportsPath = ''
    coverageExclusions = ''
    
    executeNexusIQ = 'no'
    nexusAppName = 'petclinic'
    packaging = 'jar'
    packagePath = 'target/*.jar'

    emailRecipientList = 'hegdevijay118@gmail.com'
    }
