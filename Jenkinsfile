pipeline {
			agent{
						label{
								label "built-in"
								customWorkspace "/mnt/httpd1"
							}
			}
			
			stages {
			        stage("stage-1"){
									steps {
											sh "yum install httpd -y *"
											sh "service httpd start"
											echo "hello all" >>/var/www/html/index.html
											sh "chmod 777 /var/www/html/index.html"
									
									}
					}
			
				
				}
				
				}			
			
