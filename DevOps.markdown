# My DevOps Resources - James Lavin

(Extracted from My Tech Resources due to Github README.markdown length limit & truncation)

## DESCRIPTION

Links to DevOps resources I have found useful or think might be helpful to future me or developers like me.

## DEVOPS

* [Network Chuck](https://www.youtube.com/c/NetworkChuck)
* [Building Evolutionary Infrastructure - Kief Morris (GOTO 2019)](https://www.youtube.com/watch?v=1f_P8ZH5BC8)
* [Observability: Superpowers for Developers - Christine Yen (StrangeLoop 2019)](https://www.youtube.com/watch?v=1C5eErvSvR4)
* [BOSH](https://github.com/cloudfoundry/bosh)
* [Capistrano](https://github.com/capistrano/capistrano)
* [Heroku](http://www.heroku.com/) | [Tddium](https://devcenter.heroku.com/articles/tddium)
* [Puppet](http://puppetlabs.com/)
* [Ruby-Toolbox - Deployment Automation](https://www.ruby-toolbox.com/categories/deployment_automation)
* [Ruby-Toolbox - Systems Integration](https://www.ruby-toolbox.com/categories/systems_integration)
* [LinuxAcademy.com (mostly non-free but offers some free courses)](https://app.linuxacademy.com/search?cost=0)
* [Acquiring DevOps Skills - Pavel Suchman (DevCon TLV 2014)](http://confreaks.tv/videos/3293-devcontlvjan2014-acquiring-devops-skills)
* [Configuration Management ROI - Evgeny Zislis (DevCon TLV 2014)](http://confreaks.tv/videos/3294-devcontlvjan2014-configuration-management-roi)
* [Continuous Deployment - Matt White (MountainWest RubyConf 2012)](http://confreaks.tv/videos/967-mwrc2012-continuous-deployment)
* FutureStack conference videos: [14](https://www.youtube.com/playlist?list=PLmhYj7Jl81JGhEQnFGbWVLkGWEzFXzdzr) | [13](https://www.youtube.com/playlist?list=PLmhYj7Jl81JEMKm0LFHjn25GV6gUUU9IR)

### DEVOPS - ANSIBLE

* [Docs](https://docs.ansible.com/ansible/latest/index.html) | [User Guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)
* [Ansible - Your First Step Into Server Provisioning - Ben Turner (Ruby Australia 2014)](http://vimeo.com/90171333)
* [How to Create a File in Ansible - Aleksandar Kovačević](https://phoenixnap.com/kb/ansible-create-file)
* [Using variables](https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html)
* [Interactive input: vars_prompt](https://docs.ansible.com/ansible/latest/user_guide/playbooks_prompts.html)
* [ansible-vault](https://docs.ansible.com/ansible/latest/cli/ansible-vault.html) | [Encrypting content with Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html)
* [Templating (Jinja2)](https://docs.ansible.com/ansible/latest/user_guide/playbooks_templating.html)
* [Ansible 101 (15 episodes) - Jeff Geerling](https://www.youtube.com/playlist?list=PL2_OBreMn7FqZkvMYt6ATmgC0KAGGJNAN)
  * [Episode 1 - Introduction to Ansible - Jeff Geerling](https://www.youtube.com/watch?v=goclfp6a2IQ)
  * [Episode 2 - Ad-hoc tasks and inventory - Jeff Geerling](https://www.youtube.com/watch?v=7kVfqmGtDL8)
* [Avoiding Common Mistakes In Your Ansible Playbooks - Tadej Borovsak (AnsibleFest 2021)](https://www.youtube.com/watch?v=H3of3CVBHHU)
* [All Ansible Videos from TopTechSkills.com - Percy Grunwald](https://www.youtube.com/playlist?list=PLMyOob-UkeytIleCbMlFfCzaunOh27hm6)

#### DEVOPS - ANSIBLE - COLLECTIONS

* [Using Collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html)
* [Ansible Galaxy](https://galaxy.ansible.com/)
  * [Cassandra](https://github.com/ansible-collections/community.cassandra)
  * [Galaxy: Most downloaded](https://galaxy.ansible.com/search?deprecated=false&keywords=&order_by=-download_count&page=1)
    * [Azure](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&cloud_platforms=azure)
    * [Alpine](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&platforms=Alpine)
    * [Cloud](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=cloud)
    * [Database](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=database)
    * [Development](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=development)
    * [Docker](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=docker)
    * [MacOS](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&platforms=MacOSX)
    * [Monitoring](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=monitoring)
    * [Networking](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=networking)
    * [Security](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=security)
    * [System](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=system)
    * [Ubuntu](https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1&deprecated=false&tags=ubuntu)
    * [Web](https://galaxy.ansible.com/search?deprecated=false&tags=web&keywords=&order_by=-download_count&page=1)
  * [Galaxy: Community](https://galaxy.ansible.com/community)
    * [Cassandra](https://github.com/ansible-collections/community.cassandra)
* [Collection Index](https://docs.ansible.com/ansible/latest/collections/index.html) | [Github](https://github.com/ansible-collections)
  * [Builtin](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/index.html#plugins-in-ansible-builtin)
    * [apt](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/apt_module.html#ansible-collections-ansible-builtin-apt-module)
    * [apt_key](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/apt_key_module.html#ansible-collections-ansible-builtin-apt-key-module)
    * [copy](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/copy_module.html)
    * [debug](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/debug_module.html)
    * [gather_facts](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/gather_facts_module.html#ansible-collections-ansible-builtin-gather-facts-module)
    * [get_url](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/get_url_module.html#ansible-collections-ansible-builtin-get-url-module)
    * [set_fact](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/set_fact_module.html)
    * [setup](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/setup_module.html)
    * [shell](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/shell_module.html)
    * [template](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/template_module.html)
    * [uri](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/uri_module.html)
  * [AWS](https://docs.ansible.com/ansible/latest/collections/amazon/aws/index.html#plugins-in-amazon-aws)
  * [Azure](https://docs.ansible.com/ansible/latest/collections/community/azure/index.html#plugins-in-community-azure) & [AZCollection](https://docs.ansible.com/ansible/latest/collections/azure/azcollection/index.html#plugins-in-azure-azcollection)
  * [Digital Ocean](https://docs.ansible.com/ansible/latest/collections/community/digitalocean/index.html#plugins-in-community-digitalocean)
  * [Google Cloud](https://docs.ansible.com/ansible/latest/collections/google/cloud/index.html#plugins-in-google-cloud)
  * [Kubernetes.Core](https://docs.ansible.com/ansible/latest/collections/kubernetes/core/index.html#plugins-in-kubernetes-core)
  * [MongoDB](https://docs.ansible.com/ansible/latest/collections/community/mongodb/index.html#plugins-in-community-mongodb)
  * [Podman](https://docs.ansible.com/ansible/latest/collections/containers/podman/index.html#plugins-in-containers-podman)
  * [POSIX](https://docs.ansible.com/ansible/latest/collections/ansible/posix/index.html#plugins-in-ansible-posix)
  * [PostgreSQL](https://docs.ansible.com/ansible/latest/collections/community/postgresql/index.html#plugins-in-community-postgresql)
  * [RabbitMQ](https://docs.ansible.com/ansible/latest/collections/community/rabbitmq/index.html#plugins-in-community-rabbitmq)
  * [Vault](https://docs.ansible.com/ansible/latest/collections/community/hashi_vault/index.html#plugins-in-community-hashi-vault)

#### DEVOPS - ANSIBLE - MODULES

* [10 Ansible modules for Linux system automation -  Ricardo Gerardi](https://opensource.com/article/20/10/ansible-modules-linux)
* [10 best Ansible modules for infrastructure as code - John Capobianco](https://bluecatnetworks.com/blog/10-best-ansible-modules-for-infrastructure-as-code/)

#### DEVOPS - ANSIBLE - ROLES

[Ansible.JeffGeerling.com](https://ansible.jeffgeerling.com/)

### DEVOPS - API GATEWAYS

* [Communication Patterns API Gateway Event Driven Microservices - Chris Richardson](https://www.youtube.com/watch?v=g_jrDP-FXFo)
* [API Gateway to Service Mesh: Navigating a Changing Landscape - Zhamak Dehghani](https://www.youtube.com/watch?v=QYdOJ0QJptE)

#### DEVOPS - API GATEWAYS - KONG

* [API Gateway Pattern & Kong in a Microservices World - Marco Palladino, Mashape (MesosCon 2017)](https://www.youtube.com/watch?v=OUUiS28hZuw)

#### DEVOPS - API GATEWAYS - AMBASSADOR

* [Website](https://www.getambassador.io/) | [Blog](https://blog.getambassador.io/) | [Gitter](https://gitter.im/datawire/ambassador)
* [Building Ambassador, an Open Source API Gateway on Kubernetes and Envoy - Richard Li (Datawire)](https://blog.getambassador.io/building-ambassador-an-open-source-api-gateway-on-kubernetes-and-envoy-ed01ed520844)
* [Envoy as an API Gateway in Kubernetes - envoyproxy.io](https://www.envoyproxy.io/docs/envoy/latest/start/distro/ambassador)

### DEVOPS - AWS (AMAZON WEB SERVICES)

#### DEVOPS - AWS (AMAZON WEB SERVICES) - KUBERNETES / EKS

* [Getting Started with Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/getting-started.html)
* [Amazon EKS Workshop](https://eksworkshop.com/)
* eksctl - Official CLI for Amazon EKS: [eksctl.io](https://eksctl.io/) | [Github](https://github.com/weaveworks/eksctl)
* [aws-iam-authenticator: tool to use AWS IAM credentials to authenticate to a Kubernetes cluster](https://github.com/kubernetes-sigs/aws-iam-authenticator)
* [Specifying Sensitive Data - AWS](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/specifying-sensitive-data.html)
* [Deep Dive on Amazon EKS - Brandon Chavis & Eswar Bala (AWS re:Invent 2018)](https://www.youtube.com/watch?v=EDaGpxZ6Qi0)
* [Run Kubernetes with Amazon EKS - Bob Wise (AWS New York Summit 2018)](https://www.youtube.com/watch?v=mCVdcz01Z-g)
* [Introducing Amazon EKS - Brandon Chavis (AWS re:Invent 2017)](https://www.youtube.com/watch?v=WHTejF3W0s4)
* [Run Kubernetes with Amazon EKS - Bob Wise (AWS New York Summit 2018)](https://www.youtube.com/watch?v=mCVdcz01Z-g&t=2s)
* [Running a High-Performance Kubernetes Cluster with Amazon EKS - Nathan Peck & Yekesa Kosuru (AWS re:Invent 2018)](https://www.youtube.com/watch?v=YQWt6wdAZMU)
* [Amazon Elastic Container Service for Kubernetes - Christoph Kassen (DevDay 2018](https://www.youtube.com/watch?v=lef1qR7C_GE)
* [Running Kubernetes with Amazon EKS - AWS Online Tech Talks](https://www.youtube.com/watch?v=rV_NCvs9iGE)
* [Mastering Kubernetes on AWS - Yaniv Donenfeld & Karl D'Adamo (AWS re:Invent 2018)](https://www.youtube.com/watch?v=8OPkt93WyPA)
* [Deep Dive Into Amazon EKS - (AWS re:Invent 2017)](https://www.youtube.com/watch?v=vrYLrx-a_Wg)
* [AWS Workshop for Kubernetes - AWS](https://github.com/aws-samples/aws-workshop-for-kubernetes)
* [kubernetes-aws.io](https://github.com/kubernetes/community/blob/master/sig-aws/kubernetes-on-aws.md)

#### DEVOPS - AWS (AMAZON WEB SERVICES) - PODCASTS

* [AWS Podcast](https://aws.amazon.com/podcasts/aws-podcast/)
* [AWS re:Invent 2017](https://itunes.apple.com/us/podcast/aws-re-invent-2017/id1323851530?mt=2)
* [AWS TechChat](https://aws.amazon.com/podcasts/aws-techchat/)

#### DEVOPS - AWS (AMAZON WEB SERVICES) - RDS (RELATIONAL DATABASE SERVICE)

* [Getting Started with Managed Database Services on AWS - September 2016 Webinar Series](https://www.youtube.com/watch?v=nvh3XypRSq0)
* [Getting Started with Amazon Aurora (AWS re:Invent 2017)](https://www.youtube.com/watch?v=DAJhvRMniqo) | [Deep Dive on the Amazon Aurora MySQL-compatible Edition (AWS re:Invent 2017](https://www.youtube.com/watch?v=rPmKo2g9znA)
* [Deep Dive on Amazon Relational Database Service (RDS) - Brian Welcker (AWS re:Invent 2017)](https://www.youtube.com/watch?v=TJxC-B9Q9tQ)
* [Announcing Amazon Aurora with PostgreSQL Compatibility - January 2017 AWS Onlin](https://www.youtube.com/watch?v=4jslgOGsBb4)
* [Using Performance Insights to Analyze Performance of Amazon Aurora PostgreSQL](https://www.youtube.com/watch?v=4462hcfkApM)

#### DEVOPS - AWS (AMAZON WEB SERVICES) - REDSHIFT

* [Amazon Redshift Tutorial: AWS Tutorial for Beginners - Edureka](https://www.youtube.com/watch?v=fc5WPKnbam8)

### DEVOPS - AZURE (MICROSOFT)

* Azure: [Videos](https://azure.microsoft.com/en-us/resources/videos/index/?sort=newest)

#### DEVOPS - AZURE (MICROSOFT) - KUBERNETES (AKS)

* AKS (Azure Kubernetes Service): [Webpage](https://azure.microsoft.com/en-us/services/kubernetes-service/) | [Learning Path](https://azure.microsoft.com/mediahandler/files/resourcefiles/kubernetes-learning-path/Kubernetes%20Learning%20Path%20version%201.0.pdf) | [Documentation](https://docs.microsoft.com/en-us/azure/aks/) | [Downloadable PDF](https://docs.microsoft.com/en-us/azure/opbuildpdf/aks/TOC.pdf?branch=live) | [Videos](https://azure.microsoft.com/en-us/resources/videos/index/?services=kubernetes-service&sort=newest) | [CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
* [Application Gateway Ingress Controller - Azure](https://azure.github.io/application-gateway-kubernetes-ingress/)
* [AKS Engine: easiest way to provision a self-managed Kubernetes cluster on Azure](https://github.com/Azure/aks-engine) | [Docs](https://github.com/Azure/aks-engine/blob/master/docs/README.md) | [Tutorial](https://github.com/Azure/aks-engine/blob/master/docs/tutorials/README.md) | [FAQ](https://github.com/Azure/aks-engine/blob/master/docs/faq.md)

### DEVOPS - BACKUPS

#### DEVOPS - BACKUPS - RESTIC

* Restic: [Github.io](https://restic.github.io/) | [Documentation](https://restic.readthedocs.io/en/stable/) | [Github](https://github.com/restic/restic)
* [How to configure Backblaze B2 with Restic on Linux - Roderick (Backblaze)](https://help.backblaze.com/hc/en-us/articles/115002880514-How-to-configure-Backblaze-B2-with-Restic-on-Linux)
* [My backup software of choice: restic - Jan-Piet Mens](http://jpmens.net/2017/08/22/my-backup-software-of-choice-restic/)

### DEVOPS - BALLERINA

* [Ballerina.io: Cloud-native programming language](https://ballerina.io/) | [Github](https://github.com/ballerina-platform)
* [Ballerina Microservices Programming Language: Introducing the Latest Release and "Ballerina Central" - Tyler Jewell](https://www.infoq.com/articles/ballerina-microservices-language-part-1)

### DEVOPS - BLOGS & PODCASTS

* [The Cloudcast - Aaron Delp & Brian Gracely](http://www.thecloudcast.net/)
* [Cloud Native in 15 Minutes - Pivotal](https://podcasts.apple.com/us/podcast/cloud-native-in-15-minutes/id1469633294)
* [Cloudscape Podcast](https://blog.pythian.com/podcasts/)
* [Datanauts (data center infrastructure)](http://packetpushers.net/series/datanauts-podcast/)
* [DevOps and Docker Talk - Bret Fisher](https://www.bretfisher.com/podcast/)
* [Dockercast](https://itunes.apple.com/us/podcast/dockercast/id1141133179)
* [Full Stack Journey](http://packetpushers.net/series/full-stack-journey/)
* [JAX](https://jaxenter.com/tag/devops)
* [The New Stack](http://thenewstack.io/)
* [Weekly Show (Networking Technology)](http://packetpushers.net/series/weekly-show/)

### DEVOPS - CEPH

* [Ceph](https://docs.ceph.com/docs/master/)
* [Cephadm](https://docs.ceph.com/docs/master/cephadm/)
* [Deploying a new Ceph cluster](https://docs.ceph.com/docs/master/cephadm/install/)
* [Orchestrator API](https://docs.ceph.com/docs/master/mgr/orchestrator/)
* [How Ceph Stores Data - 45 Drives](https://www.youtube.com/watch?v=ExWYSNE37js)
* 45 Drives: [Ceph & Its Components](https://www.youtube.com/watch?v=kktsCNiMgVE) | [More Ceph videos](https://www.youtube.com/channel/UCV_OrwHDqXdz7JuxjROhetA/playlists)
* [Storage and Ceph: Bare metal and Kubernetes Cluster - Bruno Dzogovic](https://www.youtube.com/watch?v=l7IKwDlh6rc)

#### DEVOPS - CEPH - ROOK.IO

* Rook.io: Open-Source, Cloud-Native Storage for Kubernetes: [Rook.io](https://rook.io/) | [Docs](https://rook.github.io/docs/rook/master/) | [Github](https://github.com/rook/rook) | [Helm chart to install Rook](https://rook.github.io/docs/rook/master/helm-operator.html)
* Cassandra: [CRD](https://rook.github.io/docs/rook/master/cassandra-cluster-crd.html) | [Quickstart](https://rook.github.io/docs/rook/master/cassandra.html)
* Ceph storage: [CRDs](https://rook.github.io/docs/rook/master/ceph-storage.html) | [Quickstart](https://rook.github.io/docs/rook/master/ceph-quickstart.html) | [Ceph tools](https://rook.github.io/docs/rook/master/ceph-tools.html)
* CockroachDB: [CRD](https://rook.github.io/docs/rook/master/cockroachdb-cluster-crd.html) | [Quickstart](https://rook.github.io/docs/rook/master/cockroachdb.html)
* NFS share: [CRD](https://rook.github.io/docs/rook/master/nfs-crd.html) | [Quickstart](https://rook.github.io/docs/rook/master/nfs.html)
* YugabyteDB: [CRD](https://rook.github.io/docs/rook/master/yugabytedb-cluster-crd.html) | [Quickstart](https://rook.github.io/docs/rook/master/yugabytedb.html)

### DEVOPS - CHAOS MONKEY, ETC

* [Principles of Chaos](http://principlesofchaos.org/)
* [Awesome Chaos Engineering](https://github.com/dastergon/awesome-chaos-engineering)
* [Precision Chaos - Aaron Blohowiak (O'Reilly Velocity San Jose 2017)](https://www.youtube.com/watch?v=C11LNUEaHuo)
* [ChAP: Chaos Automation Platform - Netflix](https://medium.com/netflix-techblog/chap-chaos-automation-platform-53e6d528371f)
* [Chaos Engineering - Netflix](http://www.oreilly.com/webops-perf/free/chaos-engineering.csp)
* [Simian Army](https://github.com/Netflix/SimianArmy/wiki) & [Quick start guide](https://github.com/Netflix/SimianArmy/wiki/Quick-Start-Guide)
* [Chaos Monkey](https://github.com/Netflix/SimianArmy/wiki/Chaos-Monkey)
* [Chaos Community Google group](https://groups.google.com/forum/#!forum/chaos-community)
* [Conformity Monkey](https://github.com/Netflix/SimianArmy/wiki/Conformity-Home)
* [Janitor Monkey](https://github.com/Netflix/SimianArmy/wiki/Janitor-Home)
* [AWS outage: How Netflix weathered the storm by preparing for the worst - Nick Heath](http://www.techrepublic.com/article/aws-outage-how-netflix-weathered-the-storm-by-preparing-for-the-worst/)

### DEVOPS - CHEF

* [Chef](http://www.opscode.com/chef/)
* [Chef Community](http://community.opscode.com/)
* [Chef Docs](http://docs.opscode.com/) & [Chef docs organized differently](http://docs.opscode.com/chef/)
* [Chef - Cookbooks, Opscode](https://github.com/opscode-cookbooks)
* [Chef - Cookbooks, Community](http://community.opscode.com/cookbooks)
* [UsingChef.com - Weekly Newsletter](http://usingchef.com/)
* [Chef - Recipe DSL](http://docs.opscode.com/chef/dsl_recipe.html)
* [Chef - Resources and Providers Reference](http://docs.opscode.com/chef/resources.html)
* [Chef videos from Opscode](http://www.youtube.com/user/Opscode)
* [Learn Chef](http://learnchef.com/)
* [Using Ruby to Automate Your Life - Seth Vargo (Ruby Australia 2014)](http://vimeo.com/90182570)
* [Testing Your Automation: TTD for Chef Cookbooks - Nathen Harvey (BigRuby 2013)](http://confreaks.tv/videos/2309-bigruby2013-testing-your-automation-ttd-for-chef-cookbooks)
* [Five Things You Didn't Know About Chef](http://confreaks.tv/videos/2301-bigruby2013-5-things-you-didn-t-know-about-chef)

#### DEVOPS - CHEF - BERKSHELF

* [Berkshelf](http://berkshelf.com/)

#### DEVOPS - CHEF - CHEF-DK

* [Chef-dk (Chef Development Kit)](https://github.com/opscode/chef-dk)

#### DEVOPS - CHEF - CHEF_SOLO

* [The Eight-fingered Chef by Jason Garber - MadisonRuby 2013](https://www.youtube.com/watch?v=eaI3OrSFdlM)

#### DEVOPS - CHEF - COOKBOOKS

* [chef-jenkins](https://github.com/fnichol/chef-jenkins)
* [chef-rbenv](https://github.com/fnichol/chef-rbenv)
* [chef-rvm](https://github.com/fnichol/chef-rvm)
* [chef-user](https://github.com/fnichol/chef-user)

#### DEVOPS - CHEF - KNIFE

* [Knife docs](http://docs.opscode.com/chef/knife.html)
* [knife-server](https://github.com/fnichol/knife-server)

#### DEVOPS - CHEF - LIBRARIAN

* [librarian-chef](https://github.com/applicationsonline/librarian-chef)
* ["What do I do with my own cookbooks (when using Librarian)?"](https://github.com/applicationsonline/librarian/wiki/FAQ)

#### DEVOPS - CHEF - TEST-KITCHEN

* [test-kitchen](https://github.com/test-kitchen/test-kitchen)

### DEVOPS - CLOUD

* [Awesome Cloud Native - Jimmy Song](https://jimmysong.io/awesome-cloud-native/)
* [Cloud Native Interactive Landscape (CNCF)](https://landscape.cncf.io/)
* [CNCF Webinars](https://www.cncf.io/webinars/)

### DEVOPS - COLOCATION

* [Colocation Is Better Than Owning Your Own Data Center. Or Is It? - Packet Pushers](https://www.youtube.com/watch?v=eFYWAdi7yp8)
* [Colocation Datacenters Introduction - Eli the Computer Guy](https://www.youtube.com/watch?v=yM1Mk8aLOLk)
* [The different types of data centers: Colocation, Enterprise, & Carrier Hotel - HawkPodcast 23](https://www.youtube.com/watch?v=DFktLnNUAO0) (content starts 14 minutes in)

### DEVOPS - CONTINUOUS DEPLOYMENT

* [Continuous Deployment at Facebook Scale - Boris Grubic & Fangfei Zhou, Facebook (Systems @Scale 2019)](https://www.youtube.com/watch?v=UAlDS6iARI0)

### DEVOPS - COREOS (RED HAT)

* [CoreOS](https://coreos.com/)
* [Getting Started With With CoreOS](https://www.digitalocean.com/community/tutorial_series/getting-started-with-coreos-2)
* [CoreOS Fleet](https://coreos.com/using-coreos/clustering/)
* [CoreOS rkt](https://github.com/coreos/rkt)

### DEVOPS - DOCKER

* Docker docs:
    * [User Guide](https://docs.docker.com/engine/userguide/)
    * [Documentation & Installation](https://docs.docker.com)
    * [Docker Container Networks](https://docs.docker.com/engine/userguide/networking/)
    * [Docker Engine](https://docs.docker.com/engine/understanding-docker/)
    * [Docker Swarm](https://docs.docker.com/swarm/)
    * [Docker Compose](https://docs.docker.com/compose/overview/)
    * [Docker Hub](https://docs.docker.com/docker-hub/)
    * [Docker Machine](https://docs.docker.com/machine/)
    * [Docker Cloud](https://docs.docker.com/docker-cloud/)
* [Docker Self-Paced Training videos](https://training.docker.com/self-paced-training)
* [Docker tutorial videos - Scott Turnbull](https://www.youtube.com/playlist?list=PLLOtMDswK0Iu0m0wseAXTzavCWji7qso7)
* [KataCoda (interactive browser-based labs, courses, & playgrounds)](https://katacoda.com/learn)
* Docker Tutorials: [1: Installing Docker](https://www.youtube.com/watch?v=bV5vbNK3Uhw) | [2: Docker Run Basics](https://www.youtube.com/watch?v=uTe08FxoKrU) | [3: Fun With Volumes](https://www.youtube.com/watch?v=rlK1JYsM6Aw) | [4: More Run With Extra Goodies](https://www.youtube.com/watch?v=ZgjHM1XmAKI) | [5: Basic Networking](https://www.youtube.com/watch?v=3uvqEC8fWV0) | [6: Dockerfiles (Part 1)](https://www.youtube.com/watch?v=gG_x28rDxus) | [7: Dockerfiles (Part 2)](https://www.youtube.com/watch?v=L6bjTlVdc6U) | [8: Troubleshooting with Sysdig](https://www.youtube.com/watch?v=S-fYCOMnsbY) | [9: Docker Machine](https://www.youtube.com/watch?v=3zXe3uXQnSY) | [10: Docker Compose](https://www.youtube.com/watch?v=gtoT0By8yh4) | [11: Docker Swarm](ihttps://www.youtube.com/watch?v=zTKGfPfhg78) | [12: Kitematic](https://www.youtube.com/watch?v=50IZ-AHPKo0) | [13: Getting Started with experimental Docker Networking](https://www.youtube.com/watch?v=gZ6UKym9ZIs) | [Full List](https://www.youtube.com/playlist?list=PLkA60AVN3hh_6cAz8TUGtkYbJSL2bdZ4h)
* [Awesome Docker - curated resources](https://github.com/veggiemonk/awesome-docker)
* [Docker for Data Scientists - Michelangelo D'Agostino (Strata 2016)](https://www.youtube.com/watch?v=GOW6yQpxOIg)
* [DockerCon 2015](https://www.youtube.com/watch?v=DfHcN3ZvjjU&list=PLenh213llmcbpJ78mZdh5pnJ_feVT9bez)
* [Docker 101: Introduction to Docker - Andrew T. Baker (PyCon 2015)](https://www.youtube.com/watch?v=YiZkHUbE6N0) & [Demystifying Docker - Andrew T. Baker (PyCon 2015)](https://www.youtube.com/watch?v=GVVtR_hrdKI)
* [The Docker Book - James Turnbull](http://dockerbook.com/)
* [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet)
* [Docker Youtube channel](https://www.youtube.com/user/dockerrun)
* [Docs.Docker.com](https://docs.docker.com/)
* [Docker Tutorials - DarkZebra](https://www.youtube.com/playlist?list=PLfpPfDziPdMIbc7p-_siXYwqsRnd3jrLM)
* Docker Overview - Rimantas Mocevicius: [Part 1](https://deis.com/blog/2016/docker-overview-pt-1/) | [Part 2](https://deis.com/blog/2016/docker-overview-pt-2/)
* [Intro to Docker - Amjith Ramanujam (PyCon 2014)](https://www.youtube.com/watch?v=9bvdc55xYdo)
* [Docker and the Future of Modern Software - Solomon Hyke (FutureStack14)](http://blog.newrelic.com/2014/11/24/fs14-video-docker-modern-software/)
* [Container Hacks and Fun Images - Jess Frazelle (DockerConf 2015)](https://www.youtube.com/watch?v=1qlLUf7KtAw) | [Jess Frazelle's .dockerfunc](https://github.com/jfrazelle/dotfiles/blob/master/.dockerfunc)
* [Containerized Ruby Applications with Docker - Laura Frank (RubyConf 2014)](http://confreaks.tv/videos/4964-RubyConf2014-containerized-ruby-applications-with-docker)
* [Shipping Ruby Apps with Docker - Bryan Helmkamp (RedDot Ruby 2014](http://confreaks.tv/videos/3853-rdrc2014-shipping-ruby-apps-with-docker)
* [Build Your Own Shipyard - Andreas Tiefenthaler (Kod.io 2014)](http://confreaks.tv/videos/3252-kodio_2014-build-your-own-shipyard)
* [Dockerising a Rails App - Graeme Mathieson](http://woss.name/articles/dockerising-a-rails-app/)
* [Docker's Youtube channel](https://www.youtube.com/channel/UC76AVf2JkrwjxNKMuPpscHQ)
* [Developing Ruby Applications With Docker - Laura Frank (ArrrrCamp 2015)](https://www.youtube.com/watch?v=hiiPMgZbzcA)
* [Immutable Infrastructure with Docker and EC2 - Michael Bryzek (Gilt) (DockerCon 2014)](https://www.youtube.com/watch?v=GaHzdqFithc)
* [3 hours to Docker fundamentals: Jumpstart your Docker knowledge](https://www.youtube.com/watch?v=ddhU3NMrhX4)
* [Be a happier developer with Docker: Tricks of the trade - Nicola Paolucci](https://www.youtube.com/watch?v=XCVOxht34Hs)
* [Pachyderm.io (MapReduce without Hadoop using a git-like distributed file system and Dockerized MapReduce)](http://www.pachyderm.io/) & [Github](https://github.com/pachyderm/pfs)
* [Docker isn’t just for deployment - Ben Dixon (RailsConf 2015)](https://www.youtube.com/watch?v=NGcT0dGivoM)

#### DEVOPS - DOCKER - CONFIGURATION

* [The Challenges of Container Configuration - Gareth Rushgrove (Craft Conference 2016)](http://www.ustream.tv/recorded/86186490) & [slides](https://speakerdeck.com/garethr/the-challenges-of-container-configuration)

#### DEVOPS - DOCKER - DIVE

* [Dive: tool for exploring a docker image, layer contents, and discovering ways to shrink your Docker image size (Alex Goodman)](https://github.com/wagoodman/dive)

#### DEVOPS - DOCKER - MICROCONTAINERS

* Demystifying Containers - Sascha Grunert: [Part I: Kernel Space](https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504) | [Part II: Container Runtimes](https://medium.com/@saschagrunert) | [Part III: Container Images](https://medium.com/@saschagrunert/demystifying-containers-part-iii-container-images-244865de6fef)
* [Microcontainers – Tiny, Portable Docker Containers - Iron.io](http://www.iron.io/blog/2016/01/microcontainers-tiny-portable-containers.html)
* [How to Build Slim Docker Images Fast - Simon Hawe](https://towardsdatascience.com/how-to-build-slim-docker-images-fast-ecc246d7f4a7)
* [Uber tiny Docker images for all the things (Ruby, Elixir, Python, etc.) - Iron.io](https://github.com/iron-io/dockers)
* [LinuxKit: Toolkit for building secure, portable and lean operating systems for containers](https://github.com/linuxkit/linuxkit)

#### DEVOPS - DOCKER - MULTIHOST ORCHESTRATION

* [Compose](http://docs.docker.com/compose/)
* Sebastien Goasguen: [Intro to Docker Compose Tool for Multi-Container Applications](https://www.linux.com/learn/introduction-docker-compose-tool-multi-container-applications) | [Docker Volumes and Networks with Compose](https://www.linux.com/learn/docker-volumes-and-networks-compose) | [How to Use Docker Machine to Create a Swarm Cluster](https://www.linux.com/learn/how-use-docker-machine-create-swarm-cluster) | [Using Docker Swarm to Create an Overlay Network](https://www.linux.com/learn/using-docker-swarm-create-overlay-network)
* [Dacker Ruby gem](https://github.com/talkingquickly/dacker)
* [Tools Built on Top of The Docker API - Vassili Van Der Mersch](http://nordicapis.com/tools-built-on-top-of-the-docker-api/)

##### DEVOPS - DOCKER - MULTIHOST ORCHESTRATION - CENTURION

* [Centurion - NewRelic](https://github.com/newrelic/centurion)

##### DEVOPS - DOCKER - MULTIHOST ORCHESTRATION - COMPOSE & SWARM

* [Docker 1.12 Release Candidate 2](https://www.youtube.com/watch?v=F7hoq0KwHD4)
* [Introducing the Docker for AWS and Azure Beta - Michael Friis](https://blog.docker.com/2016/06/azure-aws-beta/)
* [Compose - Docker](http://docs.docker.com/compose/)
* Sebastien Goasguen: [Intro to Docker Compose Tool for Multi-Container Applications](https://www.linux.com/learn/introduction-docker-compose-tool-multi-container-applications) | [Docker Volumes and Networks with Compose](https://www.linux.com/learn/docker-volumes-and-networks-compose)
* [Webinar Recording: Docker Compose: Simplifying Container Automation - Shawn Powers & Nathan Bank](https://www.youtube.com/watch?v=11jfxkuI0l4)
* [How To Install Wordpress and PhpMyAdmin with Docker Compose on Ubuntu 14.04 - DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-and-phpmyadmin-with-docker-compose-on-ubuntu-14-04)
* [Use Docker Swarm with a data persistence layer - Jonas Rosland](https://blog.emccode.com/2015/11/03/use-docker-swarm-with-a-data-persistence-layer/)
* [How To Configure a Continuous Integration Testing Environment with Docker and Docker Compose on Ubuntu 14.04 - Pablo Chico de Guzmán](https://www.digitalocean.com/community/tutorials/how-to-configure-a-continuous-integration-testing-environment-with-docker-and-docker-compose-on-ubuntu-14-04)
* [Docker Compose & Networking - Mano Marks](https://www.youtube.com/watch?v=rFQqiuFIjms)
* [Docker Compose Files Version 2](https://www.youtube.com/watch?v=EReEOMS7gsk)
* [Docker Swarm Part 1: Overview](https://www.youtube.com/watch?v=sg9wNcdMhbU) | [Part 2: Discovery](https://www.youtube.com/watch?v=4t7nej89dk4) | [Part 3: Scheduling](https://www.youtube.com/watch?v=7B_bX3czq-Y) | [Part 4: High Availability](https://www.youtube.com/watch?v=YjlH8ypkXOM) | [Part 5: Networking](https://www.youtube.com/watch?v=XemATdk8mY4) | [Part 6: Volumes](https://www.youtube.com/watch?v=Zxe0WAzPcjY)
* Docker Swarm: [Create and Join Node](https://www.youtube.com/watch?v=x843GyFRIIY) | [Setting up HA](https://www.youtube.com/watch?v=rCWki35Qk2M) | [Set up TLS](https://www.youtube.com/watch?v=PFw1GTx1XOQ) | [Container Rescheduling](https://www.youtube.com/watch?v=Bf7N6won3Eg)
* [Docker swarm cluster in AWS - Rafael Benevides](https://www.youtube.com/watch?v=JgUyI-MIKZ0)
* [From Local Docker Development to Production Deployments - Jérôme Petazzoni (AWS re:Invent 2015)](https://www.youtube.com/watch?v=7CZFpHUPqXw)

##### DEVOPS - DOCKER - MULTIHOST ORCHESTRATION - MESOS

* [Mesos - Apache](http://mesos.apache.org/)

##### DEVOPS - DOCKER - NETWORKING

* Networking for Docker Containers (a Primer) - Fernando Sanchez: [Part I](https://mesosphere.com/blog/2017/03/23/networking-docker-containers/) | [Part 2](https://mesosphere.com/blog/2017/04/25/networking-docker-containers-part-ii-service-discovery-traditional-apps-microservices/?utm_source=mesosphere&utm_medium=blog&utm_content=part1)

#### DEVOPS - DOCKER - OSX

* [Installation](https://docs.docker.com/engine/installation/mac/)
* [Docker Machine](https://docs.docker.com/machine/)

#### DEVOPS - DOCKER - POSTGRESQL

* [Official Postgres Docker repo](https://hub.docker.com/_/postgres/)

#### DEVOPS - DOCKER - REMOTE API

* [Docker Remote API](https://docs.docker.com/reference/api/docker_remote_api/)
* [Docker-api Ruby gem](https://github.com/swipely/docker-api)

#### DEVOPS - DOCKER - VIDEOS

* DockerCon: [2017](https://www.youtube.com/playlist?list=PLkA60AVN3hh_nihZ1mh6cO3n-uMdF7UlV) | [2016](https://www.youtube.com/playlist?list=PLkA60AVN3hh9gnrYwNO6zTb9U3i1Y9FMY) | [2015](https://www.youtube.com/playlist?list=PLkA60AVN3hh94tm0_6_rGxamkuHOLr30l)
* ContainerSummit.io: [2016 New York](http://containersummit.io/events/nyc-2016/videos) | [San Francisco 2015](http://containersummit.io/events/sf-2015/videos)
* [Youtube](https://www.youtube.com/user/dockerrun)
* [Confreaks](http://confreaks.tv/search?utf8=%E2%9C%93&query=Docker&commit=go)
* [DockerCon Online Meetup 2015](http://confreaks.tv/events/dockeronlinemeetup2015)
* [DockerCon EU 2015](https://www.youtube.com/playlist?list=PLLt1Xd0I4hRB5hWCjEQhZw2pwY8GTCyDA)
* [DockerCon & Co](http://confreaks.tv/events/docker&co2015)

### DEVOPS - DOCKER - VOLUMES

* [Understanding Volumes in Docker - Adrian Mouat](http://container-solutions.com/understanding-volumes-docker/)
* [Manage Data in Containers](https://docs.docker.com/engine/userguide/dockervolumes/)

### DEVOPS - DOKKU

* Dokku: [Github](https://github.com/dokku/dokku) | [website](http://dokku.viewdocs.io/dokku/) | [documentation](http://dokku.viewdocs.io/dokku/installation/)
* [One-click install-and-deploy Dokku on DigitalOcean](https://www.digitalocean.com/features/one-click-apps/dokku/)
* [Make Your Own Heroku with Dokku and DigitalOcean - Roger Stringer](http://rogerstringer.com/2015/05/13/make-your-own-heroku/)
* [Create Your Own Heroku Using Dokku-alt on DigitalOcean - Samudra Harapan Bekti](http://bekti.io/create-your-own-heroku-using-dokku-alt-on-digitalocean/)
* [Deploying Dokku to DigitalOcean for excellent deploying goodness - Pam Selle](http://thewebivore.com/tutorial-deploying-dokku-to-digitalocean-for-excellent-deploying-goodness/)
* [Running Dokku on Digital Ocean - Henrik Nyh](https://gist.github.com/henrik/26bb73091712aa42abf2)

### DEVOPS - DRONE.IO

* [Drone.io](https://drone.io/) | [Try It](http://try.drone.io/) | [Docs](https://docs.drone.io/)

### DEVOPS - DUCKTAPE

* [Ducktape: Distributed System Integration & Performance Testing Library - Confluent](https://github.com/confluentinc/ducktape)

### DEVOPS - FLUXCD

* [Flux at GitOps Con, KubeCon CloudNativeCon EU 2022](https://www.youtube.com/playlist?list=PLwjBY07V76p53FP85y03psCnb95u095Do)
* [GitOps Days 2022 presentations](https://www.youtube.com/playlist?list=PL9lTuCFNLaD0NVkR17tno4X6BkxsbZZfr)
* [FluxCD, ArgoCD or Jenkins X: Which Is the Right GitOps Tool for You? - Rafael Portela et al.](https://blog.container-solutions.com/fluxcd-argocd-or-jenkins-x-which-is-the-right-gitops-tool-for-you)
* [CI/CD Tooling, Which is best for you? - Mobilise](https://www.mobilise.cloud/ci-cd-tooling-which-is-best-for-you/)

### DEVOPS - GITLAB

* [Gitlab.com](://about.gitlab.com/)

### DEVOPS - GOCD

* GoCD - Continuous Delivery server: [GoCD.org](https://www.gocd.org/) | [Github](https://github.com/gocd/gocd)

### DEVOPS - GOOGLE CLOUD

* Gcloud: [Overview](https://cloud.google.com/sdk/gcloud/) | [Solutions](https://cloud.google.com/solutions/) | [Compute Concepts](https://cloud.google.com/compute/docs/concepts) | [SDK Concepts](https://cloud.google.com/sdk/docs/concepts) | [Reference](https://cloud.google.com/sdk/gcloud/reference/) | [Compute How-Tos](https://cloud.google.com/compute/docs/how-to) | [SDK How-Tos](https://cloud.google.com/sdk/docs/how-to)
* [Google Cloud Codelabs](https://codelabs.developers.google.com/cloud/)
* [Take5](https://www.youtube.com/playlist?list=PLIivdWyY5sqJ6sDqMDjAdB-IYZYM5UI_6) | [Platform Essentials](https://www.youtube.com/playlist?list=PLIivdWyY5sqKh1gDR0WpP9iIOY00IE0xL)
* [Coursera - Google Cloud](https://www.coursera.org/googlecloud)
* Getting Started With GCloud SDK: Joaquin Menchaca [Part 1](https://medium.com/@Joachim8675309/getting-started-with-gcloud-sdk-part-1-114924737) & [Part 2](https://medium.com/@Joachim8675309/getting-started-with-gcloud-sdk-part-2-4d049a656f1a)
* [gcp gcloud cheat sheet - Victor Yang](https://gist.github.com/pydevops/cffbd3c694d599c6ca18342d3625af97)
* [QwikLabs.com: We give you temporary credentials to Google Cloud Platform and Amazon Web Services, so you can learn the cloud using the real thing](https://www.qwiklabs.com/) | [Google.qwiklabs.com](https://google.qwiklabs.com)
* [Training - Google Cloud](https://teachercenter.withgoogle.com/gcp/training)
* [Hipster Shop: Cloud-Native Microservices Demo Application - Google Cloud](https://github.com/GoogleCloudPlatform/microservices-demo)
* [Developing Applications with Google Cloud Platform Specialization - Coursera](https://www.coursera.org/specializations/developing-apps-gcp)
* [Secrets Management - Google Cloud](https://cloud.google.com/solutions/secrets-management/)
* Janakiram MSV: [Configuring Kubernetes Cluster Federation to Create a Global Deployment](https://thenewstack.io/configuring-kubernetes-cluster-federation-to-create-a-global-deployment/) | [Deploy a Multicluster Ingress on Google Kubernetes Engine](https://thenewstack.io/deploy-a-multicluster-ingress-on-google-kubernetes-engine/)
* [Creating and Starting a VM Instance](https://cloud.google.com/compute/docs/instances/create-start-instance)
* [Setting up Jenkins on Kubernetes Engine](https://cloud.google.com/solutions/jenkins-on-kubernetes-engine-tutorial)

#### DEVOPS - GOOGLE CLOUD - FILESTORE

* [Cloud Filestore: Managed file storage for apps requiring filesystem interface and shared filesystem for data](https://cloud.google.com/filestore/)

#### DEVOPS - GOOGLE CLOUD - HEALTHCARE

* [Healthcare & Life Sciences Solutions](https://cloud.google.com/solutions/healthcare-life-sciences/)
* [Healthcare API](https://cloud.google.com/healthcare/)

#### DEVOPS - GOOGLE CLOUD - KUBERNETES (GKE)

* [Kubernetes Engine](https://cloud.google.com/kubernetes-engine/) | [Docs](https://cloud.google.com/kubernetes-engine/docs/)
* [Starting with Kubernetes Engine: Developer-friendly Deployment Strategies (Cloud Next '18)](https://www.youtube.com/watch?v=2ZP4M6UdH8s)
* [Cloud Next '18 videos](https://www.youtube.com/results?search_query=kubernetes+cloudnext+2018)
* [Using Google-managed SSL certificates](https://cloud.google.com/kubernetes-engine/docs/how-to/managed-certs)
* [Continuous Delivery Pipelines with Spinnaker and Google Kubernetes Engine](https://cloud.google.com/solutions/continuous-delivery-spinnaker-kubernetes-engin://cloud.google.com/solutions/continuous-delivery-spinnaker-kubernetes-engine)
* [Continuous Deployment to Kubernetes Engine using Jenkins](https://cloud.google.com/solutions/continuous-delivery-jenkins-kubernetes-engine)
* [Jenkins on Kubernetes Engine](https://cloud.google.com/solutions/jenkins-on-kubernetes-engine)
* [Setting up Jenkins on Kubernetes Engine](https://cloud.google.com/solutions/jenkins-on-kubernetes-engine-tutorial)
* [Configuring Jenkins for Kubernetes Engine](https://cloud.google.com/solutions/configuring-jenkins-kubernetes-engine)
* [Getting Started With Google Kubernetes Engine - Google Cloud (Coursera)](https://www.coursera.org/learn/google-kubernetes-engine)
* [Container management and deployment: from development to production - Kelsey Hightower (Google Cloud Next '17)](https://www.youtube.com/watch?v=XL9CQobFB8I)
* [Kelsey Hightower's Best Live Demo Yet - Kelsey Hightower (Cloud Next '18)](https://www.youtube.com/watch?v=U6SfRPwTKqo)
* [Google Container Engine - The easiest way to use containers in production - Robert Bailey and Chen Goldberg (Google Cloud Next '17)](https://www.youtube.com/watch?v=_yk1tTHYBvg)
* [Kubernetes 101 Workshop: Deploying a Simple Web App onto Kubernetes - Sarah Zelechoski](https://www.youtube.com/watch?v=H-FKBoWTVws)
* [Kubernetes tutorial for beginners - Basit Mustafa](https://www.youtube.com/watch?v=gpmerrSpbHg)
* [Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down - Carson Anderson](https://www.youtube.com/watch?v=90kZRyPcRZw) | [Unabridged version: Kubernetes for the basic user](https://vimeo.com/245778144/4d1d597c5e)
* [Kubernetes and Google Container Engine - Aparna Sinha and Kelsey Hightower (Google Cloud Next '17)](https://www.youtube.com/watch?v=Csf-gxjo4hc)
* [Local Persistent Volumes for Kubernetes Goes Beta](https://kubernetes.io/blog/2018/04/13/local-persistent-volumes-beta/)

##### DEVOPS - GOOGLE CLOUD - KUBERNETES (GKE) - SECURITY

* [Exploring container security: Use your own keys to protect your data on GKE](https://cloud.google.com/blog/products/containers-kubernetes/exploring-container-security-use-your-own-keys-to-protect-your-data-on-gke)

#### DEVOPS - GOOGLE CLOUD - PODCASTS

* [Google Cloud Platform Podcast](https://www.gcppodcast.com/)

#### DEVOPS - GOOGLE CLOUD - SECURITY

* [Stay in control of your security with new product enhancements in Google Cloud - Google](https://cloud.google.com/blog/products/identity-security/stay-in-control-of-your-security-with-new-product-enhancements-in-google-cloud)
* [Best practices for Identity and Access Management on Compute Engine - Eric Bahna (Google Cloud Next '17)](https://www.youtube.com/watch?v=qf_D92_yqbQ)

#### DEVOPS - GOOGLE CLOUD - SERVICES

* [All Products](https://cloud.google.com/products/)
* [CDN (Content Delivery Network)](https://cloud.google.com/cdn/)
* [Cloud SDK](https://cloud.google.com/sdk/)
* [Container Builder](https://cloud.google.com/container-builder/)
* [Container Registry](https://cloud.google.com/container-registry/)
* [DNS](https://cloud.google.com/dns/)
* [Kubernetes](https://cloud.google.com/kubernetes-engine/) | [Pricing](https://cloud.google.com/kubernetes-engine/pricing) | [Quickstart](https://cloud.google.com/kubernetes-engine/docs/quickstart) | [Tutorials](https://kubernetes.io/docs/tutorials/kubernetes-basics/) | [Deploying a containerized web application](https://cloud.google.com/kubernetes-engine/docs/tutorials/hello-app)
* [Load Balancing](https://cloud.google.com/load-balancing/)
* [PostgreSQL](https://cloud.google.com/sql/docs/postgres/) | [Concepts](https://cloud.google.com/sql/docs/postgres/concepts) | [How-Tos](https://cloud.google.com/sql/docs/postgres/how-to) | [APIs](https://cloud.google.com/sql/docs/postgres/apis) | [Resources](https://cloud.google.com/sql/docs/postgres/resources) | [Pricing](https://cloud.google.com/sql/pricing#pg-pricing)
* [Security Scanner](https://cloud.google.com/security-scanner/)
* [Source Code Repository](https://cloud.google.com/source-repositories/)
* [Stackdriver (Monitoring, Logging, Diagnostics)](https://cloud.google.com/stackdriver/)
* [VPC (Virtual Private Cloud)](https://cloud.google.com/vpc/)

### DEVOPS - GVISOR

* [gVisor: sandboxed container runtime compatible with Docker & Kubernetes - Google](https://cloudplatform.googleblog.com/2018/05/Open-sourcing-gVisor-a-sandboxed-container-runtime.html)

### DEVOPS - ISTIO

* [Istio: Open Platform to Connect, Manage, and Secure Microservices](https://istio.io/) | [Docs](https://istio.io/docs/) | [Blog](https://istio.io/blog/) | [News](https://istio.io/news/) | [Github](https://github.com/istio/istio) | [Twitter](https://twitter.com/IstioMesh)
* [IstioCon 2021 Workshop: Using Istio - Lee Calcote & Abishek Kumar](https://www.youtube.com/watch?v=T1Kwh3SRAXQ)
* [Practical Istio - (DockerCon 19)](https://www.youtube.com/watch?v=uRXzRfthYeU)
* [Bookinfo (Istio Demo) Application](https://istio.io/docs/examples/bookinfo/)
* [Exploring Istio by Example - Matthew Casperson](https://octopus.com/blog/istio/the-sample-application)
* [istio-operator](https://github.com/banzaicloud/istio-operator)
* [The Future is Istio - Jason Smith (GOTO 2018)]https://www.youtube.com/watch?v=sTqISgCgd9M()
* [Tutorial: Using Istio - Lee Calcote & Girish Ranganathan (KubeCon + CloudNativeCon 2018)](https://www.youtube.com/watch?v=jlHLZqS7Vek)
* [Distributed Microservices Metrics and Tracing with Istio and OpenCensus – Sandeep Dinesh (GDG DevFest Ukraine 2018)](https://www.youtube.com/watch?v=1wWfVqYb-5Y)
* Ray Tsang: [Reducing Microservices Architecture Complexity with Istio & Kubernetes (SpringOne Platform 2018)](https://www.youtube.com/watch?v=k42jqkjtYKY) & [Making Microservices Micro With Istio & Kubernetes](https://www.youtube.com/watch?v=4x79RfMaOyo)
* [Istio - The Packet's-Eye View - Matt Turner (KubeCon + CloudNativeCon 2018)](https://www.youtube.com/watch?v=zJnYuFsLHfY) & [Life of a Packet Through Istio - Matt Turner (Devoxx Belgium 2018)](https://www.youtube.com/watch?v=cB611FtjHcQ)
* [Kubernetes and Istio Service Mesh Demo Show - Jimmy Song](https://www.youtube.com/watch?v=26kbaZxcB4A) & [kubernetes-vagrant-centos-cluster (Github)](https://github.com/rootsongjc/kubernetes-vagrant-centos-cluster)
* [Service Mesh in Practice - Kasun Indrasiri & David Munro (BallerinaCon 2018)](https://www.youtube.com/watch?v=IpgMucMhm0g)
* [How to Gain Insights from Istio by Leveraging Tools Like Prometheus, Jaeger, and Cortex - Neeraj Poddar](https://www.youtube.com/watch?v=mOPMSdAQ0t8)
* [Introduction to Service Management with Istio Service Mesh - David Munro (Cloud Next '18)](https://www.youtube.com/watch?v=wCJrdKdD6UM)
* [The next evolution of microservices patterns with Istio Mesh - Christian Posta (JBCNConf 2018)](https://www.youtube.com/watch?v=rleCT47cqfY)
* [Istio: Defense in Depth for Modern Production Environments - Samrat Ray & Tao Li (Cloud Next 2018)](https://www.youtube.com/watch?v=eOI2aM9P7-c)
* [Istio 1.0.x Workshop - RedHat OpenShift](https://learn.openshift.com/servicemesh)
* [Istio on Kubernetes: Enter the Service Mesh - Burr Sutter](https://docs.google.com/presentation/d/1AF0ZrzkesxRpgZciZeTq9O-YHuO85R1NxsFofak-je4/edit#slide=id.g432884ce64_3_59) & [Istio Tutorial - Redhat](https://github.com/redhat-developer-demos/istio-tutorial)
* [Istio - Weaving the Service Mesh - Louis Ryan (QCon San Francisco 2017)](https://www.youtube.com/watch?v=bPEgHNZxlJw)
* [Better Canary Deploys with Kubernetes and Istio - Jason Yee (Devoxx Belgium 2018)](https://www.youtube.com/watch?v=R7gUDY_-cFo)
* [Making Microservices Micro with Istio Service Mesh - Ray Tsang (Devox Belgium 2017)](https://www.youtube.com/watch?v=AGztKw580yQ)
* [Microservices in the Cloud with Kubernetes and Istio - Sandeep Dinesh (Google I/O '18)](https://www.youtube.com/watch?v=gauOI0O9fRM)
* [Istio 101: Open Source Service Mesh for Microservices! - Sandeep Dinesh (2017)](https://www.youtube.com/watch?v=8OjOGJKM98o)
* [Getting Started with Istio on Amazon EKS - Arun Gupta](https://aws.amazon.com/blogs/opensource/getting-started-istio-eks/)
* Stop reinventing the wheel with Istio - Mete Atamel: [Devoxx UK 2018](https://www.youtube.com/watch?v=pGKwluckJ-A) & [NDC { Oslo } 2018](https://www.youtube.com/watch?v=1_7e4AyiYd8)
* [Service Mesh: What, Why, And How? - Flynn (DevOpsDays Boston 2017)](https://www.youtube.com/watch?v=B0vi6ZqqmMw)
* [Making Microservices Micro with Istio Service Mesh - Ray Tsang (Devox Belgium 2017)](https://www.youtube.com/watch?v=AGztKw580yQ)
* [Istio: Canaries and Kubernetes, Microservices and Service Mesh - Burr Sutter (DevNation Live)](https://www.youtube.com/watch?v=YQLOcjvbo9s) | [Slides](https://docs.google.com/presentation/d/1fcaJSXBUb_dORaxaGPuS8S0wh0Jg_q5Hx7snx2tBa2E/edit#slide=id.g25f5e76d7d_1_0)

#### DEVOPS - ISTIO - AWS

* [Getting Started with Istio on Amazon EKS - Arun Gupta](https://aws.amazon.com/blogs/opensource/getting-started-istio-eks/)

#### DEVOPS - ISTIO - DATADOG

* [Datadog Istio integration](https://docs.datadoghq.com/integrations/istio/) | [Monitor your Istio service mesh with Datadog - David Lentz](https://www.datadoghq.com/blog/monitor-istio-with-datadog/)

#### DEVOPS - ISTIO - ENVOY

* [Lyft's Envoy: Embracing a Service Mesh - Matt Klein (QCon NY 2018)](https://www.youtube.com/watch?v=55yi4MMVBi4)
* [Envoy Internals Deep Dive (Advanced Skill Level) - Matt Klein (KubeCon Europe 2018)](https://www.youtube.com/watch?v=gQF23Vw0keg)

#### DEVOPS - ISTIO - FLAGGER

* Flagger: Istio and App Mesh progressive delivery Kubernetes operator - Weaveworks: [Docs](https://docs.flagger.app/) | [Github](https://github.com/weaveworks/flagger) | [Flagger.app](https://flagger.app/)
* [Automated canary deployments with Flagger and Istio - Stefan Prodan](https://medium.com/google-cloud/automated-canary-deployments-with-flagger-and-istio-ac747827f9d1)

#### DEVOPS - ISTIO - GKE

* [Istio - Google Cloud](https://cloud.google.com/istio/)
* [Traffic Director & Envoy-Based L7 ILB for Production-Grade Service Mesh & Istio - Mike Columbus & Prajakta Joshi (Cloud Next '19)](https://www.youtube.com/watch?v=FUITCYMCEhU)
* The Service Mesh Era: [Istio blog post series](https://cloud.google.com/blog/products/networking/welcome-to-the-service-mesh-era-introducing-a-new-istio-blog-post-series) | [Advanced application deployments and traffic management with Istio on GKE](https://cloud.google.com/blog/products/networking/advanced-application-deployments-and-traffic-management-with-istio-on-gke) | [Securing your environment with Istio](https://cloud.google.com/blog/products/networking/the-service-mesh-era-securing-your-environment-with-istio) | [Demo: Intro to Istio Security](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/security-intro)
* [Hello Istio Codelab (With Google Kubernetes) - Google](https://codelabs.developers.google.com/codelabs/cloud-hello-istio/#0)
* [Mistake that cost thousands (Kubernetes, GKE) - Gajus Kuizinas](https://medium.com/@gajus/mistake-that-cost-thousands-kubernetes-gke-2212ea663e1f)
* [Istio 101 (1.0) on GKE](https://meteatamel.wordpress.com/2018/08/06/istio-101-1-0-on-gke/) | [Istio 101 (0.8.0) on GKE - Mete Atamel (Google)](https://meteatamel.wordpress.com/2018/06/07/istio-101-0-8-0-on-gke/)
* [ProductCatalog Canary Deployment (GKE / Istio)](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/istio-canary-gke)

#### DEVOPS - ISTIO - KIALI

* Kiali: Service Mesh Observability: [Kiali.io](https://www.kiali.io/) | [Getting started](https://www.kiali.io/gettingstarted/) | [Docs](https://www.kiali.io/documentation/) | [API](https://www.kiali.io/api/)
* [kiali-operator](https://operatorhub.io/operator/kiali-operator)

#### DEVOPS - ISTIO - MULTICLUSTER

* [Multicluster](https://istio.io/docs/setup/kubernetes/multicluster-install/)
* [To Multicluster, or Not to Multicluster: Inter-Cluster Communication Using a Service Mesh - Andrew Jenkins](https://www.infoq.com/articles/kubernetes-multicluster-comms)

#### DEVOPS - ISTIO - ROUTING

* [Incremental Istio Part 1, Traffic Management - Sandeep Parikh](https://istio.io/blog/2018/incremental-traffic-management/)

### DEVOPS - KUBERNETES

* Kubernetes: [Docs](https://kubernetes.io/) | [Kubernetes API](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.19/) | [Blog](https://kubernetes.io/blog/) | [Github](https://github.com/kubernetes/kubernetes)
  * [Concepts](https://kubernetes.io/docs/concepts/)
    * [Overview](https://kubernetes.io/docs/concepts/overview/)
    * [Cluster Architecture](https://kubernetes.io/docs/concepts/architecture/)
      * [Nodes](https://kubernetes.io/docs/concepts/architecture/nodes/)
      * [Control Plane-Node Communication](https://kubernetes.io/docs/concepts/architecture/control-plane-node-communication/)
      * [Controllers](https://kubernetes.io/docs/concepts/architecture/controller/)
      * [Cloud Controller Manager](https://kubernetes.io/docs/concepts/architecture/cloud-controller/)
    * [Containers](https://kubernetes.io/docs/concepts/containers/)
      * [Images](https://kubernetes.io/docs/concepts/containers/images/)
      * [Container Environment](https://kubernetes.io/docs/concepts/containers/container-environment/)
      * [Runtime Class](https://kubernetes.io/docs/concepts/containers/runtime-class/)
      * [Container Lifecycle Hooks](https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/)
    * [Workloads](https://kubernetes.io/docs/concepts/workloads/)
      * [Pods](https://kubernetes.io/docs/concepts/workloads/pods/)
      * [Controllers](https://kubernetes.io/docs/concepts/workloads/controllers/)
    * [Services, Load Balancing, and Networking](https://kubernetes.io/docs/concepts/services-networking/)
      * [Service](https://kubernetes.io/docs/concepts/services-networking/service/)
      * [Service Topology](https://kubernetes.io/docs/concepts/services-networking/service-topology/)
      * [DNS for Services and Pods](https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/)
      * [Connecting Applications with Services](https://kubernetes.io/docs/concepts/services-networking/connect-applications-service/)
      * [Endpoint Slices](https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/)
      * [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)
      * [Ingress Controllers](https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/)
      * [Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
      * [Adding Entries to Pod /etc/hosts with HostAliases](https://kubernetes.io/docs/concepts/services-networking/add-entries-to-pod-etc-hosts-with-host-aliases/)
      * [IPv4/IPv6 Dual Stack](https://kubernetes.io/docs/concepts/services-networking/dual-stack/)
    * [Storage](https://kubernetes.io/docs/concepts/storage/)
      * [Volumes](https://kubernetes.io/docs/concepts/storage/volumes/)
      * [Persistent Volumes](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)
      * [Volume Snapshots](https://kubernetes.io/docs/concepts/storage/volume-snapshots/)
      * [CSI Volume Cloning](https://kubernetes.io/docs/concepts/storage/volume-pvc-datasource/)
      * [Storage Classes](https://kubernetes.io/docs/concepts/storage/storage-classes/)
      * [Volume Snapshot Classes](https://kubernetes.io/docs/concepts/storage/volume-snapshot-classes/)
      * [Dynamic Volume Provisioning](https://kubernetes.io/docs/concepts/storage/dynamic-provisioning/)
      * [Storage Capacity](https://kubernetes.io/docs/concepts/storage/storage-capacity/)
      * [Ephemeral Volumes](https://kubernetes.io/docs/concepts/storage/ephemeral-volumes/)
      * [Node-Specific Volume Limits](https://kubernetes.io/docs/concepts/storage/storage-limits/)
    * [Configuration](https://kubernetes.io/docs/concepts/configuration/)
      * [Config Best Practices](https://kubernetes.io/docs/concepts/configuration/overview/)
      * [ConfigMaps](https://kubernetes.io/docs/concepts/configuration/configmap/)
      * [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)
      * [Managing Resources for Containers](https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/)
      * [Pod Overhead](https://kubernetes.io/docs/concepts/configuration/pod-overhead/)
      * [Organizing Cluster Access Using kubeconfig Files](https://kubernetes.io/docs/concepts/configuration/organize-cluster-access-kubeconfig/)
      * [Pod Priority and Preemption](https://kubernetes.io/docs/concepts/configuration/pod-priority-preemption/)
    * [Security](https://kubernetes.io/docs/concepts/security/)
      * [Overview of Cloud Native Security](https://kubernetes.io/docs/concepts/security/overview/)
      * [Pod Security Standards](https://kubernetes.io/docs/concepts/security/pod-security-standards/)
    * [Policies](https://kubernetes.io/docs/concepts/policy/)
      * [Limit Ranges](https://kubernetes.io/docs/concepts/policy/limit-range/)
      * [Resource Quotas](https://kubernetes.io/docs/concepts/policy/resource-quotas/)
      * [Pod Security Policies](https://kubernetes.io/docs/concepts/policy/pod-security-policy/)
    * [Scheduling and Eviction](https://kubernetes.io/docs/concepts/scheduling-eviction/)
      * [Kubernetes Scheduler](https://kubernetes.io/docs/concepts/scheduling-eviction/kube-scheduler/)
      * [Taints and Tolerations](https://kubernetes.io/docs/concepts/scheduling-eviction/taint-and-toleration/)
      * [Assigning Pods to Nodes](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/)
      * [Resource Bin Packing for Extended Resources](https://kubernetes.io/docs/concepts/scheduling-eviction/resource-bin-packing/)
      * [Eviction Policy](https://kubernetes.io/docs/concepts/scheduling-eviction/eviction-policy/)
      * [Scheduling Framework](https://kubernetes.io/docs/concepts/scheduling-eviction/scheduling-framework/)
      * [Scheduler Performance Tuning](https://kubernetes.io/docs/concepts/scheduling-eviction/scheduler-perf-tuning/)
    * [Cluster Administration](https://kubernetes.io/docs/concepts/cluster-administration/)
      * [Certificates](https://kubernetes.io/docs/concepts/cluster-administration/certificates/)
      * [Managing Resources](https://kubernetes.io/docs/concepts/cluster-administration/manage-deployment/)
      * [Cluster Networking](https://kubernetes.io/docs/concepts/cluster-administration/networking/)
      * [Logging Architecture](https://kubernetes.io/docs/concepts/cluster-administration/logging/)
      * [Metrics for Kubernetes System Components](https://kubernetes.io/docs/concepts/cluster-administration/system-metrics/)
      * [Certificates](https://kubernetes.io/docs/concepts/cluster-administration/certificates/)
      * [System Logs](https://kubernetes.io/docs/concepts/cluster-administration/system-logs/)
      * [Configuring Kubelet Garbage Collection](https://kubernetes.io/docs/concepts/cluster-administration/kubelet-garbage-collection/)
      * [Proxies](https://kubernetes.io/docs/concepts/cluster-administration/proxies/)
      * [API Priority and Fairness](https://kubernetes.io/docs/concepts/cluster-administration/flow-control/)
      * [Installing Add-ons](https://kubernetes.io/docs/concepts/cluster-administration/addons/)
    * [Extending Kubernetes](https://kubernetes.io/docs/concepts/extend-kubernetes/)
      * [Extending Your Kubernetes Cluster](https://kubernetes.io/docs/concepts/extend-kubernetes/extend-cluster/)
      * [Extending the Kubernetes API](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/)
      * [Compute, Storage, and Networking Extensions](https://kubernetes.io/docs/concepts/extend-kubernetes/compute-storage-net/)
      * [Operator Pattern](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
      * [Service Catalog](https://kubernetes.io/docs/concepts/extend-kubernetes/service-catalog/)
    * [Tasks](https://kubernetes.io/docs/tasks/)
      * [Install Tools](https://kubernetes.io/docs/tasks/tools/)
      * [Administer a Cluster](https://kubernetes.io/docs/tasks/administer-cluster/)
        * [Administration With Kubeadm](https://kubernetes.io/docs/tasks/administer-cluster/kubeadm/)
        * [Manage Memory, CPU, and API Resources](https://kubernetes.io/docs/tasks/administer-cluster/manage-resources/)
        * [Install a Network Policy Provider](https://kubernetes.io/docs/tasks/administer-cluster/network-policy-provider/)
        * [Access Clusters Using the Kubernetes API](https://kubernetes.io/docs/tasks/administer-cluster/access-cluster-api/)
        * [Access Services Running on Clusters](https://kubernetes.io/docs/tasks/administer-cluster/access-cluster-services/)
        * [Advertise Extended Resources for a Node](https://kubernetes.io/docs/tasks/administer-cluster/extended-resource-node/)
        * [Autoscale the DNS Service in a Cluster](https://kubernetes.io/docs/tasks/administer-cluster/dns-horizontal-autoscaling/)
        * [Change the default StorageClass](https://kubernetes.io/docs/tasks/administer-cluster/change-default-storage-class/)
        * [Change the Reclaim Policy of a PersistentVolume](https://kubernetes.io/docs/tasks/administer-cluster/change-pv-reclaim-policy/)
        * [Cloud Controller Manager Administration](https://kubernetes.io/docs/tasks/administer-cluster/running-cloud-controller/)
        * [Cluster Management](https://kubernetes.io/docs/tasks/administer-cluster/cluster-management/)
        * [Configure Out of Resource Handling](https://kubernetes.io/docs/tasks/administer-cluster/out-of-resource/)
        * [Configure Quotas for API Objects](https://kubernetes.io/docs/tasks/administer-cluster/quota-api-object/)
        * [Control CPU Management Policies on the Node](https://kubernetes.io/docs/tasks/administer-cluster/cpu-management-policies/)
        * [Control Topology Management Policies on a node](https://kubernetes.io/docs/tasks/administer-cluster/topology-manager/)
        * [Customizing DNS Service](https://kubernetes.io/docs/tasks/administer-cluster/dns-custom-nameservers/)
        * [Debugging DNS Resolution](https://kubernetes.io/docs/tasks/administer-cluster/dns-debugging-resolution/)
        * [Declare Network Policy](https://kubernetes.io/docs/tasks/administer-cluster/declare-network-policy/)
        * [Developing Cloud Controller Manager](https://kubernetes.io/docs/tasks/administer-cluster/developing-cloud-controller-manager/)
        * [Enabling EndpointSlices](https://kubernetes.io/docs/tasks/administer-cluster/enabling-endpointslices/)
        * [Enabling Service Topology](https://kubernetes.io/docs/tasks/administer-cluster/enabling-service-topology/)
        * [Encrypting Secret Data at Rest](https://kubernetes.io/docs/tasks/administer-cluster/encrypt-data/)
        * [Guaranteed Scheduling For Critical Add-On Pods](https://kubernetes.io/docs/tasks/administer-cluster/guaranteed-scheduling-critical-addon-pods/)
        * [IP Masquerade Agent User Guide](https://kubernetes.io/docs/tasks/administer-cluster/ip-masq-agent/)
        * [Limit Storage Consumption](https://kubernetes.io/docs/tasks/administer-cluster/limit-storage-consumption/)
        * [Namespaces Walkthrough](https://kubernetes.io/docs/tasks/administer-cluster/namespaces-walkthrough/)
        * [Operating etcd clusters for Kubernetes](https://kubernetes.io/docs/tasks/administer-cluster/configure-upgrade-etcd/)
        * [Reconfigure a Node's Kubelet in a Live Cluster](https://kubernetes.io/docs/tasks/administer-cluster/reconfigure-kubelet/)
        * [Reserve Compute Resources for System Daemons](https://kubernetes.io/docs/tasks/administer-cluster/reserve-compute-resources/)
        * [Safely Drain a Node while Respecting the PodDisruptionBudget](https://kubernetes.io/docs/tasks/administer-cluster/safely-drain-node/)
        * [Securing a Cluster](https://kubernetes.io/docs/tasks/administer-cluster/securing-a-cluster/)
        * [Set Kubelet parameters via a config file](https://kubernetes.io/docs/tasks/administer-cluster/kubelet-config-file/)
        * [Set up High-Availability Kubernetes Masters](https://kubernetes.io/docs/tasks/administer-cluster/highly-available-master/)
        * [Share a Cluster with Namespaces](https://kubernetes.io/docs/tasks/administer-cluster/namespaces/)
        * [Using a KMS provider for data encryption](https://kubernetes.io/docs/tasks/administer-cluster/kms-provider/)
        * [Using CoreDNS for Service Discovery](https://kubernetes.io/docs/tasks/administer-cluster/coredns/)
        * [Using NodeLocal DNSCache in Kubernetes clusters](https://kubernetes.io/docs/tasks/administer-cluster/nodelocaldns/)
        * [Using sysctls in a Kubernetes Cluster](https://kubernetes.io/docs/tasks/administer-cluster/sysctl-cluster/)
      * [Configure Pods and Containers](https://kubernetes.io/docs/tasks/configure-pod-container/)
        * [Assign Memory Resources to Containers and Pods](https://kubernetes.io/docs/tasks/configure-pod-container/assign-memory-resource/)
        * [Assign CPU Resources to Containers and Pods](https://kubernetes.io/docs/tasks/configure-pod-container/assign-cpu-resource/)
        * [Configure GMSA for Windows Pods and Containers](https://kubernetes.io/docs/tasks/configure-pod-container/configure-gmsa/)
        * [Configure RunAsUserName for Windows Pods and Containers](https://kubernetes.io/docs/tasks/configure-pod-container/configure-runasusername/)
        * [Configure Quality of Service for Pods](https://kubernetes.io/docs/tasks/configure-pod-container/quality-service-pod/)
        * [Assign Extended Resources to a Container](https://kubernetes.io/docs/tasks/configure-pod-container/extended-resource/)
        * [Configure a Pod to Use a Volume for Storage](https://kubernetes.io/docs/tasks/configure-pod-container/configure-volume-storage/)
        * [Configure a Pod to Use a PersistentVolume for Storage](https://kubernetes.io/docs/tasks/configure-pod-container/configure-persistent-volume-storage/)
        * [Configure a Pod to Use a Projected Volume for Storage](https://kubernetes.io/docs/tasks/configure-pod-container/configure-projected-volume-storage/)
        * [Configure a Security Context for a Pod or Container](https://kubernetes.io/docs/tasks/configure-pod-container/security-context/)
        * [Configure Service Accounts for Pods](https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/)
        * [Pull an Image from a Private Registry](https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/)
        * [Configure Liveness, Readiness and Startup Probes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/)
        * [Assign Pods to Nodes](https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes/)
        * [Assign Pods to Nodes using Node Affinity](https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes-using-node-affinity/)
        * [Configure Pod Initialization](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-initialization/)
        * [Attach Handlers to Container Lifecycle Events](https://kubernetes.io/docs/tasks/configure-pod-container/attach-handler-lifecycle-event/)
        * [Configure a Pod to Use a ConfigMap](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/)
        * [Share Process Namespace between Containers in a Pod](https://kubernetes.io/docs/tasks/configure-pod-container/share-process-namespace/)
        * [Create static Pods](https://kubernetes.io/docs/tasks/configure-pod-container/static-pod/)
        * [Translate a Docker Compose File to Kubernetes Resources](https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/)
      * [Manage Kubernetes Objects](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/)
        * [Declarative Management of Kubernetes Objects Using Configuration Files](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/declarative-config/)
        * [Declarative Management of Kubernetes Objects Using Kustomize](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/)
        * [Managing Kubernetes Objects Using Imperative Commands](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/imperative-command/)
        * [Imperative Management of Kubernetes Objects Using Configuration Files](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/imperative-config/)
        * [Update API Objects in Place Using kubectl patch](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/update-api-object-kubectl-patch/)
      * [Manage Secrets](https://kubernetes.io/docs/tasks/configmap-secret/)
        * [Managing Secrets using kubectl](https://kubernetes.io/docs/tasks/configmap-secret/managing-secret-using-kubectl/)
        * [Managing Secrets using Configuration File](https://kubernetes.io/docs/tasks/configmap-secret/managing-secret-using-config-file/)
        * [Managing Secrets using Kustomize](https://kubernetes.io/docs/tasks/configmap-secret/managing-secret-using-kustomize/)
      * [Inject Data Into Applications](https://kubernetes.io/docs/tasks/inject-data-application/)
        * [Define a Command and Arguments for a Container](https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/)
        * [Define Dependent Environment Variables](https://kubernetes.io/docs/tasks/inject-data-application/define-interdependent-environment-variables/)
        * [Define Environment Variables for a Container](https://kubernetes.io/docs/tasks/inject-data-application/define-environment-variable-container/)
        * [Expose Pod Information to Containers Through Environment Variables](https://kubernetes.io/docs/tasks/inject-data-application/environment-variable-expose-pod-information/)
        * [Expose Pod Information to Containers Through Files](https://kubernetes.io/docs/tasks/inject-data-application/downward-api-volume-expose-pod-information/)
        * [Distribute Credentials Securely Using Secrets](https://kubernetes.io/docs/tasks/inject-data-application/distribute-credentials-secure/)
        * [Inject Information into Pods Using a PodPreset](https://kubernetes.io/docs/tasks/inject-data-application/podpreset/)
      * [Run Applications](https://kubernetes.io/docs/tasks/run-application/)
        * [Run a Stateless Application Using a Deployment](https://kubernetes.io/docs/tasks/run-application/run-stateless-application-deployment/)
        * [Run a Single-Instance Stateful Application](https://kubernetes.io/docs/tasks/run-application/run-single-instance-stateful-application/)
        * [Run a Replicated Stateful Application](https://kubernetes.io/docs/tasks/run-application/run-replicated-stateful-application/)
        * [Scale a StatefulSet](https://kubernetes.io/docs/tasks/run-application/scale-stateful-set/)
        * [Delete a StatefulSet](https://kubernetes.io/docs/tasks/run-application/delete-stateful-set/)
        * [Force Delete StatefulSet Pods](https://kubernetes.io/docs/tasks/run-application/force-delete-stateful-set-pod/)
        * [Horizontal Pod Autoscaler](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)
        * [Horizontal Pod Autoscaler Walkthrough](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale-walkthrough/)
        * [Specifying a Disruption Budget for your Application](https://kubernetes.io/docs/tasks/run-application/configure-pdb/)
      * [Run Jobs](https://kubernetes.io/docs/tasks/job/)
        * [Running Automated Tasks with a CronJob](https://kubernetes.io/docs/tasks/job/automated-tasks-with-cron-jobs/)
        * [Parallel Processing using Expansions](https://kubernetes.io/docs/tasks/job/parallel-processing-expansion/)
        * [Coarse Parallel Processing Using a Work Queue](https://kubernetes.io/docs/tasks/job/coarse-parallel-processing-work-queue/)
        * [Fine Parallel Processing Using a Work Queue](https://kubernetes.io/docs/tasks/job/fine-parallel-processing-work-queue/)
      * [Access Applications in a Cluster](https://kubernetes.io/docs/tasks/access-application-cluster/)
        * [Web UI (Dashboard)](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)
        * [Accessing Clusters](https://kubernetes.io/docs/tasks/access-application-cluster/access-cluster/)
        * [Configure Access to Multiple Clusters](https://kubernetes.io/docs/tasks/access-application-cluster/configure-access-multiple-clusters/)
        * [Use Port Forwarding to Access Applications in a Cluster](https://kubernetes.io/docs/tasks/access-application-cluster/port-forward-access-application-cluster/)
        * [Use a Service to Access an Application in a Cluster](https://kubernetes.io/docs/tasks/access-application-cluster/service-access-application-cluster/)
        * [Connect a Front End to a Back End Using a Service](https://kubernetes.io/docs/tasks/access-application-cluster/connecting-frontend-backend/)
        * [Create an External Load Balancer](https://kubernetes.io/docs/tasks/access-application-cluster/create-external-load-balancer/)
        * [List All Container Images Running in a Cluster](https://kubernetes.io/docs/tasks/access-application-cluster/list-all-running-container-images/)
        * [Set up Ingress on Minikube with the NGINX Ingress Controller](https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/)
        * [Communicate Between Containers in the Same Pod Using a Shared Volume](https://kubernetes.io/docs/tasks/access-application-cluster/communicate-containers-same-pod-shared-volume/)
        * [Configure DNS for a Cluster](https://kubernetes.io/docs/tasks/access-application-cluster/configure-dns-cluster/)
      * [Monitoring, Logging, and Debugging](https://kubernetes.io/docs/tasks/debug-application-cluster/)
        * [Application Introspection and Debugging](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-application-introspection/)
        * [Auditing](https://kubernetes.io/docs/tasks/debug-application-cluster/audit/)
        * [Debug a StatefulSet](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-stateful-set/)
        * [Debug Init Containers](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-init-containers/)
        * [Debug Pods and ReplicationControllers](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-pod-replication-controller/)
        * [Debug Running Pods](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-running-pod/)
        * [Debug Services](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-service/)
        * [Debugging Kubernetes nodes with crictl](https://kubernetes.io/docs/tasks/debug-application-cluster/crictl/)
        * [Determine the Reason for Pod Failure](https://kubernetes.io/docs/tasks/debug-application-cluster/determine-reason-pod-failure/)
        * [Developing and debugging services locally](https://kubernetes.io/docs/tasks/debug-application-cluster/local-debugging/)
        * [Events in Stackdriver](https://kubernetes.io/docs/tasks/debug-application-cluster/events-stackdriver/)
        * [Get a Shell to a Running Container](https://kubernetes.io/docs/tasks/debug-application-cluster/get-shell-running-container/)
        * [Logging Using Elasticsearch and Kibana](https://kubernetes.io/docs/tasks/debug-application-cluster/logging-elasticsearch-kibana/)
        * [Logging Using Stackdriver](https://kubernetes.io/docs/tasks/debug-application-cluster/logging-stackdriver/)
        * [Monitor Node Health](https://kubernetes.io/docs/tasks/debug-application-cluster/monitor-node-health/)
        * [Resource metrics pipeline](https://kubernetes.io/docs/tasks/debug-application-cluster/resource-metrics-pipeline/)
        * [Tools for Monitoring Resources](https://kubernetes.io/docs/tasks/debug-application-cluster/resource-usage-monitoring/)
        * [Troubleshoot Applications](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-application/)
        * [Troubleshoot Clusters](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-cluster/)
        * [Troubleshooting](https://kubernetes.io/docs/tasks/debug-application-cluster/troubleshooting/)
      * [Extend Kubernetes](https://kubernetes.io/docs/tasks/extend-kubernetes/)
      * [TLS](https://kubernetes.io/docs/tasks/tls/)
        * [Configure Certificate Rotation for the Kubelet](https://kubernetes.io/docs/tasks/tls/certificate-rotation/)
        * [Manage TLS Certificates in a Cluster](https://kubernetes.io/docs/tasks/tls/managing-tls-in-a-cluster/)
        * [Manual Rotation of CA Certificates](https://kubernetes.io/docs/tasks/tls/manual-rotation-of-ca-certificates/)
      * [Manage Cluster Daemons](https://kubernetes.io/docs/tasks/manage-daemon/)
        * [Perform a Rolling Update on a DaemonSet](https://kubernetes.io/docs/tasks/manage-daemon/update-daemon-set/)
        * [Perform a Rollback on a DaemonSet](https://kubernetes.io/docs/tasks/manage-daemon/rollback-daemon-set/)
      * [Service Catalog](https://kubernetes.io/docs/tasks/service-catalog/)
      * [Networking](https://kubernetes.io/docs/tasks/network/)
      * [Extend Kubectl With Plugins](https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/)
      * [Manage HugePages](https://kubernetes.io/docs/tasks/manage-hugepages/scheduling-hugepages/)
      * [Schedule GPUs](https://kubernetes.io/docs/tasks/manage-gpus/scheduling-gpus/)
    * [Tutorials](https://kubernetes.io/docs/tutorials/)
      * [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
      * [Configure Redis Using a ConfigMap](https://kubernetes.io/docs/tutorials/configuration/configure-redis-using-configmap/)
      * [Exposing an External IP Address to Access an Application in a Cluster](https://kubernetes.io/docs/tutorials/stateless-application/expose-external-ip-address/)
      * [Example: Deploying PHP Guestbook Application With Redis](https://kubernetes.io/docs/tutorials/stateless-application/guestbook/)
      * [StatefulSet Basics](https://kubernetes.io/docs/tutorials/stateful-application/basic-stateful-set/)
      * [Example: WordPress and MySQL With Persistent Volumes](https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/)
      * [Example: Deploying Cassandra With StatefulSets](https://kubernetes.io/docs/tutorials/stateful-application/cassandra/)
      * [Running Zookeeper, A CP Distributed System](https://kubernetes.io/docs/tutorials/stateful-application/zookeeper/)
      * [Restrict a Container's Access to Resources With AppArmor](https://kubernetes.io/docs/tutorials/clusters/apparmor/)
      * [Restrict a Container's Syscalls with SecComp](https://kubernetes.io/docs/tutorials/clusters/seccomp/)
      * [Using Source IP](https://kubernetes.io/docs/tutorials/services/source-ip/)
    * [Reference](https://kubernetes.io/docs/reference/)
      * [Glossary](https://kubernetes.io/docs/reference/glossary/?fundamental=true)
      * [Using the Kubernetes API](https://kubernetes.io/docs/reference/using-api/)
      * [Accessing the API](https://kubernetes.io/docs/reference/access-authn-authz/)
      * [API v 1.19](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.19/)
      * [Well-Known Labels, Annotations, and Taints](https://kubernetes.io/docs/reference/kubernetes-api/labels-annotations-taints/)
      * [Kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/)
      * [Feature Gates](https://kubernetes.io/docs/reference/command-line-tools-reference/feature-gates/)
      * [Kubelet](https://kubernetes.io/docs/reference/command-line-tools-reference/kubelet/)
      * [Kubectl CLI](https://kubernetes.io/docs/reference/kubectl/)
        * [Kubectl Overview](https://kubernetes.io/docs/reference/kubectl/overview/)
        * [JSONPath Support](https://kubernetes.io/docs/reference/kubectl/jsonpath/)
        * [Kubectl Command](https://kubernetes.io/docs/reference/kubectl/kubectl/)
        * [Kubectl Cheatsheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
        * [Kubectl Commands](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands)
        * [Kubectl for Docker Users](https://kubernetes.io/docs/reference/kubectl/docker-cli-to-kubectl/)
        * [Kubectl Usage Conventions](https://kubernetes.io/docs/reference/kubectl/conventions/)
      * [Scheduling](https://kubernetes.io/docs/reference/scheduling/)
        * [Scheduling Policies](https://kubernetes.io/docs/reference/scheduling/policies/)
        * [Scheduler Configuration](https://kubernetes.io/docs/reference/scheduling/config/)
* [Kubernetes Tutorial for Beginners - Full Course in 4 Hours - TechWorld with Nana](https://www.youtube.com/watch?v=X48VuDVv0do)
* TechWorld with Nana: [Kubernetes Architecture explained | Kubernetes Tutorial 15](https://www.youtube.com/watch?v=umXEmn3cMWY) & [Complete Application Deployment using Kubernetes Components | Kubernetes Tutorial 20](https://www.youtube.com/watch?v=EQNO_kM96Mo)
* [Learning Containers, Kubernetes, and Backend Development - Ivan Velichko](https://iximiuz.com/en/)
* [Kubernetes — What Is It, What Problems Does It Solve and How Does It Compare With Alternatives? - Srikanth Koraveni](https://medium.com/@srikanth.k/kubernetes-what-is-it-what-problems-does-it-solve-how-does-it-compare-with-its-alternatives-937fe80b754f?)
* [Kubernetes Patterns - Bilgin Ibryam and Roland Huß (PDF)](https://www.redhat.com/cms/managed-files/cm-oreilly-kubernetes-patterns-ebook-f19824-201910-en.pdf)
* [Kubernetes Basics - Brendon Burns (Microsoft)](https://www.youtube.com/playlist?list=PLLasX02E8BPCrIhFrc_ZiINhbRkYMKdPT)
* [kubernetes-doc-pdf](https://github.com/dohsimpson/kubernetes-doc-pdf)
* [Kubernetes Design Principles: Understand the Why - Saad Ali (KubeCon North America 2018)](https://www.youtube.com/watch?v=ZuIQurh_kDk)
* [70 Best Kubernetes Tutorials - AquaSec](https://www.aquasec.com/wiki/display/containers/70+Best+Kubernetes+Tutorials)
* [Dissecting Kubernetes (K8s) - An Intro to Main Components - Joshua Sheppard](https://www.infoq.com/presentations/kubernetes-yaml)
* [Kubernetes Design Principles: Understand the Why - Saad Ali (KubeCon + CloudNativeCon 2018)](https://www.youtube.com/watch?v=ZuIQurh_kDk)
* [Kubernetes in About 45 Minutes - Philip Lombardi (DevOpsDays Boston 2017)](https://www.youtube.com/watch?v=D6vkeowf9f4)
* 9 Steps to Awesome With Kubernetes - Burr Sutter (3 hours, Devoxx Belgium 2018): [Video](https://www.youtube.com/watch?v=ZpbXSdzp_vo) | [Slides](https://docs.google.com/presentation/d/1QeDOfgnJO5vCftBFsA8iU3xP1FUTRXYfeVCuY_ZJTdo/edit#slide=id.g3e7ff8d655_0_600) | [Code](https://github.com/burrsutter/9stepsawesome)
* [Learn Kubernetes in Under 3 Hours: A Detailed Guide to Orchestrating Containers - Rinor Maloku](https://medium.freecodecamp.org/learn-kubernetes-in-under-3-hours-a-detailed-guide-to-orchestrating-containers-114ff420e882)
* [Kubernetes Best Practices - Sandeep Dinesh (Google)](https://www.youtube.com/playlist?list=PLIivdWyY5sqL3xfXz5xJvwzFW_tlQB_GB)
* [Kubernetes: Container Orchestration and Micro-Services - Alexander Mohr (University of Washington)](https://courses.cs.washington.edu/courses/cse550/16au/notes/kubernetes.pdf)
* [Awesome-Kubernetes](https://www.gitbook.com/book/ramitsurana/awesome-kubernetes/details)
* [Kubernetes Youtube channel](https://www.youtube.com/channel/UCZ2bu0qutTOM0tHYa_jkIwg)
* [Kubernetes By Example - OpenShift](http://kubernetesbyexample.com/)
* [Infrastructure in the New World of Containers: What are your options? - Austen Novis (DevOpsDays Boston 2018](http://confreaks.tv/videos/devopsdaysboston2018-infrastructure-in-the-new-world-of-containers-what-are-your-options)
* [Kubernetes the Hard Way - Kelsey Hightower](https://github.com/kelseyhightower/kubernetes-the-hard-way) & [Kubernetes the Easy Way - James Ward](https://github.com/jamesward/kubernetes-the-easy-way)
* [Kubernetes Failure Stories](https://k8s.af/) & [Github](https://github.com/hjacobs/kubernetes-failure-stories)
* [Kubernetes in Real Life - Ian Crosby (GOTO Conference 2017)](https://www.youtube.com/watch?v=UUt7SuG3nW4)
* [Troubleshooting & Debugging Microservices in Kubernetes - Ray Tsang & Robert Kubis (GOTO 2018)](https://www.youtube.com/watch?v=2hxTTyc6IH8)
* [The ins and outs of networking in Google Container Engine and Kubernetes - Tim Hockin and Michael Rubin (Google Cloud Next '17)](https://www.youtube.com/watch?v=y2bhV81MfKQ)
* [Kubernetes Webinars - Janakiram & Associates](https://www.youtube.com/playlist?list=PLF3s2WICJlqOiymMaTLjwwHz-MSVbtJPQ)
* [Running Kubernetes in Production - Zalendo Tech](http://kubernetes-on-aws.readthedocs.io/en/latest/admin-guide/kubernetes-in-production.html) & [Kubernetes on AWS @Zalando - David Aronchick](https://www.youtube.com/watch?time_continue=2671&v=XmnhzEoengI)
* [Kubernetes 101 for Developers - Ross Kukulinski](https://github.com/rosskukulinski/kubernetes-101-for-devs)
* [Kubernetes Under the Hood](https://mvallim.github.io/kubernetes-under-the-hood/)
* [KataCoda (interactive browser-based labs, courses, & playgrounds)](https://katacoda.com/learn)
* [Kubernetes in production - blue-green deployment, auto scaling and deployment automation - Paul Bakker (Devoxx UK 2016)](https://www.youtube.com/watch?v=-Ci4vd4rh4M)
* [Chick-Fil-A: Milking the Most out of 1000's of K8s Clusters - Caleb Hurd & Brian Chambers (QCon NYC 2018)](https://www.infoq.com/presentations/chick-fil-a-k8-clusters)

#### DEVOPS - KUBERNETES - ARGO

* [Argo: Open source Kubernetes native workflows, events, CI and CD](https://argoproj.github.io/) | [Github](https://github.com/argoproj/argo)
* Argo CD: [Website](https://argoproj.github.io/argo-cd/) | [Github](https://github.com/argoproj/argo-cd/)
* [Introduction to Argo CD : Kubernetes DevOps CI/CD - Marcel Dempers](https://www.youtube.com/watch?v=2WSJF7d8dUg)
* [GitOps at Scale with Jenkins and Argo CD on Kubernetes - Mukulika Kapas & Deepthi Panthula](https://www.youtube.com/watch?v=4owbdHzfyMY)

#### DEVOPS - KUBERNETES - BEST PRACTICES

* [Validating Kubernetes YAML for best practice and policies - Amit Saha](https://learnk8s.io/validating-kubernetes-yaml)
* [Kubeval](https://www.kubeval.com/)
* [Kube-score](https://github.com/zegl/kube-score)
* [Config-lint](https://stelligent.github.io/config-lint/#/)
* [Copper](https://github.com/cloud66-oss/copper)
* [Conftest](https://www.conftest.dev/)
* [Polaris](https://github.com/FairwindsOps/polaris)

#### DEVOPS - KUBERNETES - BLOGS

* [Codefresh](https://codefresh.io/kubernetes-tutorial/)
* [Kubernetes.io](https://kubernetes.io/blog/)
* [LearnK8s](https://learnk8s.io/blog)
* [Rancher Blog](https://www.suse.com/c/rancherblog/)

#### DEVOPS - KUBERNETES - BRIGADE

* Brigade: Event-based Scripting for Kubernetes (Microsoft): [Website](https://brigade.sh/) | [Docs](https://docs.brigade.sh/) | [Github](https://github.com/Azure/brigade)
* Kashti: Brigade pipeline dashboard: [Github](https://github.com/Azure/kashti)
* [Brigade: Scripting Container Workflows on Kubernetes - Radu Matei (CNCF webinar)](https://www.cncf.io/webinars/brigade-scripting-container-workflows-on-kubernetes/)

#### DEVOPS - KUBERNETES - CHAOS ENGINEERING

* [Kube-monkey: implementation of Netflix's Chaos Monkey for Kubernetes clusters](https://github.com/asobti/kube-monkey)
* [PowerfulSeal: adds chaos to your Kubernetes clusters, so that you can detect problems](https://github.com/bloomberg/powerfulseal)

#### DEVOPS - KUBERNETES - CILIUM

* [Cilium.io](https://cilium.io/) | [Docs](https://docs.cilium.io/en/stable/intro/) | [Github](https://github.com/cilium/cilium)
* [Use Cilium for NetworkPolicy](https://kubernetes.io/docs/tasks/administer-cluster/network-policy-provider/cilium-network-policy/)
* [eCHO - eBPF & Cilium Office Hours](https://www.youtube.com/playlist?list=PLDg_GiBbAx-mY3VFLPbLHcxo6wUjejAOC)
* [eBPF Summit 2021](https://www.youtube.com/playlist?list=PLDg_GiBbAx-laA5GG_WnbojJ44AV2uvZn)

#### DEVOPS - KUBERNETES - CONFIG MAPS & SECRETS

* [ConfigMap and Secret as Volume Types - TechWorld with Nana](https://www.youtube.com/watch?v=FAnQTgr04mU)

#### DEVOPS - KUBERNETES - CONTAINERIZATION

* [Containers From Scratch - Liz Rice (GOTO 2018)](https://www.youtube.com/watch?v=8fi7uSYlOdc)
* [Containers From Scratch: The Sequel - Liz Rice (Container Camp)](https://www.youtube.com/watch?v=_TsSmSu57Zo)
* [Building Small Containers: Kubernetes Best Practices - Sandeep Dinesh (Google)](https://www.youtube.com/watch?v=wGz_cbtCiEA)

##### DEVOPS - KUBERNETES - CONTAINERIZATION - LXD (LINUX CONTAINERS)

* [LXD Containers: Getting Started](https://www.youtube.com/playlist?list=PL34sAs7_26wPfLNZ5NKoH0RKbTAWMlh2I)

#### DEVOPS - KUBERNETES - CONTOUR

* [Contour: Kubernetes ingress controller using Lyft's Envoy proxy - Heptio](https://github.com/heptio/contour)
* [Contour: Advanced Ingress with Envoy - Josh Rosso](https://www.youtube.com/watch?v=O7HfkgzD7Z0)
* [TGI Kubernetes 056: Heptio Contour and IngressRoute - Joe Beda](https://www.youtube.com/watch?v=BSKU6QHOvVE)

#### DEVOPS - KUBERNETES - CROSSPLANE

* [Crossplane.io: Manage any infrastructure your applications need directly from Kubernetes](https://crossplane.io/) | [Github](https://github.com/crossplaneio/crossplane)

#### DEVOPS - KUBERNETES - DEBUGGING

* [A visual guide on troubleshooting Kubernetes deployments - Daniele Polencic](https://learnk8s.io/troubleshooting-deployments)

#### DEVOPS - KUBERNETES - DEPLOYMENT

* [Kafka Operator: Managing and Operating Kafka Clusters in Kubernetes [A] - Nenad Bogojevic](https://www.youtube.com/watch?v=jAz8sdO1rgE)
* [Lessons learned form Kafka in production Tim Berglund (2017)](https://www.youtube.com/watch?v=1vLMuWsfMcA)

#### DEVOPS - KUBERNETES - DISTROLESS

* [Distroless: Language-focused Docker images, minus the operating system (Google Container Tools)](https://github.com/GoogleContainerTools/distroless)

#### DEVOPS - KUBERNETES - DRAFT

* Draft - Streamlined Kubernetes Development: [Draft.sh](https://draft.sh/) | [Quickstart](https://github.com/Azure/draft/blob/master/docs/quickstart.md) | [Examples & Tutorials](https://github.com/Azure/draft/blob/master/docs/examples-and-tutorials.md) | [Advanced Setup](https://github.com/Azure/draft/blob/master/docs/advanced-setup.md) | [Github](https://github.com/Azure/draft)

#### DEVOPS - KUBERNETES - EKS (AWS)

See [DEVOPS - AWS (AMAZON WEB SERVICES) - KUBERNETES / EKS](#devops---aws-amazon-web-services---kubernetes--eks)

#### DEVOPS - KUBERNETES - GARDEN

* Garden: Development orchestrator for Kubernetes, containers and functions: [Garden.io](https://garden.io/) | [Github](https://github.com/garden-io/garden)

#### DEVOPS - KUBERNETES - GATEKEEPER

* [Gatekeeper: Policy Controller for Kubernetes](https://github.com/open-policy-agent/gatekeeper)

#### DEVOPS - KUBERNETES - GKE (GOOGLE CLOUD)

See [DEVOPS - GOOGLE CLOUD - KUBERNETES](#devops---google-cloud---kubernetes)

#### DEVOPS - KUBERNETES - HARBOR

* [Intro to Harbor - Alex Xu & Steven Ren (KubeCon Europe 2020)](https://www.youtube.com/watch?v=PmCCzyxMv8s)
* [Harbor: Manage and serve container images in a secure environment](https://goharbor.io/)
* [Intro: Harbor - James Zabala & Henry Zhang (KubeCon + CloudNativeCon Seattle 2018)](https://www.youtube.com/watch?v=RZQVBWwGa2s)

#### DEVOPS - KUBERNETES - HELM

* Helm (package manager for Kubernetes): [Website](https://helm.sh/) | [docs](https://docs.helm.sh/) | [Github](https://github.com/kubernetes/helm) | [Twitter](https://twitter.com/helmpack)
* [What is Helm in Kubernetes? Helm and Helm Charts explained | Kubernetes Tutorial 23 - TechWorld with Nana](https://www.youtube.com/watch?v=-ykwb1d0DXU)
* [Making the Most of Helm 3 - Dan Garfield & Anna Baker](https://www.youtube.com/watch?v=EfV5fOK9IRU)
* [Deep Dive into Helm - Scott Rigby & Paul Czarkowski](https://www.youtube.com/watch?v=UfASpCJOdiw)
* [Hands-On Helm - Jessica Deen](https://www.youtube.com/watch?v=6d6L4-ADF-M)
* [Intro: Helm - Matt Farina (KubeCon + CloudNativeCon Seattle 2018)](https://www.youtube.com/watch?v=0xJc3d43kn0)
* [Helm 101: Tame the chaos of your Kubernetes apps with Helm charts - Sahdev Zala et al.](https://wdc.objectstorage.softlayer.net/v1/AUTH_7046a6f4-79b7-4c6c-bdb7-6f68e920f6e5/Code-Videos/helm-101/static/helm101.pdf)
* [Continuous Delivery for Kubernetes Apps with Helm & ChartMuseum - Josh Dolitsky & Stef Arnold](https://www.youtube.com/watch?v=u3VqswB-TJo)
* [Deep Dive: Helm - Matt Butcher & Adam Reese (KubeCon + CloudNativeCon Seattle 2018)](https://www.youtube.com/watch?v=V8VCdlpWWr8)
* [Helm your way with Kubernetes - ANA MIHĂLCEANU (Voxxed Days 201)](https://www.youtube.com/watch?v=tGKk-KfwnQw)
* [Configure RBAC In Your Kubernetes Cluster: Enable Helm in Your Cluster - Bitnami](https://docs.bitnami.com/kubernetes/how-to/configure-rbac-in-your-kubernetes-cluster/)
* [Helm - the Better Way to Deploy on Kubernetes - Reinhard Nägele (Codemotion Amsterdam 2018)](https://www.youtube.com/watch?v=3q0R5x6mBZg) & [Github repo](https://github.com/unguiculus/hello-world)
* [Building an Application Catalog with Helm and Kubernetes - Rajashree Mandaogane and Jason Greathouse (Rancher Labs)](https://www.youtube.com/watch?v=knvsqzJOIz4)
* [Your First Microservice with Kubernetes, Helm Charts, and Redis - Dan Garfield (RedisConf 2018)](https://www.youtube.com/watch?v=ywEb_c6HVew) | [Github code](https://github.com/todaywasawesome/example-voting-app)
* [Optimising Kubernetes deployments with Helm - Erwin de Gier (Devoxx Belgium 2018)](https://www.youtube.com/watch?v=TXZBuBQpm-Q)
* [Continuous Delivery to Kubernetes with Jenkins and Helm - David Currie (INDEX San Francisco)](https://www.youtube.com/watch?v=xzbMHj1ly9c)
* [Helm Chart Patterns - Vic Iglesias (KubeCon)](https://www.youtube.com/watch?v=WugC_mbbiWU)
* [Building an Application Catalog with Helm and Kubernetes - Rajashree Mandaogane & Jason Greathouse (Rancher Labs 2018)](https://www.youtube.com/watch?v=knvsqzJOIz4)
* [Automating Kubernetes deployments with Helm and Gitlab CI - Peter Rossbach](https://www.youtube.com/watch?v=VzPdTMLgAxg)
* [Running MySQL on Kubernetes - Patrick M. Galbraith (KubeCon + CloudNativeCon 2018)](https://www.youtube.com/watch?v=g924HDB81oc)

##### DEVOPS - KUBERNETES - HELM - CHART MUSEUM

* [ChartMuseum.com](https://chartmuseum.com/) | [Github](https://github.com/helm/chartmuseum)

##### DEVOPS - KUBERNETES - HELM - CHARTS

* [Artifact Hub](https://artifacthub.io/) & [Helm Hub](https://hub.helm.sh/)
* [KubeApps.com (Helm charts)](https://hub.kubeapps.com/)
* [Awesome-Helm](https://github.com/cdwv/awesome-helm)
* [Chart Museum](https://hub.helm.sh/charts/stable/chartmuseum)
* [CockroachDB](https://hub.kubeapps.com/charts/stable/cockroachdb)
* [CouchDB](https://hub.kubeapps.com/charts/couchdb/couchdb)
* [Dask](https://hub.helm.sh/charts/dask/dask)
* [Docker Registry](https://hub.kubeapps.com/charts/stable/docker-registry)
* [Gitlab](https://hub.helm.sh/charts/gitlab/gitlab)
* [Grafana](https://hub.kubeapps.com/charts/stable/grafana)
* [Grafana examples](https://logit.io/blog/post/the-top-21-grafana-dashboards-and-visualisations)
* [Graphite](https://hub.kubeapps.com/charts/stable/graphite)
* [JanusGraph](https://hub.kubeapps.com/charts/stable/janusgraph)
* [Jenkins](https://hub.kubeapps.com/charts/stable/jenkins)
* [JMeter](https://hub.helm.sh/charts/stable/distributed-jmeter)
* [Kafka (Bitnami)](https://hub.helm.sh/charts/bitnami/kafka)
* [Kafka (incubator)](https://hub.helm.sh/charts/incubator/kafka)
* [Kafka Manager](https://hub.helm.sh/charts/stable/kafka-manager)
* [Kibana](https://hub.kubeapps.com/charts/stable/kibana)
* [Kong](https://hub.kubeapps.com/charts/stable/kong)
* [Kubernetes Dashboard](https://hub.kubeapps.com/charts/stable/kubernetes-dashboard)
* [Kubernetes Operational View](https://hub.kubeapps.com/charts/stable/kube-ops-view)
* [Kubernetes Vault](https://hub.kubeapps.com/charts/incubator/kubernetes-vault)
* [Kubewatch](https://hub.kubeapps.com/charts/incubator/kubewatch)
* [Memcached](https://hub.helm.sh/charts/stable/memcached)
* [MongoDB](https://hub.helm.sh/charts/incubator/mongodb)
* [MySQL](https://hub.helm.sh/charts/stable/mysql)
* [Neo4J](https://hub.kubeapps.com/charts/stable/neo4j)
* [Nginx Ingress](https://hub.kubeapps.com/charts/stable/nginx-ingress) (see also [Nginx on Docker Hub](https://hub.docker.com/_/nginx/))
* [PostgreSQL](https://hub.kubeapps.com/charts/stable/postgresql)
* [PGAdmin](https://hub.helm.sh/charts/stable/pgadmin)
* [Prometheus](https://hub.kubeapps.com/charts/stable/prometheus)
* [RabbitMQ](https://hub.helm.sh/charts/stable/rabbitmq-ha)
* [Redis](https://hub.helm.sh/charts/stable/redis-ha)
* [Schema Registry](https://hub.kubeapps.com/charts/incubator/schema-registry)
* [Selenium](https://hub.kubeapps.com/charts/stable/selenium)
* [Spark](https://hub.helm.sh/charts/stable/spark)
* [Spinnaker](https://hub.helm.sh/charts/stable/spinnaker)
* [Vault](https://hub.kubeapps.com/charts/incubator/vault)
* [Zeppelin](https://hub.kubeapps.com/charts/stable/zeppelin)

##### DEVOPS - KUBERNETES - HELM - MONOCULAR

* [Monocular: Search-and-discovery UI for helm chart repos  (Github)](https://github.com/helm/monocular)

##### DEVOPS - KUBERNETES - HELM - PLUGINS

* [Helm Plugins Guide](https://github.com/helm/helm/blob/master/docs/plugins.md)
* [Awesome-Helm plugin list](https://github.com/cdwv/awesome-helm#plugins)
* [Chart-testing](https://github.com/helm/chart-testing)
* [Helm-diff](https://github.com/databus23/helm-diff)
* [Helm-secrets](https://github.com/futuresimple/helm-secrets)

##### DEVOPS - KUBERNETES - HELM - SHIP

* Ship - A better way to deploy Kubernetes Helm charts: [Replicated.com/Ship](https://www.replicated.com/ship) | [Github](https://github.com/replicatedhq/ship)
* [Stop Forking Helm Charts, an Intro to Replicated Ship - Marc Campbell (K8s, Kustomize & Ship SF Meetup)](https://www.youtube.com/watch?v=pRG47EQ5OAg)

#### DEVOPS - KUBERNETES - HIGH-AVAILABILITY

* [Set up highly available Kubernetes cluster step by step: Keepalived & Haproxy - Just me and Opensource](https://www.youtube.com/watch?v=SueeqeioyKY)

#### DEVOPS - KUBERNETES - INGRESS CONTROLLERS

* [Kubernetes Ingress Tutorial for Beginners | simply explained | Kubernetes Tutorial 22 - TechWorld with Nana](https://www.youtube.com/watch?v=80Ew_fsV4rM)
* [Intro to Ingress - Josh Rosso](https://kube.academy/lessons/introduction-to-ingress)
* [NGINX Ingress Controller - kubernetes.github.io](https://kubernetes.github.io/ingress-nginx/)

#### DEVOPS - KUBERNETES - ISTIO

See [DEVOPS - ISTIO.IO](#devops---istioio)

#### DEVOPS - KUBERNETES - JAEGER

* [Jaeger Operator for Kubernetes](https://github.com/jaegertracing/jaeger-operator)
* [Getting started with Jaeger to build an Istio service mesh - Daniel Oh](https://opensource.com/article/19/3/getting-started-jaeger)
* [Intro: Jaeger - Yuri Shkuro (Uber) & Pavol Loffay (Red Hat) (KubeCon + CloudNativeCon 2018 North America)](https://www.youtube.com/watch?v=WRntQsUajow)

#### DEVOPS - KUBERNETES - JENKINSX

* [Jenkins-X.io](https://jenkins-x.io/) | [Docs](https://jenkins-x.io/docs/)

#### DEVOPS - KUBERNETES - KANIKO

[Kaniko: tool to build container images from a Dockerfile, inside a container or Kubernetes cluster - Google](https://github.com/GoogleContainerTools/kaniko)

#### DEVOPS - KUBERNETES - KTUNNEL

* [ktunnel: CLI that exposes your local resources to Kubernetes](https://github.com/omrikiei/ktunnel)

#### DEVOPS - KUBERNETES - KUBECTL

* kubectl: [Cheatsheet](https://kubernetes.io/docs/user-guide/kubectl-cheatsheet/) | [Overview](https://kubernetes.io/docs/user-guide/kubectl-overview/)
* [Intro to Kubectl - John Harris](https://kube.academy/lessons/introduction-to-kubectl)
* App management docs: [Apply](https://kubectl.docs.kubernetes.io/pages/app_management/apply.html) | [Secrets & Configmaps](https://kubectl.docs.kubernetes.io/pages/app_management/secrets_and_configmaps.html) | [Container Images](https://kubectl.docs.kubernetes.io/pages/app_management/container_images.html) | [Namespaces & Names](https://kubectl.docs.kubernetes.io/pages/app_management/namespaces_and_names.html) | [Labels & Annotations](https://kubectl.docs.kubernetes.io/pages/app_management/labels_and_annotations.html) | [Field merge semantics](https://kubectl.docs.kubernetes.io/pages/app_management/field_merge_semantics.html)
* Resource printing: [Summarizing Resources](https://kubectl.docs.kubernetes.io/pages/resource_printing/summaries.html) | [JSON or Yaml](https://kubectl.docs.kubernetes.io/pages/resource_printing/raw.html) | [Fields](https://kubectl.docs.kubernetes.io/pages/resource_printing/fields.html) | [Describe](https://kubectl.docs.kubernetes.io/pages/resource_printing/describe.html)
* [Boosting your kubectl productivity - Daniel Weibel](https://learnk8s.io/blog/kubectl-productivity/)

#### DEVOPS - KUBERNETES - KUBECTX

* [kubectx - Switch between Kubernetes contexts/namespaces](https://github.com/ahmetb/kubectx)

#### DEVOPS - KUBERNETES - KUSTOMIZE (NOW PART OF KUBECTL)

* Kustomize: [Github](https://github.com/kubernetes-sigs/kustomize/) | [Kustomize.io](https://kustomize.io/) | [Workflows](https://github.com/kubernetes-sigs/kustomize/blob/master/docs/workflows.md) | [Glossary](https://github.com/kubernetes-sigs/kustomize/blob/master/docs/glossary.md) | [JSON patches](https://github.com/kubernetes-sigs/kustomize/blob/master/examples/jsonpatch.md) | [Annotated examples](https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/docs/kustomization.yaml)
* [Simplify Kubernetes YAML with Kustomize - That DevOps Guy](https://www.youtube.com/watch?v=5gsHYdiD6v8)
* [Getting started with Kustomize tool for Kubernetes - Just Me & Open Source](https://www.youtube.com/watch?v=ASK6p2r-Yrk)
* [Organizing the YAML mess with Kustomize - Florian Assmus (ContainerDays Hamburg 2019)](https://www.youtube.com/watch?v=1fCAwFGX38U) | [Code examples - Base](https://github.com/PRODYNA/cd19-spaceman-base) | [Code examples - Deployment](https://github.com/PRODYNA/cd19-spaceman-deployment)
* [Declarative Management of Kubernetes Objects Using Kustomize - Kubernetes.io](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/)
* [Kubernetes: Change base YAML config for different environments prod/test using Kustomize - Kim Wuestkamp](https://levelup.gitconnected.com/kubernetes-change-base-yaml-config-for-different-environments-prod-test-6224bfb6cdd6)
* Intro to Kustomize - Nick Chase: [Part 1: Creating a Kubernetes app out of multiple pieces](https://www.mirantis.com/blog/introduction-to-kustomize-part-1-creating-a-kubernetes-app-out-of-multiple-pieces/) | [Part 2:  Overriding values with overlays](https://www.mirantis.com/blog/introduction-to-kustomize-part-2-overriding-values-with-overlays/)
* [Kustomize: Kubernetes Configuration Management, The Easy Way - Pieter Vincken](https://ordina-jworks.github.io/cloud/2019/09/18/kustomize.html)
* [Kustomize Examples](https://github.com/kubernetes-sigs/kustomize/tree/master/examples) | [More Kustomize Examples](https://kubectl.docs.kubernetes.io/pages/examples/kustomize.html) | [Kustomize Reference](https://kubectl.docs.kubernetes.io/pages/reference/kustomize.html)
* [Kustomize - The right way to do templating in Kubernetes - Kevin Davin](https://blog.stack-labs.com/code/kustomize-101/)
* Mithil Shah: [Kubernetes Kustomize – YAML Configuration Management](http://www.studytrails.com/devops/kubernetes/kubernetes-kustomize-yaml-configuration-management/) & [Kubernetes Kustomize for Multiple Environments](http://www.studytrails.com/devops/kubernetes/kubernetes-kustomize-for-multiple-environments/)
* [Kustomize: Deploy Your App with Template Free YAML - Ryan Cox, Lyft](https://www.youtube.com/watch?v=ahMIBxufNR0)
* [TGI Kubernetes 072: Kustomize and friends - Joe Beda](https://www.youtube.com/watch?v=NFnpUlt0IuM)
* [Kustomize: Kubernetes Configuration Customization - Jeff Regan (K8s, Kustomize & Ship SF Meetup)](https://www.youtube.com/watch?v=WWJDbHo-OeY)

#### DEVOPS - KUBERNETES - LOGGING

* [Stern: Multi-pod & container log tailing for Kubernetes](https://github.com/wercker/stern)
* [Kail: Kubernetes tail](https://github.com/boz/kail)
* [Kubetail: Bash script to tail Kubernetes logs from multiple pods](https://github.com/johanhaleby/kubetail)

#### DEVOPS - KUBERNETES - LONGHORN

* Longhorn (block storage for persistent disk): [Github](https://github.com/longhorn/longhorn) | [Docs](https://longhorn.io/docs/1.0.0/what-is-longhorn/)

#### DEVOPS - KUBERNETES - MICROK8S

* MicroK8s: [Website](https://microk8s.io/) | [Github](https://github.com/ubuntu/microk8s)
* [Learn Kubernetes with MicroK8s - Jamie Phillips (DevOps Knoxville, Jan 2020)](https://www.youtube.com/watch?v=qmnH5Z4nsRU)

#### DEVOPS - KUBERNETES - MONITORING

* [Kubernetes Dashboard](https://github.com/kubernetes/dashboard)
* [Application Introspection & Debugging](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-application-introspection/)
* [Kubernentes monitoring architecture](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/instrumentation/monitoring_architecture.md)

#### DEVOPS - KUBERNETES - NAMESPACES

* [Kubernetes Namespaces Explained in 15 mins - TechWorld with Nana](https://www.youtube.com/watch?v=K3jNo4z5Jx8)

#### DEVOPS - KUBERNETES - NETWORKING

* [Kubernetes Networking Intro and Deep-Dive - Bowei Du & Tim Hockin (CNCF 2020)](https://www.youtube.com/watch?v=tq9ng_Nz9j8)
* [Everything You Need to Know About Kubernetes Networking - Projet Calico](https://www.youtube.com/playlist?list=PLoWxE_5hnZUZMWrEON3wxMBoIZvweGeiq)
* [Deep dive into Kubernetes networking - Sreenivas Makam (Container Conference 2018)](https://www.youtube.com/watch?v=NUt9VVG_gac)
* [Organizing Kubernetes with Namespaces - Sandeep Dinesh (Kubernetes Best Practices)](https://www.youtube.com/watch?v=xpnZX3if9Tc)
* [Kubernetes Networking Master Class (Rancher Labs)]https://www.youtube.com/watch?v=GXq3FS8M_kw)
* [Leveraging Kubernetes Services & DNS - Christopher Liljenstolpe](https://www.youtube.com/watch?v=VR8ep5Wf_MA)

##### DEVOPS - KUBERNETES - NETWORKING - CALICO

* [Getting started with Calico Network Policy in Kubernetes - Jessica Deen](https://www.youtube.com/watch?v=0zCHtrEJ9Bc)
* [Calico Routing Modes - octetz](https://www.youtube.com/watch?v=MpbIZ1SmEkU)

#### DEVOPS - KUBERNETES - OPERATORS

* [OperatorHub.io](https://operatorhub.io/)
* [Awesome Operators](https://github.com/operator-framework/awesome-operators)
* [How to explain Kubernetes Operators in plain English - Kevin Casey](https://enterprisersproject.com/article/2019/2/kubernetes-operators-plain-english)
* [Kubernetes Operators - Steven Acreman](https://kubedex.com/operators/)
* [Operator Framework Github repos](https://github.com/operator-framework)
* [TGI Kubernetes 037: Operator Framework - Kris Nova](https://www.youtube.com/watch?v=Ko_WfXRAypY)

##### DEVOPS - KUBERNETES - OPERATORS - CASSANDRA

* [CassKop - Orange Open Source](https://github.com/Orange-OpenSource/casskop)
* [cassandra-operator - instaclustr](https://github.com/instaclustr/cassandra-operator)

##### DEVOPS - KUBERNETES - OPERATORS - ELASTICSEARCH

* [Elastic Cloud](https://github.com/elastic/cloud-on-k8s)

##### DEVOPS - KUBERNETES - OPERATORS - GITLAB

* [Gitlab Operator](https://gitlab.com/gitlab-org/charts/components/gitlab-operator/)

##### DEVOPS - KUBERNETES - OPERATORS - PROMETHEUS

* [Prometheus Operator](https://github.com/coreos/prometheus-operator)

#### DEVOPS - KUBERNETES - PERSISTENT VOLUMES

* [Kubernetes Volumes explained | Persistent Volume, Persistent Volume Claim & Storage Class - TechWorld with Nana](https://www.youtube.com/watch?v=0swOh5C3OVM)
* [Using EBS and EFS as Persistent Volume in Kubernetes - Samson Gunalan](https://containerjournal.com/2019/04/08/using-ebs-and-efs-as-persistent-volume-in-kubernetes/)
* [Resizing Persistent Volumes using Kubernetes - Hemant Kumar](https://kubernetes.io/blog/2018/07/12/resizing-persistent-volumes-using-kubernetes/)

#### DEVOPS - KUBERNETES - PODCASTS

* [PodCTL - Brian Gracely & Tyler Britten](https://itunes.apple.com/us/podcast/podctl-containers-kubernetes-openshift/id1270983443)
* [Kubernetes Podcast - Google](https://kubernetespodcast.com/)

#### DEVOPS - KUBERNETES - ROLE-BASED ACCESS CONTROL (RBAC)

* [Limiting access to Kubernetes resources with RBAC - Arthur Chiao](https://learnk8s.io/rbac-kubernetes)
* [Using RBAC Authorization - Kubernetes.io](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
* [audit2rbac: Autogenerate RBAC policies based on Kubernetes audit logs - Jordan Liggitt](https://github.com/liggitt/audit2rbac)
* [Kubernetes Identity Management: Authentication - Marc Boorshtein](https://www.linuxjournal.com/content/kubernetes-identity-management-authentication)
* [Role Based Access Control (RBAC) with Kubernetes - School of DevOps](https://www.youtube.com/watch?v=BLktpM--0jA)
* [Effective RBAC - Jordan Liggitt (KubeCon + CloudNativeCon North America 2017)](https://www.youtube.com/watch?v=Nw1ymxcLIDI)
* [Role-based access control (RBAC) policies in Kubernetes (CNCF)](https://www.youtube.com/watch?v=CnHTCTP8d48)
* [Configure RBAC In Your Kubernetes Cluster - Bitnami](https://docs.bitnami.com/kubernetes/how-to/configure-rbac-in-your-kubernetes-cluster/)
* [User Authentication and Authorization in Kubernetes - Neependra Khare](https://www.youtube.com/watch?v=2wyUQ_5eHxI)
* [Understanding (finally!) Role-based Access Control in Kubernetes - Javier J. Salmeron (Krakow Cloud Native)](https://www.youtube.com/watch?v=9iDZHaVre2c)

#### DEVOPS - KUBERNETES - ROOK

* [Rook (Github)](https://github.com/rook/rook)
* [Kubernetes - Getting Started With Rook - Tim Serewicz](https://www.youtube.com/watch?v=wIRMxl_oEMM)
* [Intro: Rook - Jared Watts (KubeCon + CloudNativeCon Seattle 2018)](https://www.youtube.com/watch?v=pwVsFHy2EdE)

#### DEVOPS - KUBERNETES - SAMPLE APPS

* [Kubernetes Examples - Kubernetes](https://github.com/kubernetes/examples)
* [Sam's Robot Shop - Instana](https://github.com/instana/robot-shop/tree/master/K8s/descriptors)

#### DEVOPS - KUBERNETES - SECURITY

* [Distroless: Language-focused Docker images, minus the operating system (truly minimal) - Google](https://github.com/GoogleContainerTools/distroless)
* [Kubeaudit (Shopify)](https://github.com/Shopify/kubeaudit)
* [kube-bench: checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark](https://github.com/aquasecurity/kube-bench) | [Tech N’ Talk: Implementing CIS Kubernetes Security Benchmarks with Kube-Bench - Liz Rice](https://blog.openshift.com/tech-n-talk-implementing-cis-kubernetes-security-benchmarks-kube-bench/)
* [kube-hunter: Hunt for security weaknesses in Kubernetes clusters - Aqua Security](https://github.com/aquasecurity/kube-hunter) | [aquasec.com](https://kubehunter.aquasec.com/)
* [11 Ways (Not) to Get Hacked - Andrew Martin](https://kubernetes.io/blog/2018/07/18/11-ways-not-to-get-hacked/)
* [Top 9 Kubernetes Settings You Should Check to Optimize Security - Connor Gilbert](https://containerjournal.com/2018/07/03/top-9-kubernetes-settings-you-should-check-to-optimize-security/)
* [Kubernetes Security Best Practices - Ian Lewis](https://speakerdeck.com/ianlewis/kubernetes-security-best-practices)
* [Building Container Images Securely on Kubernetes - Jessie Frazelle](https://blog.jessfraz.com/post/building-container-images-securely-on-kubernetes/)

#### DEVOPS - KUBERNETES - SERVICE CATALOG

* [Service Catalog documentation on Kubernetes.io](https://kubernetes.io/docs/concepts/extend-kubernetes/service-catalog/) | [Documentation on svc-cat.io](https://svc-cat.io/docs/) | [Install using Helm](https://kubernetes.io/docs/tasks/service-catalog/) | [Github](https://github.com/kubernetes-incubator/service-catalog)
* [Using Services Outside Kubernetes from Kubernetes with the Service Catalog - Ara Pulido, Bitnami](https://www.youtube.com/watch?v=mowlSkpev0o)

#### DEVOPS - KUBERNETES - SKAFFOLD

* Skaffold: Easy and Repeatable Kubernetes Development: [Github](https://github.com/GoogleCloudPlatform/skaffold) | [Getting Started](https://skaffold.dev/docs/getting-started/#installing-skaffold) | [How To](https://skaffold.dev/docs/how-tos/) | [Concepts](https://skaffold.dev/docs/concepts/) | [Tutorials](https://skaffold.dev/docs/tutorials/)
* [Skaffold: happy Kubernetes workflows - Ahmet Alp Balkan](https://ahmet.im/blog/skaffold/)
* [Skaffold on Google Kubernetes Engine](https://github.com/GoogleCloudPlatform/skaffold/blob/master/docs/quickstart-gke.md)

#### DEVOPS - KUBERNETES - STATEFULSET

* [StatefulSet simply explained - TechWorld With Nana](https://www.youtube.com/watch?v=pPQKAR1pA9U)

#### DEVOPS - KUBERNETES - STERN

* [Stern: Multi pod and container log tailing for Kubernetes](https://github.com/wercker/stern)

#### DEVOPS - KUBERNETES - TELEPRESENCE

* [Telepresence: Debug your Kubernetes service locally, using your favorite debugging tools](https://www.telepresence.io/)

#### DEVOPS - KUBERNETES - TILT

* [Tilt.dev: manages local development instances for teams that deploy to Kubernetes](https://tilt.dev/) | [Github](https://github.com/windmilleng/tilt)

#### DEVOPS - KUBERNETES - TRAEFIK

* Traefik: [Docs](https://docs.traefik.io/) | [Website](https://containo.us/traefik/) | [Github](https://github.com/containous/traefik)
* [Traefik Workshop: Getting Started with Traefik - Jakub Hajek](https://traefik.io/resources/traefik-kubernetes-tutorial/)
* [Traefik Crash Course - Architecture, L7 & L4 Proxying, Weighted Round Robin, Enabling TLS 1.2/1.3 - Hussein Nasser](https://www.youtube.com/watch?v=C6IL8tjwC5E)
* [How to Use the Open Source Tool Traefik to Direct Kubernetes Traffic - Lee Carpenter](https://dzone.com/articles/how-to-use-the-open-source-tool-traefik-to-direct)
* [Traefik Proxy v2.0 Docker Basic Tutorial - Christian Martins](https://www.youtube.com/watch?v=Gk9WER6DunE)
* [How to Install Traefik 2 on Raspberry Pi - DB Tech](https://www.youtube.com/watch?v=GcNGCOMa3wc)
* [Escaping Big Tech With Traefik 2.0 - WP Engine - Chris Wiegman](https://www.youtube.com/watch?v=q1SDzUXx5mg)

#### DEVOPS - KUBERNETES - UPGRADING

* [How to upgrade a Kubernetes cluster](https://www.youtube.com/watch?v=GuWPqpjncyo)

#### DEVOPS - KUBERNETES - VIDEOS

* [KubeCon + CloudNativeCon 2019 Barcelona 2019 (343 videos)](https://www.youtube.com/playlist?list=PLj6h78yzYM2PpmMAnvpvsnR4c27wJePh3)
* [ContainerDays Hamburg 2019](https://www.youtube.com/playlist?list=PLHhKcdBlprMdg-fwPD1b3IjBRR_Ga09H0)
* [Kubernetes Day India 2019](https://www.youtube.com/playlist?list=PLj6h78yzYM2NXMGswJofR2N1pGdET_9EV)
* [KubeCon + CloudNativeCon 2018 Seattle (345 videos)](https://www.youtube.com/playlist?list=PLj6h78yzYM2PZf9eA7bhWnIh_mK1vyOfU)
* [KubeCon + CloudNativeCon 2018 (51 videos)](https://www.youtube.com/playlist?list=PLIivdWyY5sqLctSoRvWI71mQx_5kU9SQm)
* [theCUBE - KubeCon Seattle 2018](https://www.youtube.com/playlist?list=PLenh213llmcaRR96V1yvSqtz7AiU5sqp7)
* [Skillsmatter.com](https://skillsmatter.com/explore?content=skillscasts&location=&q=Kubernetes)
* [TGI Kubernetes - Heptio](https://www.youtube.com/playlist?list=PLvmPtYZtoXOENHJiAQc6HmV2jmuexKfrJ) & [Code from every episode on Github](https://github.com/heptio/tgik/tree/master/episodes)
* [KubeCon + CloudNativeCon China 2018](https://www.youtube.com/playlist?list=PLj6h78yzYM2OK087kzLgc4jTPVbZjuNfs)
* [ContainerDays Hamburg 2018](https://www.youtube.com/playlist?list=PLHhKcdBlprMcVSL5OmlzyUrFtc7ib1V4w)
* [KubeCon + CloudNativeCon 2018 - Copenhagen (354 videos!)](https://www.youtube.com/playlist?list=PLj6h78yzYM2N8GdbjmhVU65KYm_68qBmo)
* [CNCF (Cloud Native Computing Foundation) video playlists](https://www.youtube.com/channel/UCvqbFHwN-nwalWPjPUKpvTA/playlists)
* [KubeCon + CloudNativeCon 2017 - Austin](https://www.youtube.com/playlist?list=PLj6h78yzYM2P-3-xqvmWaZbbI1sW-ulZb)

#### DEVOPS - KUBERNETES - VS CODE (VISUAL STUDIO CODE)

* [Build containerized microservices faster and ship with confidence using Visual Studio Code and GitHub - Nick Greenfield](https://channel9.msdn.com/Events/Build/2020/BOD122)

### DEVOPS - LOGGING

#### DEVOPS - LOGGING - ELK (Elasticsearch + Logstash + Kibana)

* [My Elasticsearch resources](#elasticsearch)
* [My Logstash resources](#devops---logging---logstash)
* [Elasticsearch, Logstash & Kibana - Kevin Kluge](http://www.socallinuxexpo.org/scale12x-supporting/default/files/presentations/Scale12x%20-%20Intro%20to%20Elasticsearch%20%28Kluge%29.pdf)
* [Using ElasticSearch, Logstash and Kibana to Create Realtime Dashboards - Alexander Reelsen](http://gotocon.com/dl/goto-berlin-2014/GOTO_Night/logstash-kibana-intro.pdf)
* [Query Log Analysis – Using Logstash, ElasticSearch and Kibana - Niels Henrik Hagen](http://nhhagen.wordpress.com/2013/11/28/query-log-analysis-using-logstash-elasticsearch-and-kibana/)
* [Visualizing Logs Using ElasticSearch, Logstash and Kibana - Jeff Sogolov](https://www.youtube.com/watch?v=Kqs7UcCJquM)
* [Setting up Elasticsearch, Kibana, and Logstash - Daniel Dreier](https://www.ddreier.com/setting-up-elasticsearch-kibana-and-logstash/) & [Logstash Cnfiguration Dissection](https://www.ddreier.com/logstash-configuration-dissection/)

##### DEVOPS - LOGGING - ELK (Elasticsearch + Logstash + Kibana) - SHIELD (Non-free)

* [Shield (non-free ELK security product)](https://www.elastic.co/products/shield)
* [Shield documentation](http://www.elastic.co/guide/en/shield/current/index.html)

#### DEVOPS - LOGGING - ELSA

* [ELSA: Enterprise Log Search and Archive](https://code.google.com/p/enterprise-log-search-and-archive/)

#### DEVOPS - LOGGING - GRAYLOG2

* [GrayLog2](http://graylog2.org/)

#### DEVOPS - LOGGING - KIBANA

* Kibana documentation: [Current](http://www.elastic.co/guide/en/kibana/current/index.html) | [Older versions](http://www.elastic.co/guide/en/kibana/index.html)

#### DEVOPS - LOGGING - LOGSTASH

* Documentation: [Current](http://www.elastic.co/guide/en/logstash/current/index.html) | [1.4.2](http://logstash.net/docs/1.4.2/)
* [Getting Started](http://logstash.net/docs/1.4.2/tutorials/getting-started-with-logstash)
* [Logstash and Other Things - Jordan Sissel (PuppetConf 2012)](https://www.youtube.com/watch?v=RuUFnog29M4)
* [More Logstash Awesome - Jordan Sissel (PuppetConf 2013)](https://www.youtube.com/watch?v=fwMnb4-t8vo)
* [Logstash Presentation - Matthew Smith](https://www.youtube.com/watch?v=U3m0jKygAqU)
* [A Bit of Logstash Cooking](https://home.regit.org/2014/01/a-bit-of-logstash-cooking/)
* [Chef-logstash](https://github.com/lusis/chef-logstash)
* [Logstash Google Forum](https://groups.google.com/forum/?fromgroups#%21forum/logstash-users)
* [Logstash Freenode IRC](http://irc.lc/freenode/logstash/t4nk@@@)

### DEVOPS - OBSERVABILITY

* [Observability Infra Uber and Facebook - Yuri Shkuro & Michael Bevilacqua-Linn (Systems @Scale 2019)](https://www.youtube.com/watch?v=nO8AYhEok1c)

### DEVOPS - OPEN POLICY AGENT (OPA)

* [OPA Deep Dive - Tim Hinrichs, Styra & Torin Sandall, Styra (KubeCon + CloudNativeCon 2019)](https://www.youtube.com/watch?v=Uj2N9S58GLU)
* [Authorization in Micro Services World Kubernetes, ISTIO and Open Policy Agent (AppSecCali 2019)](https://www.youtube.com/watch?v=UnXjwCWgBKU)
* [TGI Kubernetes 071: Exploring the Open Policy Agent (OPA) - Joe Beda](https://www.youtube.com/watch?v=QU9BGPf0hBw)
* [Intro: Open Policy Agent - Torin Sandall (KubeCon & CloudNativeCon North America 2018)](https://www.youtube.com/watch?v=CDDsjMOtJ-c)
* [Deep Dive: Open Policy Agent - Torin Sandall (KubeCon & CloudNativeCon North America 2018)](https://www.youtube.com/watch?v=Vdy26oA3py8)
* [How Netflix Is Solving Authorization Across Their Cloud [I] - Manish Mehta & Torin Sandall](https://www.youtube.com/watch?v=R6tUNpRpdnY)

### DEVOPS - NEWS

* [The Register](http://www.theregister.co.uk/infrastructure/)
* [SiliconAngle](https://siliconangle.com/category/cloud/)

### DEVOPS - OPEN CONTAINER INITIATIVE (OCI)

* [Open Container Initiative (OCI)](https://www.opencontainers.org)

### DEVOPS - OPENSTACK

* [OpenStack.org](https://www.openstack.org/): [Overview](https://www.openstack.org/software/)
* [What is OpenStack?](http://opensource.com/resources/what-is-openstack)
* [OpenStack on Youtube](https://www.youtube.com/results?search_query=openstack) & [OpenStack Channel](https://www.youtube.com/user/OpenStackFoundation)
* [Paris Summit 2014: Videos](https://www.openstack.org/summit/openstack-paris-summit-2014/session-videos/)
* [OpenStack Superuser magazine](http://superuser.openstack.org/articles)
* [@OpenStack (Twitter)](https://twitter.com/openstack)
* [OpenStack blog](https://www.openstack.org/blog/)
* [Ubuntu on OpenStack](http://www.ubuntu.com/cloud/openstack)

### DEVOPS - PROMETHEUS

* Prometheus: [Docs](https://prometheus.io/docs/prometheus/latest/getting_started/) | [Prometheus.io](https://prometheus.io/) | [Github](https://github.com/prometheus/prometheus)
* [Prometheus Helm chart](https://hub.kubeapps.com/charts/stable/prometheus)

#### DEVOPS - PROMETHEUS - CORTEX

* [Intro: Cortex - Tom Wilkie & Bryan Boreham (KubeCon + CloudNativeCon 2019)](https://www.youtube.com/watch?v=_7Wnta-3-W0)
* [Deep Dive: Cortex - Tom Wilkie & Bryan Boreham (KubeCon + CloudNativeCon 2019)](https://www.youtube.com/watch?v=mYyFT4ChHio)

#### DEVOPS - PROMETHEUS - GRAFANA

* [Getting Started with Grafana Webinar - Marcus Olsson](https://www.youtube.com/watch?v=0n2UNzk2OaI)

### DEVOPS - RELIABILITY

* [Site Reliability Engineering: Measuring and Managing Reliability - Google Cloud (Coursera)](https://www.coursera.org/learn/site-reliability-engineering-slos)
* [Site Reliability Engineering - Google (editors: Betsy Beyer, Chris Jones, Jennifer Petoff, & Niall Richard Murphy)](https://landing.google.com/sre/book/index.html)

### DEVOPS - RKT

* [Rkt: CLI for running application containers on Linux](https://github.com/rkt/rkt)

### DEVOPS - SERVERLESS

* [Serverless NYC 2018](https://www.serverlessnyc.com/)
* [The Problem is Data - Gwen Shapira (Serverless NYC 2018)](https://www.youtube.com/watch?v=J-9afazR2o0)
* Serverlessconf: [Austin 2017](https://www.youtube.com/playlist?list=PLnwBrRU5CSTmruZzR8Z06j3pGglBZcdDr) | [NYC 2016](https://www.youtube.com/playlist?list=PLnwBrRU5CSTnd6NC6E-Fn3SJEJKRkaHJY)

### DEVOPS - SERVICE MESH

* [The Service Mesh: What Every Software Engineer Needs to Know about the World's Most Over-Hyped Technology - William Morgan](https://servicemesh.io/)

### DEVOPS - SPINNAKER.IO

* [Spinnaker.io](https://www.spinnaker.io/)
* [Spinnaker Summit 2018 conference videos](https://www.youtube.com/playlist?list=PL4yLrwUObNksZ8svJWu5HOHT3e_dpa5Ih)
* [Continuous Delivery With Spinnaker - Emily Burns et al. (PDF book)](https://www.spinnaker.io/publications/ebook/ContinuousDeliveryWithSpinnaker.pdf)
* [Using Kubernetes, Spinnaker and Istio to Manage a Multi-cloud Environment - Ameer Abbas (Cloud Next '18)](https://www.youtube.com/watch?v=kKC-VgAptII)

### DEVOPS - STATEFUL SERVICES

* [Stateful Service Design Considerations for the Kubernetes Stack - Jonas Bonér](https://www.infoq.com/articles/stateful-service-design-kubernetes)
* [Building Scalable Stateful Services - Caitie McCaffrey (Curry On 2016)](https://www.youtube.com/watch?v=aJFxQAAMAQc) & [Building Scalable Stateful Services - Caitie McCaffrey (StrangeLoop 2015)](https://www.youtube.com/watch?v=H0i_bXKwujQ)
* [Kubernetes: A Detailed Example of Deployment of a Stateful Application - Srikanth Koraveni](https://medium.com/better-programming/kubernetes-a-detailed-example-of-deployment-of-a-stateful-application-de3de33c8632)

### DEVOPS - TEKTON

* Tekton: K8s-native Pipeline resource: [Tutorial](https://github.com/tektoncd/pipeline/blob/master/docs/tutorial.md) | [Github](https://github.com/tektoncd/pipeline) | [Tekton on Google Cloud](https://cloud.google.com/tekton/) | [Roadmap](https://github.com/tektoncd/pipeline/blob/master/roadmap.md) | [Dashboard](https://github.com/tektoncd/dashboard)

### DEVOPS - TERRAFORM

* [Terraform explained in 15 minutes - TechWorld with Nana](https://www.youtube.com/watch?v=l5k1ai_GBDE)
* [Terraform course - freeCodeCamp.org](https://www.youtube.com/watch?v=SLB_c_ayRMo) (140 minutes)
* [Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code) - Sid Palas](https://www.youtube.com/watch?v=7xngnjfIlK4) (160 minutes)
* [Developing Terraform Modules at Scale - HashiCorp](https://www.youtube.com/watch?v=bDVr7RNlPsQ)
* [Azure DevOps: Provision API Infrastructure using Terraform - Full Course - Les Jackson](https://www.youtube.com/watch?v=Ff0DoAmpv6w) (125 minutes)
* [DevOps Crash Course (Docker, Terraform, and Github Actions) - Traversy Media](https://www.youtube.com/watch?v=OXE2a8dqIAI)
* [Devops Terraform Course | Automate your AWS Cloud Infrastructure | Intellipaat](https://www.youtube.com/watch?v=CwBaVZKoyWc)
* [Terraform best practices with examples and arguments - Anton Babenko](https://www.youtube.com/watch?v=mOsiLZGdXS4)

### DEVOPS - TITUS

* Titus (Netflix): [Github](https://github.com/Netflix/titus) | [Documentation](https://netflix.github.io/titus/)
* [Titus, the Netflix container management platform, is now open source - Netflix Technology Blog](https://medium.com/@NetflixTechBlog/titus-the-netflix-container-management-platform-is-now-open-source-f868c9fb5436)

### DEVOPS - VAGRANT

* [Vagrant, Packer, Serf: Maximum Potency DevOps - Mitchell Hashimoto (Kod.io 2014)](http://confreaks.tv/videos/3251-kodio_2014-vagrant-packer-serf-maximum-potency-devops)

### DEVOPS - VIDEOS

* [DevOpsDays Philly 2019](https://www.youtube.com/playlist?list=PLE7tQUdRKcyZhPbZzB8LBO-pQwaQ5NKCT)
* [DevOpsDays Boston 2019](https://www.youtube.com/playlist?list=PLKOXVA7dUqS9DFBY_IeDtsR5aH4kR3Daj)
* [DevOpsDays Chicago 2019](https://www.youtube.com/playlist?list=PLE7tQUdRKcyaVPM8O67RtKZsfo2WNySPo)
* [DevOpsDays Baltimore 2019](https://www.youtube.com/playlist?list=PLE7tQUdRKcyb-MIsb0pSgf8ZI-qz_hTh4)
* [DevUp 2018](https://www.infoq.com/dev-up-2018/presentations/]
* [DevOpsDays Boston 2018](http://confreaks.tv/events/devopsdaysboston2018)
* [DevOpsDays New York 2018](http://confreaks.tv/events/devopsdaysnyc2018)
* [DevOpsDays Baltimore 2018](https://www.youtube.com/playlist?list=PLE7tQUdRKcyZZhQVK1UhqKrVHsQ1d0I7J)
* [DevOpsDays Philadelphia 2017](http://confreaks.tv/events/devopsdaysphiladelphia2017)
* [DevOpsDays Seattle 2017](http://confreaks.tv/events/devopsdaysseattle2017)
* [DevOpsDays Chicago 2017](http://confreaks.tv/events/devopsdayschicago2017)
* [DevOpsDays Salt Lake City 2017](http://confreaks.tv/events/devopsdayssaltlakecity2017)
* [DevOpsDays Boston 2017](https://www.youtube.com/playlist?list=PLE7tQUdRKcyZfwse2URwQjCI7-qeURNxt)
* [DevOpsDays Rockies 2017](http://confreaks.tv/events/devopsdaysdenver2017)
* [DevOpsDays Boston 2016](http://confreaks.tv/events/devopsdaysboston2016)
* [DevOpsDays Rockies 2016](http://confreaks.tv/events/devopsdaysrox2016)
