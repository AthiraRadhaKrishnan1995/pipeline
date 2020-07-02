node{
	    stage('SCM Checkout'){
	      git ' https://github.com/AthiraRadhaKrishnan1995/pipeline.git '
	     }
	     stage('Compile-Package'){
	      sh '/opt/apache-maven-3.6.3/bin/mvn -Dtest=GooglePage test -DfailIfNoTests=false'
	     }
	}
