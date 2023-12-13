# New York Times Article Hub

## A first-stage cloud system, experimental tool to explore New York Times articles. Built upon AWS S3 and RDS, MySQL, NodeJS, Express, Javascript, and Python

*Created by Griffin Minster, Macy Bosnich, Will Hoffmann, and Patrick Hoey* \
*Northwestern University COMP_SCI 310: Scalable Software Architecture*

### Components
- User communicating with text-based Python frontend client
- Client using REST framework to talk to the Javascript backend server
- Server communicating with New York Times API to find articles
- Server saves designated articles in AWS S3
- Server saves various article information in DB, run on AWS S3 


*Server currently run "pseudo-locally" on Replit. Future versions will host on AWS EC2*
