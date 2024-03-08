

# The Google Cloud Developer's Cheat Sheet
Every product, feature and service in the Google Cloud family described in <=4 words (with liberal use of hyphens and slashes :smirk:) by the Google Developer Relations Team

Check out the *NEW* [interactive version of the cheat sheet](https://goo.gle/GCdevelopercheatsheet) <img border="1" valign="middle" src="Map&list.gif">

Here are the downloadable versions as well: 

White background:
[High-resolution PNG](Poster-hires.png)
|
[Medium-res PNG](Poster-medres.png)
|
[Low-res PNG](Poster-lowres.png)\
Dark background:
[High-resolution PNG](DarkPoster-hires.png)
|
[Medium-res PNG](DarkPoster-medres.png)
|
[Low-res PNG](DarkPoster-lowres.png)
Desktop Wallpapers: [16:9 (iMac, etc.)](Wallpaper-16-9.png) | [16:10 (Macbook Pro)](Wallpaper-16-10.png) | [4:3 (Older computers)](Wallpaper-4-3.png) | [3:2 (Pixelbook)](Wallpaper-3-2.png)\

<a target="_blank" href="DarkPoster-medres.png"><img border="1" alt="Google Cloud Developer's Cheat Sheet Poster Image" src="DarkPoster-lowres.png"></a>

Text descriptions with links are below

Suggestions for better descriptions? Missing products? Pull requests are welcome on README.md (this file).

Feedback? <img width="40" valign="middle" src="https://storage.googleapis.com/gregsramblings-downloads/Twitter_Logo_Blue.png">[@pvergadia](https://twitter.com/pvergadia) or [@GoogleCloudTech](https://twitter.com/GoogleCloudTech). 

**Note:** This list only includes products that are publicly available. There are several products in pre-release/private-alpha that will not be included until they go public preview, beta or GA.

Fun flashback - [here's the list of products in 2014](https://web.archive.org/web/20140702161745/https://cloud.google.com/products/)

Many of these products have a [free tier](https://cloud.google.com/free/). There is also a [free trial](https://console.cloud.google.com/freetrial) that will enable you try almost everything.

Many of these products have a [visual Google Cloud Sketchnote](https://goo.gle/gcpsketchnote) to provide you a one pager visual overview of what each of these products are and how you can use them.

----------------------------
# All Products
<sup>:link:-Product page</sup>
<sup>:page_facing_up:-Documentation</sup>

### Compute


* **Cloud Functions**: Event-driven serverless functions [<sup>:link:</sup>](https://cloud.google.com/functions/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/functions/docs/)
* **App Engine**: Managed app platform [<sup>:link:</sup>](https://cloud.google.com/appengine/) 
[<sup>:page_facing_up:</sup>](https://cloud.google.com/appengine/docs/)
* **Cloud Run**: Serverless for containerized applications [<sup>:link:</sup>](https://cloud.google.com/run/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/run/docs/)
* **Google Kubernetes Engine (GKE)**: Managed Kubernetes/containers [<sup>:link:</sup>](https://cloud.google.com/kubernetes-engine/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/kubernetes-engine/docs/)
* **Compute Engine**: VMs, GPUs, TPUs, Disks [<sup>:link:</sup>](https://cloud.google.com/compute/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/compute/docs/)
* **Bare Metal Solution**: Hardware for specialized workloads [<sup>:link:</sup>](https://cloud.google.com/bare-metal) 
* **Preemptible VMs**: Short-lived compute instances [<sup>:link:</sup>](https://cloud.google.com/preemptible-vms) [<sup>:page_facing_up:</sup>](https://cloud.google.com/compute/docs/instances/preemptible)
* **Shielded VMs**: Hardened VMs [<sup>:link:</sup>](https://cloud.google.com/shielded-vm/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/security/shielded-cloud/shielded-vm/)
* **Sole-tenant Nodes**: Dedicated physical servers [<sup>:link:</sup>](https://cloud.google.com/sole-tenant-nodes) [<sup>:page_facing_up:</sup>](https://cloud.google.com/compute/docs/nodes)
* **VMware Engine**: VMware as a service [<sup>:link:</sup>](https://cloud.google.com/vmware-engine) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vmware-engine/docs)

### Storage
  
* **Cloud Filestore**: Managed NFS server [<sup>:link:</sup>](https://cloud.google.com/filestore/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/filestore/docs/)
* **Cloud Storage**: Multi-class multi-region object storage[<sup>:link:</sup>](https://cloud.google.com/storage/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/storage/docs/)
* **Persistent Disk**: Block storage for VMs [<sup>:link:</sup>](https://cloud.google.com/persistent-disk/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/compute/docs/disks/)
* **Local SSD**: VM locally attached SSDs [<sup>:link:</sup>](https://cloud.google.com/local-ssd) [<sup>:page_facing_up:</sup>](https://cloud.google.com/compute/docs/disks/local-ssd)
  
### Database 
  
* **Cloud Bigtable**: Petabyte-scale, low-latency, non-relational [<sup>:link:</sup>](https://cloud.google.com/bigtable/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/bigtable/docs/)
* **Cloud Firestore**: Serverless NoSQL document database [<sup>:link:</sup>](https://cloud.google.com/firestore/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/firestore/docs/)
* **Cloud Memorystore**: Managed Redis and Memcached [<sup>:link:</sup>](https://cloud.google.com/memorystore/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/memorystore/docs/)
* **Cloud Spanner**: Horizontally scalable relational database [<sup>:link:</sup>](https://cloud.google.com/spanner/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/spanner/docs/)
* **Cloud SQL**: Managed MySQL, PostgreSQL, SQL Server [<sup>:link:</sup>](https://cloud.google.com/sql/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/sql/docs/)
* **Database Migration Service**: Migrate to Cloud SQL [<sup>:link:</sup>](https://cloud.google.com/database-migration) [<sup>:page_facing_up:</sup>](https://cloud.google.com/database-migration/docs)
* **Cloud SQL Insights**: SQL Inspector [<sup>:link:</sup>](https://cloud.google.com/sql/docs/postgres/insights-overview) [<sup>:page_facing_up:</sup>](https://cloud.google.com/sql/docs/postgres/using-insights)
  
### Data Analytics 
  
* **BigQuery**: Data warehouse and analytics [<sup>:link:</sup>](https://cloud.google.com/bigquery/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/bigquery/docs/)
* **BigQuery BI Engine**: In-memory analytics engine [<sup>:page_facing_up:</sup>](https://cloud.google.com/bi-engine/docs/)
* **BigQuery ML**: BigQuery model training/serving [<sup>:page_facing_up:</sup>](https://cloud.google.com/bigquery-ml/docs/)
* **BigQuery GIS**: BigQuery geospatial functions/support [<sup>:page_facing_up:</sup>](https://cloud.google.com/bigquery/docs/gis)
* **BigQuery Data Transfer Service**: Automated data ingestion service [<sup>:page_facing_up:</sup>](https://cloud.google.com/bigquery-transfer/docs)
* **Connected Sheets**: Spreadsheet interface for (big)data [<sup>:page_facing_up:</sup>](https://cloud.google.com/bigquery/docs/connected-sheets)
* **Cloud Composer**: Managed workflow orchestration service [<sup>:link:</sup>](https://cloud.google.com/composer/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/composer/docs/)
* **Cloud Data Fusion**: Graphically manage data pipelines [<sup>:link:</sup>](https://cloud.google.com/data-fusion/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/data-fusion/docs/)
* **Dataflow**: Stream/batch data processing [<sup>:link:</sup>](https://cloud.google.com/dataflow/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/dataflow/docs/)
* **Dataprep by Trifacta**: Visual data wrangling [<sup>:link:</sup>](https://cloud.google.com/dataprep/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/dataprep/docs/)
* **Dataproc**: Managed Spark and Hadoop [<sup>:link:</sup>](https://cloud.google.com/dataproc/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/dataproc/docs/)
* **Datastream**: Change data capture/replication service [<sup>:link:</sup>](https://cloud.google.com/datastream) [<sup>:page_facing_up:</sup>](https://cloud.google.com/datastream/docs)
* **Pub/Sub**: Global real-time messaging [<sup>:link:</sup>](https://cloud.google.com/pubsub/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/pubsub/docs/)
* **Data Catalog**: Metadata management service  [<sup>:link:</sup>](https://cloud.google.com/data-catalog/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/data-catalog/docs/)
* **Google Data Studio**: Collaborative data exploration/dashboarding [<sup>:link:</sup>](https://datastudio.google.com/overview) [<sup>:page_facing_up:</sup>](https://datastudio.google.com/overviewdocs/)
* **Looker**: Enterprise BI and analytics [<sup>:link:</sup>](https://cloud.google.com/looker)
* **Public Datasets**: Hosted data in BigQuery[<sup>:page_facing_up:</sup>](https://cloud.google.com/public-datasets)


### Hybrid and multi-cloud
* **Anthos**: Enterprise hybrid/multi-cloud platform [<sup>:link:</sup>](https://cloud.google.com/anthos/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/anthos/docs/)
* **Anthos clusters**: Hybrid/on-premises GKE [<sup>:link:</sup>](https://cloud.google.com/anthos/gke) [<sup>:page_facing_up:</sup>](https://cloud.google.com/anthos/gke/docs/on-prem/)
* **Anthos Config Management**:Policy and security automation [<sup>:link:</sup>](https://cloud.google.com/anthos/config-management) [<sup>:page_facing_up:</sup>](https://cloud.google.com/anthos-config-management/docs)
* **Anthos Service Mesh**: Managed service mesh (Istio) [<sup>:link:</sup>](https://cloud.google.com/anthos/service-mesh) [<sup>:page_facing_up:</sup>](https://cloud.google.com/service-mesh/docs)
* **Cloud Run for Anthos**: Serverless development for Anthos [<sup>:link:</sup>](https://cloud.google.com/anthos/run) [<sup>:page_facing_up:</sup>](https://cloud.google.com/run/docs/quickstarts/prebuilt-deploy-gke)
* **Google Cloud Marketplace for Anthos**: Pre-configured containerized apps [<sup>:link:</sup>](https://cloud.google.com/kubernetes-applications) [<sup>:page_facing_up:</sup>](https://cloud.google.com/marketplace/docs/kubernetes-apps)
* **Migrate for Anthos and GKE**: Migrate VMs to GKE [<sup>:link:</sup>](https://cloud.google.com/migrate/anthos/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/migrate/anthos/docs/getting-started)
* **Google Cloud's operations suite**: Monitoring, logging, troubleshooting [<sup>:link:</sup>](https://cloud.google.com/products/operations) [<sup>:page_facing_up:</sup>](https://cloud.google.com/stackdriver/docs)
* **Traffic Director**: Service mesh traffic management [<sup>:link:</sup>](https://cloud.google.com/traffic-director/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/traffic-director/docs/)
* **Apigee API Management**: API management, development, security [<sup>:link:</sup>](https://cloud.google.com/apigee)


### AI and ML

* **Vertex AI**: Managed platform for ML [<sup>:link:</sup>](https://cloud.google.com/ai-platform/) 
* **AutoML**: Custom low-code models [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/training/training)
* **Vertex AI Data Labeling**: Data labeling by humans [<sup>:page_facing_up:</sup>](https://cloud.google.com/data-labeling/docs/)
* **Deep Learning VM Images**: Preconfigured VMs for deep learning [<sup>:link:</sup>](https://cloud.google.com/deep-learning-vm/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/deep-learning-vm/docs/)
* **Vertex AI Workbench**:Jupyter-based environment for Data Science  [<sup>:link:</sup>](https://cloud.google.com/vertex-ai-workbench)  [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/workbench)
* **Deep Learning Containers**: Preconfigured containers for deep learning [<sup>:link:</sup>](https://cloud.google.com/ai-platform/deep-learning-containers/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/ai-platform/deep-learning-containers/docs/)
* **Vertex AI Matching Engine**: Vector similarity searches [<sup>:link:</sup>](https://cloud.google.com/vertex-ai/docs/matching-engine)[<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/matching-engine)
* **Vertex AI Pipelines**: Hosted ML workflows[<sup>:link:</sup>](https://cloud.google.com/ai-platform/pipelines/)
* **Vertex AI Predictions**: Autoscaled model serving [<sup>:page_facing_up:</sup>](https://cloud.google.com/ai-platform/prediction/docs/overview)
* **Vertex AI Training**: Distributed AI training [<sup>:page_facing_up:</sup>](https://cloud.google.com/ai-platform/training/docs/overview)
* **Vertex AI Edge Manager**: Deploy monitor edge inferences [<sup>:page_facing_up:</sup>](https://https://cloud.google.com/vertex-ai/docs/)
* **Vertex Explainable AI**: Understand ML model predictions [<sup>:link:</sup>](https://cloud.google.com/vertex-ai/docs/explainable-ai/overview) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/explainable-ai)
* **Vertex AI Feature Store**: Managed ML feature repository [<sup>:link:</sup>](https://cloud.google.com/vertex-ai/docs/featurestore) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/featurestore/overview)
* **Vertex ML Metadata**: Artifact, lineage, and execution tracking [<sup>:link:</sup>](https://cloud.google.com/vertex-ai/docs/ml-metadata) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/ml-metadata/introduction)
* **Vertex AI Model Monitoring**: Monitor models for skew/drift [<sup>:link:</sup>](https://cloud.google.com/vertex-ai/docs/model-monitoring) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/model-monitoring/overview)
* **Vertex AI Tensorboard**: Managed TensorBoard for ML-experiment Visualization [<sup>:link:</sup>](https://cloud.google.com/vertex-ai/docs/experiments) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/experiments/tensorboard-overview)
* **Vertex AI Vizier**: black-box hyperparameter tuning [<sup>:link:</sup>](https://cloud.google.com/vertex-ai/docs/vizier/overview) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vertex-ai/docs/vizier)
* **Speech-To-Text**: Convert audio to text [<sup>:link:</sup>](https://cloud.google.com/speech/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/speech/docs/)
* **Talent Solutions**: Job search with ML [<sup>:link:</sup>](https://cloud.google.com/job-discovery/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/job-discovery/docs/)
* **Text-To-Speech**: Convert text to audio [<sup>:link:</sup>](https://cloud.google.com/text-to-speech/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/text-to-speech/docs/)
* **Cloud TPU**: Hardware acceleration for ML [<sup>:link:</sup>](https://cloud.google.com/tpu/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/tpu/docs/)
* **Cloud Translation**: Language detection and translation [<sup>:link:</sup>](https://cloud.google.com/translate/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/translate/docs/)
* **Cloud Video Intelligence API**: Scene-level video annotation [<sup>:link:</sup>](https://cloud.google.com/video-intelligence/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/video-intelligence/docs/)
* **Cloud Vision**: Image recognition and classification [<sup>:link:</sup>](https://cloud.google.com/vision/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vision/docs/)
* **Contact Center AI**: AI in your contact center[<sup>:link:</sup>](https://cloud.google.com/solutions/contact-center/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/solutions/contact-center/)
* **Dialogflow**: Create conversational interfaces [<sup>:link:</sup>](https://cloud.google.com/dialogflow-enterprise/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/dialogflow-enterprise/docs/)
* **Document AI**: Analyze, classify, search documents [<sup>:link:</sup>](https://cloud.google.com/solutions/document-understanding/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/document-understanding/docs/)
* **Recommendations AI**: Create custom recommendations [<sup>:link:</sup>](https://cloud.google.com/recommendations/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/recommendations-ai/docs/)
* **Vision Product Search**: Visual search for products [<sup>:page_facing_up:</sup>](https://cloud.google.com/vision/product-search/docs/)

### Networking 
  
* **Carrier Peering**: Peer through a carrier [<sup>:page_facing_up:</sup>](https://cloud.google.com/interconnect/docs/how-to/carrier-peering)
* **Direct Peering**: Peer with Google Cloud [<sup>:page_facing_up:</sup>](https://cloud.google.com/interconnect/docs/how-to/direct-peering)
* **Dedicated Interconnect**: Dedicated private network connection [<sup>:page_facing_up:</sup>](https://cloud.google.com/interconnect/docs/details/dedicated)
* **Partner Interconnect**: Connect on-prem network to VPC [<sup>:page_facing_up:</sup>](https://cloud.google.com/interconnect/docs/concepts/partner-overview)
* **Google Cloud Armor**: DDoS protection and WAF [<sup>:link:</sup>](https://cloud.google.com/armor/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/armor/docs/)
* **Cloud CDN**: Content delivery network [<sup>:link:</sup>](https://cloud.google.com/cdn/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/cdn/docs/)
* **Cloud DNS**: Programmable DNS serving [<sup>:link:</sup>](https://cloud.google.com/dns/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/dns/docs/)
* **Cloud Load Balancing**: Multi-region load distribution/balancing [<sup>:link:</sup>](https://cloud.google.com/load-balancing/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/load-balancing/)
* **Cloud NAT**: Network address translation service [<sup>:page_facing_up:</sup>](https://cloud.google.com/nat/docs/overview/)
* **Cloud Router**: VPC/on-prem network route exchange (BGP) [<sup>:page_facing_up:</sup>](https://cloud.google.com/router/docs/)
* **Cloud VPN**: Virtual private network connection[<sup>:page_facing_up:</sup>](https://cloud.google.com/compute/docs/vpn/overview)
* **Network Service Tiers**: Price versus performance tiering [<sup>:link:</sup>](https://cloud.google.com/network-tiers/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/network-tiers/docs/)
* **Network Telemetry**: Network telemetry service [<sup>:link:</sup>](https://cloud.google.com/network-telemetry/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vpc/docs/using-flow-logs/)
* **Traffic Director**: Service mesh traffic management [<sup>:link:</sup>](https://cloud.google.com/traffic-director/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/traffic-director/docs/)
* **Anthos Service Mesh**: Service-aware network management [<sup>:link:</sup>](https://cloud.google.com/service-mesh/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/trace/docs/)
* **Virtual Private Cloud**: Software defined networking [<sup>:link:</sup>](https://cloud.google.com/vpc/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vpc/docs/)
* **Cloud Domains**: Register, transfer, manager domains [<sup>:link:</sup>](https://cloud.google.com/domains) [<sup>:page_facing_up:</sup>](https://cloud.google.com/domains/docs/)
* **VPC Service Controls**: Security perimeters for API-based services [<sup>:link:</sup>](https://cloud.google.com/vpc-service-controls/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vpc-service-controls/)
* **Network Intelligence Center**: Network monitoring and topology [<sup>:link:</sup>](https://cloud.google.com/network-intelligence-center/)
[<sup>:page_facing_up:</sup>](https://cloud.google.com/network-intelligence-center/docs/)
* **Service Directory**: Centrally publish/discover/connect services [<sup>:link:</sup>](https://cloud.google.com/service-directory)
[<sup>:page_facing_up:</sup>](https://cloud.google.com/service-directory/docs)
* **Private Service Connect**: Privately connect services across VPCs [<sup>:link:</sup>](https://cloud.google.com/service-directory)
[<sup>:page_facing_up:</sup>](https://cloud.google.com/vpc/docs/private-service-connect)
* **Network Connectivity Center**: Connect VPC & On-prem [<sup>:link:</sup>](https://cloud.google.com/network-connectivity-center)
[<sup>:page_facing_up:</sup>](https://cloud.google.com/network-connectivity/docs/network-connectivity-center)
* **Packet Mirroring**: Monitor/analyze instance traffic [<sup>:page_facing_up:</sup>](https://cloud.google.com/vpc/docs/packet-mirroring)
* **Cloud IDS**: Detects network based threats [<sup>:link:</sup>](https://cloud.google.com/intrusion-detection-system)
[<sup>:page_facing_up:</sup>](https://cloud.google.com/intrusion-detection-system/docs)
 

### Identity and Security
  
* **Access Transparency**: Audit cloud provider access [<sup>:link:</sup>](https://cloud.google.com/access-transparency/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/logging/docs/audit/access-transparency-overview/)
* **Assured Workloads**: Workload compliance controls [<sup>:link:</sup>](https://cloud.google.com/assured-workloads) [<sup>:page_facing_up:</sup>](https://cloud.google.com/assured-workloads/docs)
* **Binary Authorization**: Kubernetes deploy-time security [<sup>:link:</sup>](https://cloud.google.com/binary-authorization/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/binary-authorization/docs/)
* **Certificate Authority Service**: Managed private CAs [<sup>:link:</sup>](https://cloud.google.com/certificate-authority-service) [<sup>:page_facing_up:</sup>](https://cloud.google.com/certificate-authority-service/docs)
* **Cloud Asset Inventory**: All assets, one place [<sup>:link:</sup>](https://cloud.google.com/asset-inventory) [<sup>:page_facing_up:</sup>](https://cloud.google.com/asset-inventory/docs/overview)
* **Cloud Audit Logs**: Audit trails for Google Cloud [<sup>:link:</sup>](https://cloud.google.com/audit-logs/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/logging/docs/audit/)
* **Cloud Data Loss Prevention (DLP)**: Classify and redact sensitive data [<sup>:link:</sup>](https://cloud.google.com/dlp/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/dlp/docs/)
* **Cloud HSM**: Hardware security module service [<sup>:link:</sup>](https://cloud.google.com/hsm/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/kms/docs/hsm/)
* **Cloud External Key Manager (EKM)**: External keys you control [<sup>:link:</sup>](https://cloud.google.com/ekm/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/kms/docs/ekm/)
* **Cloud IAM**: Resource access control [<sup>:link:</sup>](https://cloud.google.com/iam/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/iam/docs/)
* **Cloud Identity**: Manage users, devices & apps [<sup>:link:</sup>](https://cloud.google.com/identity/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/identity/solutions/overview/)
* **Cloud Identity-Aware Proxy**: Identity-based app access [<sup>:link:</sup>](https://cloud.google.com/iap/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/iap/docs/)
* **Cloud Key Management Service**: Hosted key management service [<sup>:link:</sup>](https://cloud.google.com/kms/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/kms/docs/)
* **Resource Manager**: Cloud project metadata management [<sup>:link:</sup>](https://cloud.google.com/resource-manager/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/resource-manager/docs/)
* **Security Command Center**: Security management and data risk platform [<sup>:link:</sup>](https://cloud.google.com/security-command-center/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/security-command-center/docs/)
* **Web Security Scanner**: App engine security scanner [<sup>:link:</sup>](https://cloud.google.com/security-scanner/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/security-scanner/docs/)
* **Confidential Computing**: Encrypt data in-use [<sup>:link:</sup>](https://cloud.google.com/confidential-computing) [<sup>:page_facing_up:</sup>](https://cloud.google.com/confidential-computing/docs)
* **Access Context Manager**: End-user attribute-based access control [<sup>:link:</sup>](https://cloud.google.com/context-aware-access/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/iap/docs/cloud-iap-context-aware-access-howto/)
* **Event Threat Detection**: Scans for suspicious activity [<sup>:link:</sup>](https://cloud.google.com/event-threat-detection/) 
* **Managed Service for Microsoft Active Directory**: Managed Microsoft Active Directory  [<sup>:link:</sup>](https://cloud.google.com/managed-microsoft-ad/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/managed-microsoft-ad/docs/)
* **Secret Manager**: Store and manage secrets [<sup>:link:</sup>](https://cloud.google.com/secret-manager/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/secret-manager/docs/)
* **Security Key Enforcement**: Two-step key verification [<sup>:link:</sup>](https://cloud.google.com/security-key/)
* **Shielded VMs**: Hardened VMs [<sup>:link:</sup>](https://cloud.google.com/shielded-vm/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/security/shielded-cloud/shielded-vm/)
* **Titan Security Key**: Two-factor authentication (2FA) device [<sup>:link:</sup>](https://cloud.google.com/titan-security-key/)
* **VPC Service Controls**: VPC data constraints [<sup>:link:</sup>](https://cloud.google.com/vpc-service-controls/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/vpc-service-controls/docs/)
* **Chronicle**: Find threats from security telemetry  [<sup>:link:</sup>](https://chronicle.security/products/platform/) 
* **VirusTotal**: Research/hunt for malware  [<sup>:link:</sup>](https://chronicle.security/products/virustotal/) 
* **Risk Manager**: Evaluate organization’s security posture  [<sup>:link:</sup>](https://cloud.google.com/risk-manager/docs) 
* **reCAPTCHA Enterprise**: Protection against bot/spam/abuse [<sup>:link:</sup>](https://cloud.google.com/recaptcha-enterprise) [<sup>:page_facing_up:</sup>](https://cloud.google.com/recaptcha-enterprise/docs/)
* **BeyondCorp Enterprise**: Zero trust secure access [<sup>:link:</sup>](https://cloud.google.com/beyondcorp-enterprise) [<sup>:page_facing_up:</sup>](https://cloud.google.com/beyondcorp-enterprise/docs)
* **Access Context Manager**: Fine-grained, attribute based access-control [<sup>:page_facing_up:</sup>](https://cloud.google.com/access-context-manager/docs)
* **Web Security Scanner**: Identifies  web-app security vulnerabilities [<sup>:page_facing_up:</sup>](https://cloud.google.com/security-command-center/docs/concepts-web-security-scanner-overview)


### Operations & Monitoring
* **Cloud Debugger**: Live production debugging [<sup>:link:</sup>](https://cloud.google.com/debugger/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/debugger/docs/)
* **Error Reporting**: App error reporting [<sup>:link:</sup>](https://cloud.google.com/error-reporting/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/error-reporting/docs/)
* **Cloud Logging**: Centralized logging [<sup>:link:</sup>](https://cloud.google.com/logging/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/logging/docs/)
* **Cloud Monitoring**: Infrastructure and application monitoring [<sup>:link:</sup>](https://cloud.google.com/monitoring/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/monitoring/docs/)
* **Cloud Profiler**: CPU and heap profiling [<sup>:link:</sup>](https://cloud.google.com/profiler/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/profiler/docs/)
* **Cloud Trace**: App latency insights [<sup>:link:</sup>](https://cloud.google.com/trace/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/trace/docs/)  
 
 
### DevOps CI/CD

* **Cloud Build**: Continuous integration/delivery platform [<sup>:link:</sup>](https://cloud.google.com/cloud-build/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/cloud-build/docs/)
* **Cloud Deploy**: Deployment pipeline for GKE [<sup>:link:</sup>](https://cloud.google.com/deploy) [<sup>:page_facing_up:</sup>](https://cloud.google.com/deploy/docs/)
* **Artifact Registry**: Universal package manager [<sup>:link:</sup>](https://cloud.google.com/artifacts/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/artifacts/)
* **Cloud Source Repositories**: Hosted private git repos [<sup>:link:</sup>](https://cloud.google.com/source-repositories/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/source-repositories/docs/)
* **Container Registry**: Private container registry/storage [<sup>:link:</sup>](https://cloud.google.com/container-registry/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/container-registry/docs/)


### Application Integration
* **Eventarc**: Event-driven Cloud Run services [<sup>:link:</sup>](https://cloud.google.com/eventarc/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/eventarc/docs/)
* **Cloud Scheduler**: Managed cron job service [<sup>:link:</sup>](https://cloud.google.com/scheduler/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/scheduler/docs/)
* **Cloud Tasks**: Asynchronous task execution [<sup>:link:</sup>](https://cloud.google.com/tasks/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/tasks/docs/)
* **Workflows**: HTTP services orchestration [<sup>:link:</sup>](https://cloud.google.com/workflows/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/workflows/docs/)
* **Pub/Sub**: Global real-time messaging [<sup>:link:</sup>](https://cloud.google.com/pubsub/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/pubsub/docs/)


### API Platform and Ecosystems   
* **API Analytics**: API metrics [<sup>:link:</sup>](https://cloud.google.com/api-analytics/)
* **API Monetization**: Monetize APIs [<sup>:link:</sup>](https://cloud.google.com/api-monetization/)
* **Apigee API Platform**: Develop, secure, monitor APIs [<sup>:link:</sup>](https://cloud.google.com/apigee-api-management/)
* **API Gateway**: Fully managed API Gateway [<sup>:link:</sup>](https://cloud.google.com/api-gateway)
* **Apigee Hybrid**: Manage hybrid/multi-cloud API environments [<sup>:link:</sup>](https://cloud.google.com/apigee/api-management/hybrid/)[<sup>:page_facing_up:</sup>](https://docs.apigee.com/hybrid/beta2)
* **Apigee Sense**: API protection from attacks [<sup>:link:</sup>](https://cloud.google.com/apigee-sense/)
* **Cloud Endpoints**: Cloud API gateway [<sup>:link:</sup>](https://cloud.google.com/endpoints/)
* **Developer Portal**: API management portal [<sup>:link:</sup>](https://cloud.google.com/developer-portal/)
* **Marketplace**: Partner & open source marketplace [<sup>:link:</sup>](https://cloud.google.com/marketplace/)
* **AppSheet**: No-code App creation [<sup>:link:</sup>](https://www.appsheet.com/)

### Internet of Things (IoT) 
  
* **Cloud IoT Core**: Manage devices, ingest data [<sup>:link:</sup>](https://cloud.google.com/iot-core/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/iot-core/docs/)
  
### Gaming
* **Google Cloud Game Servers**: Orchestrate Agones clusters [<sup>:link:</sup>](https://cloud.google.com/game-servers)

### Healthcare
* **Cloud Healthcare API**: Healthcare system Google Cloud interoperability [<sup>:link:</sup>](https://cloud.google.com/healthcare-api/)
* **Apigee Healthcare APIx**: Healthcare system Google Cloud interoperability [<sup>:link:</sup>](https://cloud.google.com/solutions/apigee-health-apix)
* **Healthcare Natural Language AI**: Real-time insights from media-text [<sup>:link:</sup>](https://cloud.google.com/healthcare-api/docs/how-tos/nlp)
* *Cloud Life Sciences**: Manage, process, transform biomedical-data [<sup>:link:</sup>](https://cloud.google.com/life-sciences)[<sup>:page_facing_up:</sup>](https://cloud.google.com/life-sciences/docs)


### Retail
* **Vision Product Search**: Visual search for products [<sup>:page_facing_up:</sup>](https://cloud.google.com/vision/product-search/docs/)
* **Recommendations AI**: Create custom recommendations [<sup>:link:</sup>](https://cloud.google.com/recommendations/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/recommendations-ai/docs/)
* **Visual Inspection AI**: Train/deploy models to detect defects [<sup>:link:</sup>](https://cloud.google.com/solutions/visual-inspection-ai) 


 ### Management Tools
* **VM Manager**: Manage OS VM Fleets [<sup>:page_facing_up:</sup>](https://cloud.google.com/compute/docs/vm-manager)
* **Cloud APIs**: APIs for cloud services [<sup>:link:</sup>](https://cloud.google.com/apis/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/apis/docs/)
* **Cloud Billing API**: Programmatically manage Google Cloud billing [<sup>:page_facing_up:</sup>](https://cloud.google.com/billing/docs/)
* **Cloud Billing**: Billing and cost management tools [<sup>:link:</sup>](https://cloud.google.com/billing/docs/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/billing/docs/docs/)
* **Cloud Console**: Web-based management console [<sup>:link:</sup>](https://cloud.google.com/cloud-console/)
* **Cloud Deployment Manager**: Templated infrastructure deployment [<sup>:link:</sup>](https://cloud.google.com/deployment-manager/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/deployment-manager/docs/)
* **Cloud Mobile App**: iOS/Android Google Cloud manager app [<sup>:link:</sup>](https://cloud.google.com/console-app/)
* **Private Catalog**: Internal Solutions Catalog [<sup>:link:</sup>](https://cloud.google.com/private-catalog/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/private-catalog/docs/)
* **Carbon Footprint**: Report and reduce carbon emissions [<sup>:link:</sup>](https://cloud.google.com/carbon-footprint) [<sup>:page_facing_up:</sup>](https://cloud.google.com/carbon-footprint/docs)


### Developer Tools  
  
* **Cloud Code for IntelliJ**: IntelliJ Google Cloud tools [<sup>:link:</sup>](https://cloud.google.com/intellij/)
* **Cloud Code for VS Code**: VS Code Google Cloud tools [<sup>:link:</sup>](https://cloud.google.com/code/docs/vscode/)
* **Cloud Code**: Cloud native IDE extensions [<sup>:link:</sup>](https://cloud.google.com/code/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/code/docs/)
* **Cloud Tools for Eclipse**: Eclipse Google Cloud tools [<sup>:link:</sup>](https://cloud.google.com/eclipse/docs/)
* **Cloud Tools for Visual Studio**: Visual Studio Google Cloud tools [<sup>:link:</sup>](https://cloud.google.com/visual-studio/)
* **App Engine Plugins**: Gradle/Maven App Engine plugin [<sup>:link:</sup>](https://github.com/GoogleCloudPlatform/app-gradle-plugin)
* **Cloud SDK**: CLI for Google Cloud [<sup>:link:</sup>](https://cloud.google.com/sdk/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/sdk/docs/)
* **Cloud Shell**: Browser-based terminal/CLI [<sup>:link:</sup>](https://cloud.google.com/shell/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/shell/docs/)


### Migration to Google Cloud  
  
* **BigQuery Data Transfer Service**: Bulk import analytics data [<sup>:link:</sup>](https://cloud.google.com/bigquery/transfer/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/bigquery/transfer/docs/)
* **Cloud Data Transfer**: Data migration tools/CLI [<sup>:link:</sup>](https://cloud.google.com/products/data-transfer/)
* **Google Transfer Appliance**: Rentable data transport box [<sup>:link:</sup>](https://cloud.google.com/transfer-appliance/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/transfer-appliance/docs/)
* **Storage Transfer Service**: Online/on-premises data transfer [<sup>:page_facing_up:</sup>](https://cloud.google.com/storage-transfer-service/)
* **Migrate for Anthos and GKE**: Migrate VMs to GKE [<sup>:link:</sup>](https://cloud.google.com/migrate/anthos/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/migrate/anthos/docs/getting-started)
* **Migrate for Compute Engine**: Compute Engine migration tools [<sup>:link:</sup>](https://cloud.google.com/migrate/compute-engine/) [<sup>:page_facing_up:</sup>](https://cloud.google.com/velostrata/docs/)
* **Migrate from Amazon Redshift**: Migrate from Redshift to BigQuery [<sup>:link:</sup>](https://cloud.google.com/bigquery/docs/redshift-migration) 
* **Migrate from Teradata**: Migrate from Teradata to BigQuery [<sup>:link:</sup>](https://cloud.google.com/solutions/migration/td2bq/td-bq-migration-overview) 
* **Cloud Foundation Toolkit**: Infrastructure as Code templates [<sup>:link:</sup>](https://cloud.google.com/foundation-toolkit) 
* **KF**: Cloud Foundry to Kubernetes [<sup>:link:</sup>](https://cloud.google.com/migrate/kf/docs)

  
### Google Maps Platform  
  
* **Directions API**: Get directions between locations [<sup>:link:</sup>](https://developers.google.com/maps/documentation/directions/)
* **Distance Matrix API**: Multi-origin/destination travel times [<sup>:link:</sup>](https://developers.google.com/maps/documentation/distance-matrix/intro)
* **Geocoding API**: Convert address to/from coordinates [<sup>:link:</sup>](https://developers.google.com/maps/documentation/geocoding/)
* **Geolocation API**: Derive location without GPS [<sup>:link:</sup>](https://developers.google.com/maps/documentation/geolocation/)
* **Maps Embed API**: Display iframe embedded maps [<sup>:link:</sup>](https://developers.google.com/maps/documentation/embed/)
* **Maps JavaScript API**: Dynamic web maps [<sup>:link:</sup>](https://developers.google.com/maps/documentation/javascript/)
* **Maps SDK for Android**: Maps for Android apps [<sup>:link:</sup>](https://developers.google.com/maps/documentation/android-sdk/)
* **Maps SDK for iOS**: Maps for iOS apps [<sup>:link:</sup>](https://developers.google.com/maps/documentation/ios-sdk/)
* **Maps Static API**: Display static map images [<sup>:link:</sup>](https://developers.google.com/maps/documentation/maps-static/)
* **Maps SDK for Unity**: Unity SDK for games [<sup>:link:</sup>](https://cloud.google.com/maps-platform/gaming/)
* **Maps URLs**: URL scheme for maps [<sup>:link:</sup>](https://developers.google.com/maps/documentation/urls/)
* **Places API**: Rest-based Places features [<sup>:link:</sup>](https://developers.google.com/places/web-service/)
* **Places Library, Maps JS API**: Places features for web [<sup>:link:</sup>](https://developers.google.com/maps/documentation/javascript/places)
* **Places SDK for Android**: Places features for Android [<sup>:link:</sup>](https://developers.google.com/places/android-sdk/)
* **Places SDK for iOS**: Places feature for iOS [<sup>:link:</sup>](https://developers.google.com/places/ios-sdk/)
* **Roads API**: Convert coordinates to roads [<sup>:link:</sup>](https://developers.google.com/maps/documentation/roads/)
* **Street View Static API**: Static street view images [<sup>:link:</sup>](https://developers.google.com/maps/documentation/streetview/)
* **Street View Service**: Street view for JavaScript [<sup>:link:</sup>](https://developers.google.com/maps/documentation/javascript/streetview/)
* **Time Zone API**: Convert coordinates to timezone [<sup>:link:</sup>](https://developers.google.com/maps/documentation/timezone/)
  
### Workspace Platform  
  
* **Admin SDK**: Manage Google Workspace resources [<sup>:link:</sup>](https://developers.google.com/admin-sdk)
* **AMP for Email**: Dynamic interactive email [<sup>:link:</sup>](https://developers.google.com/gmail)
* **Apps Script**: Extend and automate everything [<sup>:link:</sup>](https://developers.google.com/apps-script/)
* **Calendar API**: Create and manage calendars [<sup>:link:</sup>](https://developers.google.com/calendar/)
* **Classroom API**: Provision and manage classrooms [<sup>:link:</sup>](https://developers.google.com/classroom)
* **Cloud Search**: Unified search for enterprise [<sup>:link:</sup>](https://developers.google.com/cloud-search/docs/guides/)
* **Docs API**: Create and edit documents [<sup>:link:</sup>](https://developers.google.com/docs/api/)
* **Drive Activity API**: Retrieve Google Drive activity [<sup>:link:</sup>](https://developers.google.com/drive/activity/)
* **Drive API**: Read and write files [<sup>:link:</sup>](https://developers.google.com/drive/)
* **Drive Picker**: Drive file selection widget [<sup>:link:</sup>](https://developers.google.com/picker/)
* **Email Markup**: Interactive email using schema.org [<sup>:link:</sup>](https://developers.google.com/gmail/markup/)
* **Google Workspace Add-ons**:  Extend Google Workspace apps [<sup>:link:</sup>](https://developers.google.com/gsuite/add-ons)
* **Google Workspace Marketplace**: Storefront for integrated applications [<sup>:link:</sup>](https://developers.google.com/gsuite/marketplace/)
* **Gmail API**: Enhance Gmail [<sup>:link:</sup>](https://developers.google.com/gmail/)
* **Google Chats API**: Conversational bots in chat [<sup>:link:</sup>](https://developers.google.com/chat)
* **People API**: Manage user's Contacts [<sup>:link:</sup>](https://developers.google.com/people/)
* **Sheets API**: Read and write spreadsheets [<sup>:link:</sup>](https://developers.google.com/sheets/api/)
* **Slides API**: Create and edit presentations [<sup>:link:</sup>](https://developers.google.com/slides/)
* **Task API**: Search, read & update Tasks [<sup>:link:</sup>](https://developers.google.com/tasks/)
* **Vault API**: Manage your organization's eDiscovery [<sup>:link:</sup>](https://developers.google.com/vault/)
  
### Mobile (Firebase)  
  
* **Cloud Firestore**: Document store and sync [<sup>:link:</sup>](https://firebase.google.com/products/firestore/)
* **Cloud Functions for Firebase**: Event-driven serverless applications [<sup>:link:</sup>](https://firebase.google.com/products/functions/)
* **Cloud Storage for Firebase**: Object storage and serving [<sup>:link:</sup>](https://firebase.google.com/products/storage/)
* **Crashlytics**: Crash reporting and analytics [<sup>:link:</sup>](https://fabric.io/kits/android/crashlytics/summary)
* **Firebase A/B Testing**: Create A/B test experiments [<sup>:link:</sup>](https://firebase.google.com/products/ab-testing/)
* **Firebase App Distribution**: Trusted tester early access [<sup>:link:</sup>](https://firebase.google.com/products/app-distribution/)
* **Firebase Authentication**: Drop-in authentication [<sup>:link:</sup>](https://firebase.google.com/products/auth/)
* **Firebase Cloud Messaging**: Send device notifications [<sup>:link:</sup>](https://firebase.google.com/products/cloud-messaging/)
* **Firebase Dynamic Links**: Link to app content [<sup>:link:</sup>](https://firebase.google.com/products/dynamic-links/)
* **Firebase Extensions**: Pre-packaged development solutions [<sup>:link:</sup>](https://firebase.google.com/products/extensions)
* **Firebase Hosting**: Web hosting with CDN/SSL [<sup>:link:</sup>](https://firebase.google.com/products/hosting/)
* **Firebase In-App Messaging**: Send in-app contextual messages [<sup>:link:</sup>](https://firebase.google.com/products/in-app-messaging/)
* **Firebase Performance Monitoring**: App/web performance monitoring [<sup>:link:</sup>](https://firebase.google.com/products/performance/)
* **Firebase Predictions**: Predict user targeting [<sup>:link:</sup>](https://firebase.google.com/products/predictions/)
* **Firebase Realtime Database**: Real-time data synchronization [<sup>:link:</sup>](https://firebase.google.com/products/realtime-database/)
* **Firebase Remote Config**: Remotely configure installed apps [<sup>:link:</sup>](https://firebase.google.com/docs/remote-config/)
* **Firebase Test Lab**: Mobile testing device farm [<sup>:link:</sup>](https://firebase.google.com/docs/test-lab/)
* **Google Analytics for Firebase**: Mobile app analytics [<sup>:link:</sup>](https://firebase.google.com/products/analytics/)
* **ML Kit for Firebase**: ML APIs for mobile [<sup>:link:</sup>](https://firebase.google.com/products/ml-kit/)
  
### Additional Resources

* **Google Cloud Home Page**: [<sup>:link:</sup>](https://cloud.google.com)
* **Google Cloud Blog**: [<sup>:link:</sup>](https://cloud.google.com/blog)
* **Google Cloud Platform Podcast**: [<sup>:link:</sup>](https://Google Cloudpodcast.com/)
* **Kubernetes Podcast from Google**: [<sup>:link:</sup>](https://kubernetespodcast.com/)
* **Google Cloud Reader**: [<sup>:link:</sup>](https://podcasts.google.com/feed/aHR0cHM6Ly9mZWVkcy50cmFuc2lzdG9yLmZtL2dvb2dsZS1jbG91ZC1yZWFkZXI=)
* **Google Cloud Open Source**: [<sup>:link:</sup>](https://opensource.google/projects/list/cloud)
* **Google Cloud Medium Publication**: [<sup>:link:</sup>](https://medium.com/google-cloud)
* **Apigee Blog**: [<sup>:link:</sup>](https://apigee.com/about/blog)
* **Firebase Blog**: [<sup>:link:</sup>](https://firebase.googleblog.com)
* **Google Workspace Developers Blog**: [<sup>:link:</sup>](https://gsuite-developers.googleblog.com)
* **Google Workspace GitHub**: [<sup>:link:</sup>](https://github.com/gsuitedevs)
* **Google Workspace Twitter**: [<sup>:link:</sup>](https://twitter.com/gsuitedevs)
* **Google Cloud Certifications**: [<sup>:link:</sup>](https://cloud.google.com/certification)
* **Google Cloud System Status**: [<sup>:link:</sup>](https://status.cloud.google.com)
* **Google Cloud Training**: [<sup>:link:</sup>](https://cloud.google.com/training)
* **Google Developers Blog**: [<sup>:link:</sup>](https://developers.googleblog.com) 
* **Google Maps Platform Blog**: [<sup>:link:</sup>](https://mapsplatform.googleblog.com)
* **Google Open Source Blog**: [<sup>:link:</sup>](https://opensource.googleblog.com)
* **Google Security Blog**: [<sup>:link:</sup>](https://security.googleblog.com)
* **Kaggle Home Page**: [<sup>:link:</sup>](https://www.kaggle.com) 
* **Kubernetes Blog**: [<sup>:link:</sup>](https://kubernetes.io/blog)
* **Regions and Network Map**: [<sup>:link:</sup>](https://cloud.google.com/about/locations)
* **DORA - Software & Delivery Research**: [<sup>:link:</sup>](https://cloud.google.com/devops)
* **Cloud Security Podcast**: [<sup>:link:</sup>](https://cloud.withgoogle.com/cloudsecurity/podcast/)
* **Google Cloud Sketchnote**: [<sup>:link:</sup>](https://goo.gle/Google Cloudsketchnote)



----------------------------
### Everything below is not included in the PDFs/PNGs due to space limitations

----------------------------

### Additional Resources

* **Source for this document**: [<sup>:link:</sup>](https://4words.dev)
* **Google Cloud Solutions Library**: [<sup>:link:</sup>](https://cloud.google.com/solutions/)
* **Google Workspace Solutions Gallery**: [<sup>:link:</sup>](https://developers.google.com/gsuite/solutions)
* **Google Cloud Support Hub**: [<sup>:link:</sup>](https://cloud.google.com/support-hub/)
* **Google Cloud Pricing**: [<sup>:link:</sup>](https://cloud.google.com/pricing/)
* **Google Cloud Pricing Calculator**: [<sup>:link:</sup>](https://cloud.google.com/products/calculator/)
* **Qwiklabs Home Page**: [<sup>:link:</sup>](https://www.qwiklabs.com/)
* **Codelabs Home Page**: [<sup>:link:</sup>](https://codelabs.developers.google.com/)
* **YouTube Channels**:
  * **Google Cloud**: [<sup>:link:</sup>](https://www.youtube.com/channel/UCTMRxtyHoE3LPcrl-kT4AQQ)
  * **Google Cloud Technical**: [<sup>:link:</sup>](https://www.youtube.com/user/googlecloudplatform)
  * **Google Workspace**: [<sup>:link:</sup>](https://www.youtube.com/user/GoogleApps)
  * **Google Developer's**: [<sup>:link:</sup>](https://www.youtube.com/user/GoogleDevelopers)
  * **Firebase**: [<sup>:link:</sup>](https://www.youtube.com/user/Firebase)
* **Reddit**:
  * **/r/googlecloud**: [<sup>:link:</sup>](https://www.reddit.com/r/googlecloud/)
  * **/r/AppEngine**: [<sup>:link:</sup>](https://www.reddit.com/r/AppEngine/)
  * **/r/bigquery**: [<sup>:link:</sup>](https://www.reddit.com/r/bigquery/)
  * **/r/dataflow**: [<sup>:link:</sup>](https://www.reddit.com/r/dataflow/)
  * **/r/firebase**: [<sup>:link:</sup>](https://www.reddit.com/r/firebase/)
  * **/r/GoogleAppsScript**: [<sup>:link:</sup>](https://www.reddit.com/r/GoogleAppsScript/)
* **Big Data / Data Analytics Product Comparisons**: [<sup>:link:</sup>](https://cloud.google.com/products/big-data)
* **Compute Product Comparisons**: [<sup>:link:</sup>](https://cloud.google.com/products/databases)
* **Database Product Comparisons**: [<sup>:link:</sup>](https://cloud.google.com/products/compute)
* **Networking Product Comparisons**: [<sup>:link:</sup>](https://cloud.google.com/products/networking)
* **Storage Product Comparisons**: [<sup>:link:</sup>](https://cloud.google.com/products/storage)

### Google Cloud Foundational Open Source Projects
  
* **Apache Beam**: Batch/streaming data processing [<sup>:link:</sup>](https://beam.apache.org/)
* **Go**: High Concurrency Programming Language [<sup>:link:</sup>](https://golang.org/)
* **gRPC**: RPC framework [<sup>:link:</sup>](https://grpc.io/)
* **gVisor**: Secure container runtime [<sup>:link:</sup>](https://github.com/google/gvisor)
* **Istio**: Connect and secure services [<sup>:link:</sup>](https://istio.io/)
* **Knative**: Serverless framework for Kubernetes [<sup>:link:</sup>](https://github.com/knative)
* **Kubeflow**: ML toolkit for Kubernetes [<sup>:link:</sup>](https://www.kubeflow.org/)
* **Kubernetes**: Management of containerized applications [<sup>:link:</sup>](https://kubernetes.io/)
* **OpenCensus**: Cloud native observability framework [<sup>:link:</sup>](https://opencensus.io/)
* **TensorFlow**: ML framework [<sup>:link:</sup>](https://www.tensorflow.org/)

### Platform Comparisons

* **Google Cloud Platform for AWS Professionals**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/docs/compare/aws/)
* **Google Cloud Platform for Azure Professionals**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/docs/compare/azure/)
* **Google Cloud Platform for Data Center Professionals**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/docs/compare/data-centers/)
* **Google Cloud Platform for OpenStack Users**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/docs/compare/openstack/)

### Language Specific Documentation

* **Apps Script**: [<sup>:page_facing_up:</sup>](https://developers.google.com/apps-script)
* **Java**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/java/docs/)
* **Node.js**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/nodejs/docs/)
* **Python**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/python/docs/)
* **Go**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/go/docs/)
* **Ruby**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/ruby/docs/)
* **PHP**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/php/docs/)
* **.NET/C#**: [<sup>:page_facing_up:</sup>](https://cloud.google.com/dotnet/docs/)







