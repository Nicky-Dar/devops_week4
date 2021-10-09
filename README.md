# devops_week4
![image](https://user-images.githubusercontent.com/88620315/136655371-45597339-d12d-44db-af15-c132881f04d2.png)

# Version Control System(VCS)
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

##### Open source
* ArX – written by Walter Landry, started as a fork of GNU arch, but has been completely rewritten
* Bazaar – written in Python, originally by Martin Pool and sponsored by Canonical; decentralised, and aims to be fast and easy to use; can losslessly import Arch archives
* BitKeeper – was used in Linux kernel development (2002 – April 2005) until its license was revoked for breach of contract. It was open-sourced in 2016 in an attempt to broaden its appeal again.
* Codeville – written in Python originally by Ross Cohen; uses an innovative merging algorithm
* Darcs – written in Haskell and originally developed by David Roundy; can keep track of inter-patch dependencies and automatically rearrange and "cherry-pick" them using a "theory of patches"
* DCVS – decentralized and CVS-based
* Fossil – written by D. Richard Hipp for SQLite; distributed revision control, wiki, bug-tracking, and forum (all-in-one solution) with console and web interfaces. Single portable executable and single repository file.
* Git – written in a collection of Perl, C, and various shell scripts, designed by Linus Torvalds based on the needs of the Linux kernel project; decentralized, and aims to be fast, flexible, and robust
* GNU arch
* Mercurial – written in Python as an Open Source replacement to BitKeeper; decentralized and aims to be fast, lightweight, portable, and easy to use
* Monotone – developed by the Monotone Team; decentralized in a peer-to-peer way

## Git
Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).

Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development. Since 2005, Junio Hamano has been the core maintainer. As with most other distributed version control systems, and unlike most client–server systems, every Git directory on every computer is a full-fledged repository with complete history and full version-tracking abilities, independent of network access or a central server. Git is free and open-source software distributed under GNU General Public License Version 2.

For install git on linux input this command:
> sudo apt install git -y

![image](https://user-images.githubusercontent.com/88620315/136655374-7f47ced4-55ac-49a6-ae54-3ca2478b3cab.png)


> git –version

![image](https://user-images.githubusercontent.com/88620315/136655377-ea401249-73c9-48a6-92d8-5b8c9b0063f6.png)

> git config  --global user.name “Nicky-Dar”

> git config  --global user.email “Nicholausnicky.nicky@gmail.com”

> git config  --list

![image](https://user-images.githubusercontent.com/88620315/136655381-c99912a0-cadd-4de8-b3de-ab757e31ff9c.png)

> ssh-keygen

> ls /home/user/.ssh

> cat ~/.ssh/id_rsa.pub

copy the key to SSH keys on github. signin to github -> Setting -> SSH and GPG keys
![image](https://user-images.githubusercontent.com/88620315/136655488-83f1852a-86a0-4a76-9ad5-da939785f9e4.png)


> ssh -T git@github.com

![image](https://user-images.githubusercontent.com/88620315/136655437-8e4bed71-972c-4068-bb9e-1bf31c7a61f9.png)

### Repository management
-a, --all                  do not ignore entries starting with .

. git is the place to save your database folder. And the longer it will take up more memory but don't delete it. If you delete it, the previous changes won't appear.

![image](https://user-images.githubusercontent.com/88620315/136655920-1b517562-8b7f-4223-9da5-ca0c4c413d8b.png)
![image](https://user-images.githubusercontent.com/88620315/136655925-e391a8ae-8ec2-4ef7-b241-a4d2b6f88537.png)


### Git Ignore
![image](https://user-images.githubusercontent.com/88620315/136656825-3d5c53e5-ec45-4811-bc77-88739238bc87.png)
![image](https://user-images.githubusercontent.com/88620315/136656832-e854b2a6-3da8-4ef1-8cc0-1a5f62a3bc5e.png)

File1 and folder1 are not displayed because they are included in .gitignore so that if the data is pushed, file1 and folder1 are not uploaded.
![image](https://user-images.githubusercontent.com/88620315/136656833-3598fb88-fb7c-426d-a301-f43e3e2eb8cd.png)

### Git add & commit
![image](https://user-images.githubusercontent.com/88620315/136657812-8813fc59-92d6-4875-9bdf-7497203003d8.png)


![image](https://user-images.githubusercontent.com/88620315/136657817-d1c36bb4-6761-4d1b-9b04-fececc2bbc47.png)


![image](https://user-images.githubusercontent.com/88620315/136657830-fc143186-5307-4c7f-89db-b2a37f4f747d.png)


![image](https://user-images.githubusercontent.com/88620315/136657845-8685fb32-a477-4d94-a857-2ac13ebf4727.png)


![image](https://user-images.githubusercontent.com/88620315/136657855-3965b14c-060b-46b6-9242-218020b0c181.png)


![image](https://user-images.githubusercontent.com/88620315/136657866-12cb2997-890a-4b6a-9d3b-d369f07e42a5.png)


![image](https://user-images.githubusercontent.com/88620315/136657873-6d33a111-4fb5-43e8-a081-044965277d80.png)


![image](https://user-images.githubusercontent.com/88620315/136657939-ea2379b3-5b89-41f1-b859-be5af9bcf51e.png)


![image](https://user-images.githubusercontent.com/88620315/136657942-5da03f49-c9e2-4269-b6fc-17bc54562a9f.png)


![image](https://user-images.githubusercontent.com/88620315/136657945-8e2b7e2e-10a9-4ad8-b40f-52dabb8cdf5a.png)


![image](https://user-images.githubusercontent.com/88620315/136657954-88fc2c4b-20e9-4a1d-b8b8-3a88a3dd1d25.png)

#### Git Pull

![image](https://user-images.githubusercontent.com/88620315/136658033-988d11e4-cc22-47aa-a5b3-3d93e114ed67.png)


