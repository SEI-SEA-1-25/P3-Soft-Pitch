# Soft Pitch 

## 1. **00:00 - 01:00: Elevator Pitch**

A space for special needs persons and special needs family/caregivers to plug in to their local communities, connect, share tips & resources. 

## 2. **1:00 - 3:00: User Stories**

MVP:
* Linking into the local community for persons with similar special needs – Aspergers, paraplegics, etc.
* User will be connected to others in their geographical area
* Users can submit topics for discussion
* Users can comment on others posts
Stretch:
* User can view Yelp wheelchair-accessability scores on an interactive map
* Top features(locations of top caregivers + PT/OT centers, doctors, childcare centers)
* Roadmap:
* Right-Size geographical zoning for rural regions



## 3. **3:00 - 5:00: How**

Mongoose/MongoDB, React, Express, Node, Bootstrap

User Collection:
* Email
* Username
* Hashed password
* Relation to person with needs
* Geographic Location
* Topics of Interest (ex: wheelchair accessibility, local meetups)
* Disabilities
Post Collection:
* Title
* Discussion Tags
* Content
* comment ids(foreign key) linked under the post
* User ID (foreign key)
* number of likes
Comment Collection:
* Content
* Comment that it replies to
* Post ID (foreign key)
* User ID who posts (foreign key)
* Number of likes
Search/Filtering

Stretch:
* Zip Code or Location API Or Database
* Business accessibility/accomodation ratings API (Gmaps, yelp, or similar)
* Search Algorithm
* Allow users to upload pictures/files (ie photo of ramp, profile photo)
* Optional Anonymity 


## 4. **6:00 - 7:00: Resource Ask**

* Outlining structure/architecture of app, planning
* Helping determine the right resources for MVP
* Any API keys that are available to GA instructional staff
* $100 budget to pay for API calls
* Help with specific APIs

## 5. **7:00 - 10:00: Q&A** 