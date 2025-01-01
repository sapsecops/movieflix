Project-1 ==> Achieve Path-Based Routing Using AWS Application Load Balancer

        Step:1 ==> Create 3 Ec2 Instances 
                        1. Instance-1 ==> Install Nginx and Deploy Homepage Code
                        2. Instance-2 ==> Install Nginx and Deploy Movies Code
                        2. Instance-3 ==> Install Nginx and Deploy Songs Code

        Step:2 ==> Create Target Group
        Step:3 ==> Create AWS Application Load Balancer and achieve the Path-Based Routing

                Achieve this

	                1. When i hit filmy.com ==> it will redirect to Home page
	                2. when i hit filmy.com/movies ==> it will redirect to Movies page
	                3. when i hit filmy.com/songs ==> it will redirect to songs page

        Step:4 ==> Create AWS Application Load Balancer and achieve the Host-Based Routing

                 Achieve this

   			1. When i hit filmy.com ==> it will redirect to Home page
	                2. when i hit movies.filmy.com ==> it will redirect to Movies page
	                3. when i hit songs.filmy.com ==> it will redirect to songs page


Project-2 ==> Achieve Path-Based Routing Using AWS Application Load Balancer in EKS Using Ingress
        
        Step:1 ==> Create Docker Images of your Homepage, movies, games, songs
        Step:2 ==> Create EKS Cluster
	Step:3 ==> Deploy your Home page 
        Step:4 ==> Deploy your Movies page
        Step:5 ==> Deploy your Songs page 
        Step:6 ==> Deploy Ingress Controller
       
        # We learn ALB Load Balancer using Ingress
        Step:7 ==> Deploy ALB Ingress Object  [Achieve the Path-Based Routing using Ingress]
                        1. When i hit filmy.com ==> it will redirect to Home page
                        2. when i hit filmy.com/movies ==> it will redirect to Movies page
                        3. when i hit filmy.com/songs ==> it will redirect to songs page
        Step:8 ==> Deploy ALB  Ingress Object  [Achieve the Host Routing using Ingress]
                        1. When i hit filmy.com ==> it will redirect to Home page
	                2. when i hit movies.filmy.com ==> it will redirect to Movies page
	                3. when i hit songs.filmy.com ==> it will redirect to songs page
        # We learn NLB Load Balancer using Ingress
