pipeline 
{ 
    agent any
    
    stages 
    {
        stage ('HelloWorld') 
        {
            steps 
            {
                echo "Hello World"
            }
            post
            {
                success
                {
                    echo "Se ha saludado correctamente"    
                }
                failure
                {
                    echo "Se ha producido un error en el saludo"    
                }
      
            }
        }
    }
}
