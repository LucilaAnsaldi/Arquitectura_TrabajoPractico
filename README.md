
## This is the final integrative project for the "Arquitectura en Sistemas" course.

#### Tecnicatura Universitaria en Programación - Universidad Austral
#### Professor: Joaquin Romero
#### Students: Lucila Ansaldi, Sebastián Comparada, Olivia Luciano, Victoria Svaikauskas
<hr />
To download the Contact Agenda application, please follow these steps:

1) Open the Ubuntu terminal.

2) To run commands with administrator privileges, enter the following command:
 ~~~  
 sudo su
 ~~~
  Then enter your Ubuntu password and press ENTER.

3) If you don't have Git on your computer, run the following command to install it:
~~~
apt-get install git
~~~
4) Clone the project using the following command:
~~~
git clone https://github.com/LucilaAnsaldi/Arquitectura_TrabajoPractico.git
~~~
5) Navigate to the repository folder by running the following command:
~~~
cd Arquitectura_TrabajoPractico
~~~
6) Next, give execution permissions to the installation file to be able to run it later. This file contains the installation commands for Docker and Docker Compose. Enter the following in the console:
~~~
chmod +x ./instalaciones.sh
~~~
~~~
./instalaciones.sh
~~~
7) To navigate to the file containing the project, run:
~~~
cd proyecto_arq
~~~
8) Finally, to start the application, type the following command:
~~~
docker-compose up
~~~
9) Now everything is ready! Go to your preferred web browser and enter the following in the navigation bar:
~~~
localhost:80
~~~
  --- You should see your new Contact Agenda application on the screen. ---

