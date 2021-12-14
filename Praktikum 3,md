<h4>Nama : Dewa Nusantara MP</h4>
<h4>NIM  : 1202190053</h4>
<h4>Nama : Agi Lobita J.M</h4>
<h4>NIM  : 1202190031</h4>
           
<h3><a href="https://github.com/agisx/Container-LXC-Ubuntu20Server/tree/main/images/Soal%20Praktikum02/ansible">Ansible link github</a><h3>

<h1>Ansbile</h1>
<ol>
  <li>Create a new lxc with the folcan version with the same setup, namely lxc php7 and lxc landing</li>
  sudo lxc-create -n [name] -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --no-validate --server images.linuxcontainers.org 
  <!-- Setup lxc -->
  <ol type="A">
    <h5>Initial Landing and PHP7 Configuration<h5>
    <li>Install net tools, apt install nano net-tools curl</li> 
    
    <li>Change Ip, both are php7 then sudo nano /etc/netplan/10-lxc.yaml</li>
    <ol type="i"> 
      <li>Ip landing : 10.0.3.103, Ip php7 : 10.0.3.101</li>
      
      <li>sudo netplan apply; ifconfig</li>
    </ol>
    <li>Installing ssh and python, apt install openssh-server python</li>
    
    <li>Enable root user, nano /etc/ssh/sshd_config</li>
    
    <li>Restart ssh service, sudo service sshd restart</li>
    <li>Change the password, passwd</li>
    <q>Do it on both lxc</q>
    <li>If you have finished both setup, do: ssh root@lxc_php7.dev and ssh root@lxc_landing.dev, enter the password</li>  
   
  </ol>
  <li>Creating ansible folder, prak2-ansible example</li> 
  <li>Create ansible hosts file group</li>
  
  <li>Check the connection, ansible -i hosts -m ping all -k</li>
  
  <li>Create roles folder</li>  
  <ol>
    <h2>Laravel 8 as landing page</h2>
    <li>Creating ansible file, example deploy-landing-app.yml</li>
    <li>Create to load roles in a folder, for example landing</li>
    <ol type="a">
      <h4>Ansible</h4>
      <li>Host deploy</li>
     
      <li>Install server and laravel requirements</li>
      
      <li>Looking for a repository with php7.4</li>
      
      <li>Install nginx and php7</li>
      
      <li>Clone laravel</li>
      
      <li>Config nginx</li>
      
      <li>Config laravel</li>
      
      <li>Add hosts to hosts file</li>
      
      <li>Nginx template</li>
      
      <li>.env template</li>
      
      <li>Restart php</li>
       
    </ol>  
    <li>Run oh yeah</li>
     
  </ol>
  <ol>
    <h2>Wordpress as blog</h2>
    <li>Creating ansible files, example deploy-blog-app.yml</li>
    <ol type="a">
      <h4>Ansible</h4>
      <li>Host deploy</li>
      
      <li>Install server and wordpress needs</li>
      
      <li>Search repository with php7.4</li>
      
      <li>Install nginx and php7</li>
      
      <li>Clone wordpress</li>
      
      <li>Config nginx</li>
      
      <li>Config wordpress</li>
      
      <li>Add host to hosts file</li>
      
      <li>Nginx template</li>
      
      <li>wp-config template</li>
      
      <li>Restart php</li>
      
      <li>Config db for blog</li>
      
    </ol>
    <li>Run oh yeah</li> 
    
  </ol>
  <li>VM nginx config</li>
  
  <li>Check all</li>
  
</ol>
