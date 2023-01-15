Jenkins project

Done by Almaz Mullagilov

It is a Jenkins pipeline project which pulls a Jenkins job from a GitHub 
repository. The Jenkins job describes deployment of a Docker container 
with Nginx pre-installed, copies index.html + Nginx config files into the 
created container and restarts Ngninx configuration. It results in one click 
deployment of an Nginx web server based on a Docker container and as GitHub as a code source.


Jenkins job:

![image](https://user-images.githubusercontent.com/117575383/212549105-da78424f-cc5e-48e1-8849-771a599008cf.png)
![image](https://user-images.githubusercontent.com/117575383/212549338-b79bf5f1-564e-426f-94dd-5f617410f225.png)
![image](https://user-images.githubusercontent.com/117575383/212549361-ac0d8b66-cef4-4188-a338-3e0f480ae2fd.png)

Jenkins file configuration (JenkinsFile2.txt) on the GitHub repository:

![image](https://user-images.githubusercontent.com/117575383/212549386-a54f3054-c30f-497b-a734-8d96cf89cf50.png)

Job run results:


Jenkins pipeline output:

![image](https://user-images.githubusercontent.com/117575383/212549403-b0467fb7-8afe-40bc-8059-d1209480f15b.png)

Web server view:

![image](https://user-images.githubusercontent.com/117575383/212549413-79e3b183-c311-474f-9aa2-7d98df2d795c.png)
