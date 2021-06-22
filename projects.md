# Currently Active projects

## The biggest one:

### VDS64
[VDS64](https://vds64.com) Cloud Vitual Servers platform, it includes:
- Control panel for the users: https://cc.vds64.com (can add access for you if needed). The first version youtube tutorial (https://www.youtube.com/watch?v=cKGCDcdWMOw)
- Control panel for the support team: https://cp-support.vds64.com
- Automated monitoring and alerting system: https://status.vds64.com
Host node microservices are in closed github repos and can be opened if needed after signing an NDA agreement.

Currently hosts 9641 web site by the our distributed DNS servers (ns1.ns64.com, ns2.ns64.com) stats.

## The latest ones:

### Slavena.pro
[Slavena.pro](https://slavena.pro) Business Management System for the biggest printing and packaging manufacture in Ukraine. Was made in 6 months during first 
Covid lockdown.

Customer looking for a software company that can create a smart production and personel management system. 

Web gui for management, designers, factory managers, CEO based
on Redmine and RoR. Part of the plugins uses Python. Microservices written in NodeJS. 

- Mobile application for the stuff [App in Play Market](https://play.google.com/store/apps/details?id=com.geeksteam.slavena&hl=uk&gl=US).


Currently App on the stuff mobile devices deployed using Expo deployment system not from Play Store (but can be updated from it too).
System is running 1+ year and manages 15000 stampels, around 6000 printing orders, 60 stuff, 2 locations. System running from two different cloud locations to provide a full
backup solution in case of an hardware issues.

### Relly.me
Relly is smart home and smart doorbell system which include Mobile App, Backend part, Analytics, Device design, manufacture and microchip firmware parts. 

It is on active development stage and now we deploying 200 devides acros 30  multi-story buildings for beta tests. When we are started we are issued
a trade mark problems, thats why at the time we have three different versions, but they are the same and a few month ago at last we registered our new name for the project
and go with it now.

User mobile Apps are available at the Google Play Market and App Store as well: 
- [Мир16](https://play.google.com/store/apps/details?id=cloud.jelly.home.mir16&hl=uk&gl=US)
- [32Г](https://play.google.com/store/apps/details?id=cloud.jelly.home32g&hl=uk&gl=US)

At the moment we have around 1800 everyday active users, every ten seconds someone opens the doors, parking lots and etc, so it's a high loaded system.
We are using distributed database based on Cloudflare KV and MongoDB. Also analytics TimescaleDB. As a message layer between devices we are using MQ servers.
