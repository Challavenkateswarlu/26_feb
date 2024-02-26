pipeline
	{
	agent any
		stages
			{
			stage("GIT")
				{
				steps
					{
					git "https://github.com/Challavenkateswarlu/26_feb.git"
					}
				}
			stage("Run")
				{
				steps
					{
					sh "python3 main.py"
					sh "java Demo.java"
					}
				}
			}
	}
