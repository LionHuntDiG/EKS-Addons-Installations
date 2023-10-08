
# EKS Creation & Add-ons




## Authors

- Shanmukha nath Reddy



## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
 - Cross Plane 




## Installation

Installation of eks cluster using eksctl

- Make sure you have enough IAM Permissions to create the cluster,  i have done using Root access.
```bash
eksctl create cluster --name crossp
  
Once the cluster is created, you will see output like:
  
2023-10-04 15:20:32 [✔]  EKS cluster "crossp" in "us-east-1" region is ready

% kubectl get no
NAME                             STATUS   ROLES    AGE   VERSION
ip-192-168-22-123.ec2.internal   Ready    <none>   18m   v1.25.13-eks-43840fb
ip-192-168-42-181.ec2.internal   Ready    <none>   18m   v1.25.13-eks-43840fb
```
### Follow Below link for s3 creation using cross plane. 
https://docs.crossplane.io/v1.13/getting-started/provider-aws/


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## License

[MIT](https://choosealicense.com/licenses/mit/)


# Hi, I'm Shanmukha nath reddy! 👋
Current Role: Lead Devops Engineer 

Organisation: Impetus Technologies


