
#iOS examples showing how to connect mobile native iOS UI controls to LoopBack services



##Getting Started

1. Install and configure the StrongLoop Suite on your dev environment.  more information on installing LoopBack can be found in the [ StrongLoop Products ](http://strongloop.com/products)

2. Download or clone this repo to your local machine from github [loopback-mobile-getting-started ](https://github.com/strongloop-community/loopback-mobile-getting-started) to a folder on iOS development machine
```sh
$ git clone https://github.com/strongloop-community/loopback-examples-ios.git
$ cd loopback-examples-ios
```

3. Start the LoopBack Node Server 
```sh
$ node loopback-nodejs-server/server/server.js 
```

4. inject some demo data
```sh
#This script needs to be updated to include the required fields.
./initialize-data.sh
```

5. Open and Run ( CMD-R ) one of the sample projects 

###Example apps

![Image](screenshots/sample-examples-ios-all.png?raw=true)

####UITableView with CRUD
![](screenshots/tableview.png?raw=true)

####MapView with Get All, Get Nearest, Get Nearest 5 
![](screenshots/mapview.png?raw=true)

####Remote Method
![](screenshots/remote.png?raw=true)




<!--Broken Link, githalytics seems to no longer exist: [![githalytics.com alpha](https://cruel-carlota.pagodabox.com/d2ee0a3325036377aca0f548c0d27602 "githalytics.com")](http://githalytics.com/strongloop-community/loopback-examples-ios)-->

