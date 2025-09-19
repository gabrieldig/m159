# Berechtigungen

![alt text](image-1.png)

Für die Berechtigungen habe ich Gruppen erstellt, die mit *V* beginnen, und die entsprechenden Abkürzungen für die verschiedenen Abteilungen verwendet:
Daten -> DAT
Abteilung -> ABT
Pool -> PL
Buchhaltung -> BUC
Externe -> EXT
Intern -> INT
Promoter -> PRO
Sekretariat -> SEK
Geschäftsleitung -> GL


# AWS Managed AD
![alt text](image-2.png)



# Admin tool Center


## EC2
Die Ec2-Instanz ist mit dem AWS Managed AD verbunden.
DAher muss sie im Public Subnet sein, damit sie den AD-Server erreichen kann.
![alt text](image-3.png)

IP: 10.100.128.10
PW: 5jfbkn&q1lu0p6A%v?P8u-SOD5Ve7DUq

## NatGateway
![alt text](image-3.png)

![alt text](image-4.png)