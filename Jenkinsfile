@Library('github.com/TYPO3-infrastructure/jenkins-pipeline-global-library-chefci') 
def pipe = new org.typo3.chefci.v1.Pipeline()
pipe.execute([lint: [foodcritic: [epicFail: 'any']]])
