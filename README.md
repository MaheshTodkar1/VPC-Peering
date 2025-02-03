# VPC-Peering
AWS VPC Peering project demonstrating a cross-region peering connection between Mumbai (ap-south-1) and Tokyo (ap-northeast-1) VPCs. Includes step-by-step instructions, route table configurations, security group updates, and connectivity testing.




Project Overview
This project demonstrates how to establish a VPC Peering connection between two AWS regions:

Mumbai (ap-south-1) → 10.0.0.0/16
Tokyo (ap-northeast-1) → 192.0.0.0/16
The setup enables private communication between VPCs without using the public internet.


Steps Involved
1. Create a VPC Peering Connection
Initiate peering request from Mumbai to Tokyo.
Accept the request in Tokyo.
2. Update Route Tables
Add necessary routes in both VPCs to allow traffic flow.
3. Configure Security Groups
Allow ICMP (ping) and necessary ports for communication.
4. Test Connectivity
Use ping to verify communication between instances in both regions.


Project Documentation
All detailed steps and screenshots are included in the Word document (VPC-Peering-Project.docx).

Screenshots
Here are some key screenshots from the project:

Technologies Used
AWS VPC Peering
Route Tables
Security Groups
ICMP Traffic Testing
