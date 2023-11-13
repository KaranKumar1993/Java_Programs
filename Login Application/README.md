The login application let's you login using the predefined credentials given in the Database Setup document. 
Follow the instructions below to launch the application. Requires <b>Java 17</b> and above.

1. Install the database <b>first</b>. Instructions are given in the <b>Database Setup</b> document.
2. Download <b>all</b> three rar files and extract any <b>one</b> of them. The three files <b>must</b> be in the same location.
3. After extracting, navigate to the </b>target</b> folder and run <b>cmd</b> there
4. Run the command: <b>java -jar simple-form-0.0.1-SNAPSHOT.jar</b>
5. Open a browser and type <b>localhost:8080/</b>
6. Login using the credentials given in the document
7. Upon successful login, there should be a welcome page that shows the <b>name, username and role (manager/user)</b>.
8. If the user has a <b>manager</b> role, the welcome page will have a <b>link</b> to access a restricted webpage.
