# smilescare
Live Fundraiser used at Smiles.Care fundraising event.

##Installation instructions
1. Install Node.Js LTS
  https://nodejs.org/en/
 
 2. Install MongoDB Community Server
  https://www.mongodb.com/download-center?ct=false#community
  
 3. Create a new folder in C drive and name it "dbdata"
  
 4. Open a CMD window and execute following commands in order: </br>
      cd 'C:\Program Files\MongoDB\Server\3.4\bin'</br>
      mongod --dbpath "C:\dbdata"</br>
 
 Now mongo server will start
 
 5. Open a seprate CMD window in an empty folder and execute following commands in order </br>
 
 git clone https://github.com/lavisht22/smilescare.git</br>
 npm install (will take some time)</br>
 npm start </br>
 
 6. Now connect two devices to same network and open the following links:
  http://localhost:4000/new   on the device that is connected to projector
  http://ipofthehost:4000/donate on the donation desk device
 
 
  
