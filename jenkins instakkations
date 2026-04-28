9 11 17 23  27 28 30

Approach 4 :- Install Jenkins On Ubuntu    (this is production / real time approach)

This installation is specific to systems operating on Ubuntu.   Follow the below steps:  https://www.jenkins.io/doc/book/installing/linux/ 
Step 1: Install Java                           


sudo apt update                
java -version

sudo apt install openjdk-21-jdk -y            


Step 2: Add Jenkins Repository i.e key

sudo wget -O /etc/apt/keyrings/jenkins-keyring.asc https://pkg.jenkins.io/debian-stable/jenkins.io-2026.key


Step 3: Add Jenkins repo to the system i.e source list


echo "deb [signed-by=/etc/apt/keyrings/jenkins-keyring.asc]"  https://pkg.jenkins.io/debian-stable binary/ | sudo tee  /etc/apt/sources.list.d/jenkins.list > /dev/null


Step 4: Install Jenkins
sudo apt update
 sudo apt install jenkins
Step 5: Verify installation


systemctl status jenkins

Step 6: Once Jenkins is up and running, access it from the
link: http://localhost:8080    or the IP of virtual machine like xx.xx.xx.xx:8080

Get the initial admin pwd from command  cat /var/lib/jenkins/secrets/initialAdminPassword
Start, Stop & Restart Jenkins
$ sudo service jenkins restart
$ sudo service jenkins stop
$ sudo service jenkins start


-----------

Default Jenkins Plugins installed on Runtime 

Matrix Authorization Strategy LDAP Email Extension Mailer Dark Theme
commons-lang3 v3.x Jenkins API
Ionicons API
Folders
OWASP Markup Formatter
ASM API
JSON Path API
Structs
Pipeline: Step API
commons-text API
Token Macro
Build Timeout
bouncycastle API
Credentials
Plain Credentials
Variant
SSH Credentials
Credentials Binding
SCM API
Pipeline: API
Timestamper
Caffeine API
Script Security
Pipeline: Supporting APIs
Plugin Utilities API
Font Awesome API
Bootstrap 5 API
Jackson Annotations 2 API
SnakeYAML Engine API
Woodstox Core API
Jackson 3 API
JQuery3 API
ECharts API
Prism API
Display URL API
Checks API
JUnit
Matrix Project
Resource Disposer
Workspace Cleanup
Ant
OkHttp
JavaBeans Activation Framework (JAF) API
JAXB
JSON Api
Jakarta Activation API
SnakeYAML API
Jakarta XML Binding API
Jackson 2 API
Apache HttpComponents Client 4.x API
Pipeline: Job
Gradle
Pipeline: Milestone Step
Durable Task
Pipeline: Nodes and Processes
Pipeline: Build Step
Pipeline: SCM Step
Pipeline: Groovy
Pipeline: Groovy Libraries
Joda Time API
Pipeline: Model API
Pipeline: Stage Step
Pipeline: Declarative Extension Points API
Jakarta Mail API
Instance Identity
Mailer
Branch API
Pipeline: Multibranch
Pipeline: Stage Tags Metadata
Pipeline: Input Step
Pipeline: Basic Steps
Pipeline: Declarative
Pipeline
Java JSON Web Token (JJWT)
GitHub API
Mina SSHD API :: Common
Mina SSHD API :: Core
Gson API
Git client
Git
GitHub
GitHub Branch Source
Pipeline: GitHub Groovy Libraries
Metrics
Pipeline Graph View
Git
EDDSA API
Trilead API
SSH Build Agents
Matrix Authorization Strategy
LDAP
jsoup API
Email Extension
Mailer
Theme Manager
Dark Theme
** - required dependency


Jenkins 2.555.1
