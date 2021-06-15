# Jatis Subversion Training

# Running Docker Subversion
docker-compose up -d

subversion path: 127.0.0.1/svn

subversion admin path: 127.0.0.1/svnadmin

# Creating User and Password fo Subversion Server
docker exec -t #container_name htpasswd -b /etc/subversion/passwd #username #password

# Setup SVNAdmin
Subversion authorization file: /etc/subversion/subversion-access-control

User authentication file: /etc/subversion/passwd

Parent directory of the repositories (SVNParentPath): /home/svn

Subversion client executable: /usr/bin/svn

Subversion admin executable: /usr/bin/svnadmin
