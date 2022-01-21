# DevOps
AWS ASSIGNMENT 
Q1. HOW TO LOGIN EC2 INSTANCE THROUGH TEMINAL ?
ANS. Go to terminal
     cd Downlods
     chmod 400 .pem file name
     ssh -i .pem file name ubuntu(username)@IP address.
Q2. DIFFERENCE BETWEEN INTERNET GATEWAY AND NAT GATEWAY ?
ANS. Internet Gateway is a way to Internet for the public resources in your AWS Virtual Private Cloud i.e. the resources with public ip address. We can only have 1 IGW per VPC.
     A NAT Gateway allows the private resources in your VPC to access the internet. The internet does not know anything about the private network as it gets the request from the NAT with the public IP address of the NAT Gateway.
Q3. WHAT ARE INBOUND AND OUTBOUND RULES?
ANS. Inbound Rules- Inbound Rules control the incoming traffic of your Instance.
     Outbound Instance- Outbound Rules control the outgoing traffic from your Instance.
Q4. WHERE IS INBOUND AND OUTBOUND LOCATED IN AWS?
ANS. Inside Security Groups when we create EC2 Instance.
Q5. HOW TO CONNECT PUBLIC INSTANCE TO PRIVATE INSTANCE?
ANS.
Q6. HOW TO CHECK PERMISSIONS FOR S3 BUCKET IN TERMINAL?
ANS. 
