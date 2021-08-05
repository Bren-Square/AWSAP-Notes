# AWSAP-Notes

These are personal notes that I am taking as I work my way through A Cloud Guru's AWS Architect Pro course. 

Please note that I cannot certify that these notes are 100% correct as things change quite rapidly in the cloud world. They are simply my notes as I learned things. 

---
## The Exam

All of AWS' test questions are based on [Bloom's Taxonomy](https://en.wikipedia.org/wiki/Bloom%27s_taxonomy). As this is a professional exam (not associate), the expectation is that the student will be in phase two of the taxonomy where you analyze/apply/evaluate the content domain. 

**NOTE:** Some of the questions on the exam are beta questions which will not be scored against you. 

**NOTE:** AWS' documentation states that a technology should be GA for about 6 months before they will consider having it on their exams. This means that most brand new tech will not be featured. 

**NOTE:** Make sure to read all of the supplemental material as it fills gaps in the required information that is not covered in the course. 

I will link all white papers I find below for later reading: 

---

## White Papers

- Link them here. 

--- 

## Data Stores 

#### Key Concepts/Terms

**Three Types of Data Store:**
- **Persistent Data Stores** - Durable and sticks around after reboot. 
  - EX: Glacier/RDS
- **Transient Data Stores** - Temporarily stored so that it can be passed along to another service or storage medium. 
  - EX: SQS/SNS
- **Ephemeral Data Stores** - Does not persist to disk. You reboot, you lose. 
  - EX: EC2 Instance Store or Memcached/Redis

**IOPS vs. Throughput**
    - **IOPS:** Measure of how fast we can read/write to a device. 
    - **Througput:** Measure of how much data can be moved at a time

**Consistency**
 - Consistency is far better than rare moments of greatness - Scott Ginsberg - Consistency in data stores regards the rules with which that particular data store behaves when handling the data. In theory, the data store should always follow its consistency model

 **Consistency Models**
 - **ACID:** (Think MySQL)
    - **A**tomic: Transactions are all or nothing. They happen or they don't. 
    - **C**onsistent: Transactions must be validated (think ANSI) or they will not happen. 
    - **I**solated: One transaction can't mess with another. 
    - **D**urable: Completed Transaction must stick around. 
 - **BASE:** (Think Fastly)
   - **B**asic **A**vailability - Values must be present even if stale
   - **S**oft-state - Might not be instantly consistent across all stores
   - **E**ventual Consistency - Achieved at some point. Eventually.


#### S3



#### Glacier

#### Elastic Block Storage

#### Elastic File System

#### Storage Gateway

#### WorkDocs

#### EC2 Databases

#### RDS

#### DynamoDB

#### Redshift

#### Neptune

#### Elasticache

---

## Networking

--- 

## Security

--- 

## Migrations

--- 

## Architecture at Scale 

---

## Business Continuity

--- 

## Deployment and Ops Management

--- 

## Cost Management