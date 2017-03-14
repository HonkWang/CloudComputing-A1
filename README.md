# CloudComputing-A1
## Twittmap

Step 1: Creating Amazon Elasticsearch domain

Step 2: Creating Index and Type 

tep 3: Streaming Tweets Run Twitter StreamingAPI.ipynbs

Step 4: Creating Web UI Create a Web UI using html and javascript to let users choose any keyword from 10 (default) via a drop-down box ['Trump', 'Hilary','Obama','Amazon','Google','','Python','Technology','Stanford','Columbia'] Require socket.io (version 1.2.1 or later to escape special character) to send the keyword to back-end Initialize Google Map using Google Maps API

Step 5: Searching Tweets Using node.js express framework as back-end server to connect to elasticsearch Query elasticsearch according to keyword selected by users from the front-end Once ES responds to the server, the server then sends the response as JSON payload to the front-end

Step 6: Visualizing Filtered Tweets Locate tweets and place a marker with anchor set to geometry information Add a listener Event for each marker. Whenver the user clicks the marker, an infowindow is created and popped out. Previous infowindow, is any, is closed

Step 7: Deploying to Amazon Elastic Beanstalk Since the Linux VMs do not allow listening on port 80, it's necessary to configure the application to listen on some other port (we used 2222) Make an archive of all files in the directory nodejs (except node_modules), and deploy it to Amazon Elastic Beanstalk Configure the Elastic Load Balancer to forward traffic from port 80 to port 2222, and add corresponding rules to the security groups
