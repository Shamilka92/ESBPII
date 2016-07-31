#Lab3

##Creating an Amazon RDS 

####*Step1:* Choose Instances from RDS Dashboard. Select Launch DB Instance.
![screenshot 162](https://cloud.githubusercontent.com/assets/20286032/17275132/3d660f34-571b-11e6-93d0-5a860fcc6340.png)


####*Step2:* Choose MySQL from ‘Select Engine’ tab.
![screenshot 163](https://cloud.githubusercontent.com/assets/20286032/17275134/40e6dbe8-571b-11e6-8a38-9ad151561622.png)


####*Step3:* Select MySQL under ‘Dev/Test’ category. Then proceed to next step.
![screenshot 164](https://cloud.githubusercontent.com/assets/20286032/17275135/420b9478-571b-11e6-9edd-2e9f2efda312.png)


####*Step4:* Specify the DB details. (Instance Specifications and Settings) 
![screenshot 165](https://cloud.githubusercontent.com/assets/20286032/17275136/435b4526-571b-11e6-8f9a-7093b3993052.png)


####*Step5:* Fill the required fields.DB Instance Class, Multi-AZ Deployment, Storage Type. Then provide DB instance identifier, a master username and a master password.
![screenshot 166](https://cloud.githubusercontent.com/assets/20286032/17275137/4afcb40e-571b-11e6-9d3f-60dfc001f555.png)


####*Step6:* Give a database name in ‘Configure Advanced Settings’ tab. (Database Options) Choose ‘No’ in Enable Enhanced Monitoring. (Monitoring) and then Click ‘Launch DB Instance’.
![screenshot 167](https://cloud.githubusercontent.com/assets/20286032/17275138/4b840332-571b-11e6-83a6-1485742a967b.png)


####*Step7:* Click on ‘View Your DB Instance’.
![screenshot 168](https://cloud.githubusercontent.com/assets/20286032/17275139/4c770d8e-571b-11e6-8bc5-4e864f39b391.png)


####*Step8:* Wait until the instance status changes to ‘available’ from ‘creating’. Copy the endpoint details without the port number.
![screenshot 169](https://cloud.githubusercontent.com/assets/20286032/17275140/4f19e6c4-571b-11e6-9f74-369f59a57809.png)


####*Step9:* Start MySQL workbench and create a new connection.
![screenshot 170](https://cloud.githubusercontent.com/assets/20286032/17275141/4ff9d752-571b-11e6-86ab-9e8b52f9dcb1.png)


####*Step10:* Provide a connection name. Give the copied endpoint details as the hostname. Provide the master username you used before as the username.
![screenshot 171](https://cloud.githubusercontent.com/assets/20286032/17275142/5113dfca-571b-11e6-8534-694fb292872a.png)


####*Step11:* Click on ‘Store in Vault’ and provide the Master Password you given previously as the password.
![screenshot 172](https://cloud.githubusercontent.com/assets/20286032/17275143/522d8d16-571b-11e6-9c5a-d727350b9c31.png)


####*Step12:* You will be prompted to the newly created DB.
![screenshot 173](https://cloud.githubusercontent.com/assets/20286032/17275144/530b5fd8-571b-11e6-8dfd-9cf13156e707.png)


####*Step13:* Delete the created DB Instance.
![screenshot 174](https://cloud.githubusercontent.com/assets/20286032/17275145/54755252-571b-11e6-96e6-2b2f7e761aeb.png)
![screenshot 175](https://cloud.githubusercontent.com/assets/20286032/17275146/57157b90-571b-11e6-8b73-33d567f37f35.png)
![screenshot 176](https://cloud.githubusercontent.com/assets/20286032/17275147/580ab5c4-571b-11e6-82c7-c3d4384ea23f.png)



