# GCP.CP100A Keynotes

## Why choose GCP
1. GAE(Google App Engine) can automatically scale out/scale in
2. Computing, big data, machine learning
3. Sub-hour billing (by 10 minutes), friendly pricing
4. Custom machine types, custom detail CPU, RAM
5. laaS for computing and PaaS for app engine

## Infra
1. Data Centers
2. Backbone (for remote backup and its very fast... etc)
3. Points of Presnece(POP)
4. Edge Caching (static data, such as image, html)

## Regions and zones
1. Isolation engine zoom
2. (Suggest)Deploy applications to different zone

## The future
1. Colocation -> VM datacenters -> Global elastic cloud

## Whaz inside
1. Dataproc contains Haddoop, Spark
2. Cloud SQL, including of MySQL, Postgre
3. Natural language
4. Vision API
5. Speech API
6. Translate API
7. more...

## Project
1. Project name/number/id

### Permissions

Use `IAM` function.

> Who/can do what/on what resource

* Owner
* Editor: Deploy application/Modify code/Config
* Viewer: Read-only
* Billing admin: Manage billing

The permission can be assigned to google account, *google group*, service account.

> **Google group**
> Create group with members

> **Service account**
> DO NOT remove or modify the DEFAULT service account in project.

In a company,
1. IAM Resource Hierarchy
2. XPN: Cross Project Network
3. Organization Node (Beta)


### GUI

#### Cloud shell: 
1. Free linux to use, but it will clear what you installed after rebbot
2. Code editor
3. gcloud --help


## Google Cloud SDK
1. Find it in Docker hub
2. Use restful api with token
3. OAuth playground


## Google App Engine and Google Cloud Datastore

### GAE

1. Deploy/Monitor/Scale
2. Example : [Snapchat](https://www.snapchat.com/)
3. Free daily quota, can set limited price and then close service in a day
4. Environment

**Standard**
- Java/Python/Go/PHP
- Auto-scale
- SDKs for sandbox, but no writing to local file system
- Limit on 3rd packages

**Flexible**(Beta)
- Standard runtimes : Java/Python/Go/Node.js, with no sandbox contraints
- Local development relies on Docker
- Can access App Engine Service
- Support on 3rd packages

### GCD
1. NoSQL
2. AES encrypt on data
3. Auto-scale


## Network

### Google Cloud Interconnect
- Carrier interconnect
- Direct Peering
- CDN interconnect

### Google Cloud DNS
- Highly available and scalable
- DDOS protection

### Load Balance
- HTTP(S) load balancing
- Quick response with nearest location


## Google Stackdriver
- Monitor/Log/Dashboard
- Open source engine
- 3rd package support

## Google Cloud Functions
- Micro-service


## Google Cloud Storage (GCS)
- BLOB(Binary large object storage)
- Could be accessed by 3rd party tools: Cloud Storage Fuse

1. Multi-regional
2. Regional
3. Nearline
4. Coldline







