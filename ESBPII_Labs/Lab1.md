#LAB-01

## Creating an Amazon EBS-Backed Windows AMI

####*Step1:* Select EC2 web service from Amazon Web Services. Then it will be directed to the EC2 dashboard. Under create instance click the ‘Launch Instance’ to create an Amazon EC2 instance.
![screenshot 109](https://cloud.githubusercontent.com/assets/20286032/17274752/d7664396-570d-11e6-9ed1-e6c8cc9ce992.png)

####*Step2:* Choose the ‘Microsoft Windows Server 2012 R2 Base’ Amazon Machine Image(AMI)
![screenshot 110](https://cloud.githubusercontent.com/assets/20286032/17274753/dc68391c-570d-11e6-8015-2fb75375f77c.png)

####*Step3:*Select an Instance Type and click on ’Review and Launch’ button.
![screenshot 111](https://cloud.githubusercontent.com/assets/20286032/17274754/de1ac5c2-570d-11e6-8efd-5cbdbd44c94b.png)

####*Step4:* Review Instance Launch and click on ‘Launch’ button.
![screenshot 112](https://cloud.githubusercontent.com/assets/20286032/17274755/df9d1594-570d-11e6-8bd8-3a88284f534f.png)

####*Step5:* A popup window will appear whether to select an existing key pair or to create a new key pair. Select ‘Create a new key pair’ and give a key pair name. Then Click on ‘Download key pair’. After that click on ‘Launch Instance’.
![screenshot 113](https://cloud.githubusercontent.com/assets/20286032/17274756/e10ce8be-570d-11e6-98d6-77e7a52ddd8b.png)

####*Step6:* View Instance after launching.
![screenshot 114](https://cloud.githubusercontent.com/assets/20286032/17274757/e25db860-570d-11e6-8968-f083e2e11c70.png)

####*Step7:* Select the created instance and connect. (Here it’s still pending)
![screenshot 115](https://cloud.githubusercontent.com/assets/20286032/17274758/e3c7d622-570d-11e6-8286-0ebda487aedf.png)

####*Step8:* The launched instance is running.
![screenshot 116](https://cloud.githubusercontent.com/assets/20286032/17274759/e4d57b5a-570d-11e6-844d-2f574c66c4fc.png)

####*Step9:* Click on ‘Get Password’ to connect to your instance.
![screenshot 117](https://cloud.githubusercontent.com/assets/20286032/17274760/e613c5ee-570d-11e6-9b04-594d915e15aa.png)

####*Step10:* Give the path of the previously downloaded key.
![screenshot 118](https://cloud.githubusercontent.com/assets/20286032/17274761/e8a396fe-570d-11e6-884d-ad6d62a63ed5.png)

####*Step11:* Decrypt the password.
![screenshot 119](https://cloud.githubusercontent.com/assets/20286032/17274762/e9a9872a-570d-11e6-943d-b719b06024ce.png)

####*Step12:* Note down the user name and the decrypted password.
![screenshot 120](https://cloud.githubusercontent.com/assets/20286032/17274764/eadd6ea4-570d-11e6-9460-640c42d6d07c.png)

####*Step13:* Open Remote Desktop Connection. Provide the public IP of the launched instance. Then log in to Windows Server 2012 R2 using the given user name and the decrypted password.
![screenshot 121](https://cloud.githubusercontent.com/assets/20286032/17274774/74deb91e-570e-11e6-95f3-19e9b909a24a.png)





