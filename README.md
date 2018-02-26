# WordPress
Hera we’ll use terraform to define a WordPress website and deploy it to AWS. We are going to create: 
1.A standalone EC2 instance with Bitnami WordPress Multisite installed using ami from bitnami
 https://aws.amazon.com/marketplace/fulfillment?productId=2f1d4d67-324b-41d7-8af9-b7860d269c6d
2.A security group to restrict access to the server and allow SSH from our local machine An elastic IP so that DNS mappings work if the server is rebooted A root device that won’t get deleted with the instance, so that if the server dies, we still have the website data.
