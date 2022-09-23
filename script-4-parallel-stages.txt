pipeline {

		agent {
		
				label 'built-in'
		}
		
		stages {
		
			stage ('parallel-stages'){
			
			parallel {
			
			stage ('sleep-1'){
			
				steps {
				
						sleep 10
				
				}
		
			
			}
			
			stage ('sleep-2'){
			
				steps {
				
						sleep 10
				
				}
		
			
			}
			
			stage ('sleep-3'){
			
				steps {
				
						sleep 10
				
				}
		
			
			}

			
			}


}
}
}

