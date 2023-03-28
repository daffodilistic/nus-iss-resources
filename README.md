# List of resources for learning at NUS-ISS
Are you a new ISS student? Stuck on deciding which is the cheapest cloud provider?
Or which is the best web framework to use? This repository is for you!
## Table of Contents
- [Cloud/Managed VPS Providers](#cloudmanaged-vps-providers)
- [Domain Name Registrars](#domain-name-registrars)
- [Web Frameworks](#web-frameworks)
- [Software Libraries](#software-libraries)

### Cloud/Managed VPS Providers
| **Vendor**            | **Cost Rating** | **Complexity** | **Remarks**                                                                                                                     |
| --------------------- | --------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Oracle Cloud          | 2               | Advanced       | Free forever instances only with arm64 CPUs (as of time of writing), and requires linking a credit card to your Oracle account. |
| Google Cloud Platform | 3               | Advanced       | Free 90-day US$300 credit for GCP applied on sign up                                                                            |
| Amazon Web Services   | 4               | Expert         | Free 12-month trial                                                                                                             |
| Microsoft Azure       | 5               | Advanced       | Free 12-month trial                                                                                                             |
| Vultr                 | 1               | Simple         |                                                                                                                                 |
| Linode (Akamai)       | 2               | Simple         |                                                                                                                                 |
| Digital Ocean         | 2               | Simple         |                                                                                                                                 |

### Domain Name Registrars
| **Vendor**      | **Cost Rating** | **Complexity** | **Remarks** |
| --------------- | --------------- | -------------- | ----------- |
| Namecheap       | 1               | Simple         |             |
| Google Domains  | 1               | Simple         |             |
| GoDaddy         | 3               | Simple         |             |
| Amazon Route 53 | 2               | Simple         |             |
| Cloudflare      | 1               | Simple         |             |

### Web Frameworks
| **Vendor** | **Complexity** | **Remarks**                                                                                                                                                                                                                                                      |
| ---------- | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Django     | Advanced       | Initial setup might be difficult, but there are plenty of tutorials on the web                                                                                                                                                                                   |
| Flask      | Simple         | Same as Django, but unlike Django, this does NOT come with "batteries" (i.e. ORM, middleware, user auth, etc.)                                                                                                                                                   |
| Express    | Simple         | Good tradeoff between complexity and features. Plenty of tutorials on the web.                                                                                                                                                                                   |
| Laravel    | Advanced       | "Batteries included" (i.e. comes with an ORM, middleware, etc.) If you are familiar with PHP, this is a good choice. Note that setup might be more difficult, but it is one of the easiest to deploy since this will work with most shared web hosting providers |
| Spring     | Advanced       | Plenty of tutorials on the web, but initial setup might be difficult.                                                                                                                                                                                            |
| .NET Core  | Advanced       | Decent choice if you are familar with .NET. Plenty of tutorials on the web.                                                                                                                                                                                      |
