pipeline {
        agent any
	stages {
	       stage('image_build'){
	                      steps {
			           sh '''
			                  echo "building Docker image"
				          docker run -itd centos:7
                                 '''

			             }
			            }
	       stage('image_tagging'){
	                        steps {
			             sh ''' 
				             echo "tagging the image...." 
					     docker image tag image_pipeline1:latest Ravi/image_pipeline1:latest
					 '''    
				     
			               }
			              }

	       }

	 }      
