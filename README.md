## Angular learning repository.
<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fsg.com.mx%2Frevista%2F56%2Fangular&psig=AOvVaw0kVx8l_P-np-O2gTaje5FI&ust=1611245853086000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJim1N_0qu4CFQAAAAAdAAAAABAE" width="200px">

### Steps to install/work_with angular in Ubuntu 18.04 LTS
1) First we check all packages are uptaded/upgraded:
```
sudo apt update
sudo apt upgrade
```

2) Before installing angular, first we must install Node Js and Node Package Manager (npm)
```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo npm install npm@latest -g
```

3) Installing CLI Angular in Ubuntu
```
sudo npm install -g @angular/cli
```

4) Checking angular version in terminal
```
ng --version
```

5) Angular CLI use git to deploy neccesary modules, that's why we need to have git configured
```
git config --global user.email "correo@electronico.com"
git config --global user.name "usuario"
```

6) Creating a new angular version
```
ng new application-name
```

7) Launch an angular application
```
cd application-name
npm start
```
