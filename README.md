# tools.devopsy.pl


## Documentation


## our websites

+ [Bash Tool – DevOps Shop](https://bashtool.com/)


## Kubeflow

+ [DSL Static Type Checking - Kubeflow](https://www.kubeflow.org/docs/components/pipelines/v1/sdk/static-type-checking/)
+ [How to install Charmed Kubeflow | Documentation | Charmed Kubeflow](https://charmed-kubeflow.io/docs/install)


## KubeVirt
+ [Virtualization with Red Hat OpenShift](https://www.redhat.com/en/technologies/cloud-computing/openshift/virtualization)



## VMware

+ [Get Started - VMware Tanzu](https://tanzu.vmware.com/get-started)
+ [Deploying the vCenter Server Appliance](https://docs.vmware.com/en/VMware-vSphere/7.0/com.vmware.vcenter.install.doc/GUID-F06BA415-66D8-42CD-9151-701BBBCE8D65.html)
+ [vSphere 7 with Kubernetes - Tanzu Kubernetes cluster - Technical Overview - YouTube](https://www.youtube.com/watch?v=BukxNlznftI)
+ [VMware vCenter Server Photon OS Security Patches](https://docs.vmware.com/en/VMware-vSphere/7.0/rn/vcenter-server-appliance-photonos-security-patches.html)
+ [All Downloads](https://customerconnect.vmware.com/downloads/#all_products)





## Tools


[Top 10 uncommon DevOps tools you should know | Top of the OPS](https://medium.com/leapp-cloud/top-10-uncommon-devops-tools-you-should-know-91dadde9777e)

> # Top 10 uncommon DevOps tools you should know
> 
> Hello everyone! You clicked here to take a laugh at yet another boring list, right? I’ll try to surprise you with a list of unique tools that you probably still don’t know! I know you already know about Git, Terraform, Jenkins, and so on, so let’s focus on the **tiny pearls** you can find out there! I’ve chosen only open-source tools to spread some love; if you find anything helpful, you can contribute back.
> 
> # 1\. Chaostoolkit
> 
> As a DevOps (and software engineer), I find chaos engineering one of the most relevant and thrilling topics to study right now. [Chaostoolkit](http://chaostoolkit.org/) it’s a perfect way to introduce into this world through a straightforward and flexible command-line tool and a way to define experiments with declarative files that you can version.
> 
> # 2\. Insomnia
> 
> I bet you all know Postman for API design, right? I prefer [Insomnia.rest](http://insomnia.rest/) since they’ve taken the extra mile to open-source the complete application and integrations through their [plugin hub](https://insomnia.rest/plugins). I know it’s a bit more popular nowadays, but I started using this when there were just a few thousand stars, and it got better and better over the years. I think the trend will keep up.
> 
> # 3\. Leapp
> 
> [Leapp](https://github.com/Noovolari/leapp) is my go-to tool for accessing my cloud accounts. I was fed up with manually managing local development and operations credentials, so I automated everything most securely. I can’t count how much time it saved me over the years.
> 
> It integrates with nearly any development tool (Terraform, CDK, etc.) and some excellent additions like connecting directly to SSM. Like Insomnia, it’s completely open-source, and the repository and slack channel are very active if you want to come around. Also, the tool is getting better at each release, and there is an excellent [roadmap](https://roadmap.leapp.cloud/tabs/4-in-progress) to keep up with what’s new.
> 
> ![](https://miro.medium.com/max/700/0*2c4eQfzVmBPBTEHU)
> 
> # 4\. Gitea
> 
> If you don’t live under a rock, you already know about mainstream git repository software like GitHub and GitLab. But what if a highly lightweight, community-driven, and self-hosted alternative exists? That’s [gitea.io](http://gitea.io/). It’s not as full-fledged as its counterparts, but it’s highly promising and painless to install and use and has a very active and welcoming community.
> 
> # 5\. Hubot
> 
> [Hubot](https://hubot.github.com/) is kind of old (at least in software terms!), but I’m amazed at how few people know about the ChatOps model. From 10000 thousand feet perspective, it’s just automation through your go-to chat software (discord, slack, rocketchat, mattermost, etc.), and Hubot paved the way to other similar tools. Maybe it’s less relevant today, but I find an interesting concept nonetheless (I love automation in any form it can take) that can solve a few issues, especially for less technical people.
> 
> # 6\. Mkdocs-material
> 
> I love markdown, and MkDocs is my go-to tool for writing documentation, but it’s pretty bare. [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) is a template that you can put mkdocs on… except it packs a whole world of additional features: versioning your documentation, a native cookie consent solution, rich search previews, and a truckload of other things… seriously give the guy 10$ a month to get supporters-only features, and you’ll get the only documentation tool you will ever need. (for instance, the [AWS Copilot CLI](https://aws.github.io/copilot-cli/) docs were written with this, see for yourself, that’s amazing).
> 
> ![](https://miro.medium.com/max/700/0*9tslhhA7-HX76Eyx)
> 
> # 7\. Podman
> 
> I’ve actively used Docker for almost all my container needs, but I’m always happy to take a look at new and emerging technologies. What got me into Podman was the daemonless architectural pattern, and nowadays, I like where the project is going. However, it’s still rough around the edges (especially the docs). Still, when I tried it out the first time, I was able to drop it in the middle of my Dockerfile, and everything just worked.
> 
> # 8\. Sshuttle
> 
> [Sshuttle](https://github.com/sshuttle/sshuttle) is an excellent tool that acts as a “poor man” VPN, allowing you to create a VPN connection from your machine to any remote server you can connect to via ssh. The exciting part is that it is not precisely a VPN and not exactly port forwarding. Internally it assembles the TCP stream locally, multiplexes it statefully over an ssh session, and disassembles it back into packets at the other end to achieve data-over-TCP, which is safe. Useful if your VPN breaks down.
> 
> # 9\. Infracost
> 
> If you’re a Terraform fan, you’ll love this one. What if I tell you you can couple your infrastructure as code with bill forecasting? Sounds fantastic, huh? That’s what [infracost.io](http://infracost.io/) is all about: it will scan through your Terraform files when you commit some changes to git and estimate the resulting billing of your changes! Pretty handy to have before getting unpleasant surprises.
> 
> ![](https://miro.medium.com/max/700/0*0QZJp_5oyoJsip3Z)
> 
> # 10\. Checkov
> 
> Ok, here’s the final pearl. [Checkov.io](http://checkov.io/) is a static code analysis tool for checking infrastructure as code misconfiguration. I cannot express how much this one can help find and fix the most basic (and advanced) security problems in your cloud infrastructure, and it comes with support to a whole world of different IaC tools. I also love it because you can run it from the command line.


# Management




[Welcome - Portainer Documentation](https://docs.portainer.io/)

> **Portainer Community Edition (CE)** is our foundation. With over half a million regular users, CE is a powerful, open source toolset that allows you to easily build and manage containers in Docker, Docker Swarm, Kubernetes and Azure ACI.
> 
> **Portainer Business Edition (BE)** is our commercial offering. With features geared towards businesses and larger organizations such as , , and
> 
> , Portainer BE is a powerful toolset that allows you to easily build and manage containers in Docker, Docker Swarm, Kubernetes and Azure ACI.
> 
> Portainer Business Edition requires a license key to install and use. If you don't currently have a license key, you can of Portainer Business Edition or purchase Portainer Business Edition for your organization by
> 
> .
> 
> Portainer hides the complexity of managing containers behind an easy-to-use UI. By removing the need to use the CLI, write YAML or understand manifests, Portainer makes deploying apps and troubleshooting problems so easy that anyone can do it.






# Monitoring



---

+ [edit](https://github.com/devopsy-pl/tools/edit/main/README.md)

