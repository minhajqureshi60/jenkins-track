Added a new file index.html
steps for launching jenkins with github
 1  sudo yum install git
    2* 
    3  sudo amazon-linux-extras install java-openjdk11
    4  sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins.io/redhat/jenkins.repo
    5  sudo rpm  --import http://pkg.jenkins-ci.org/redhat/jenkins.io.key
    6  sudo yum install jenkins
    7  sudo service jenkins status
    8  sudo service jenkins start
    9  sudo service jenkins status
   10  sudo cat /var/lib/jenkins/secrets/initialAdminPassword
   11  git clone https://github.com/minhajqureshi60/jenkins-track.git
   12  cd jenkins-track
   13  vi index.html
   14  vi README.md
   15  git status
   16  git log
   17  git add .
   18  git status
   19  git commit -m "Added a index.html file"
   20  git remote -v
   21  git push
   22  cd /var/lib/jenkins
   23  ls
   24  cd workspace
   25  ls
   26  history
