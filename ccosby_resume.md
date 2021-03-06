# <div align="center">Christopher S. Cosby</div>
### <div align="center">ccosby@gmail.com</div>
### <div align="center">678-805-7481</div>

This CV probably does not read the way in which you're accustomed. If you
read from the bottom up, it is an autobiographical account of my career. The
skills sections that appear under each blurb are the highlights of what I
picked up during that particular assignment, not the sum total of what I know.

In short, I'm a problem solver. I like to take on new things and master them.
I don't limit myself to a single technology, or to a single way of thinking.
I'll find out what's broken and fix it, or I'll help you find a solution to a
problem you can't even quite define.

<hr/>

## W2 History

### 2/2016 - Present / *Apt Platform Technologies, Inc.* / Co-owner, CTO

After a long time in the corporate world, a partner and I decided to venture out on our own.
Most of my recent and current work has been building custom software and websites (mostly
using Python and React) and providing managed services and solutions. I have also done several
installations of campus networks and security solutions. I continue to do an unreasonable number
of API integrations allowing clients to move data between disparate systems. Much of my work is
built using Docker. That includes using and creating docker-compose and creating Dockerfiles (*please
don't judge me for really enjoying creating the smallest most function Docker image possible*).)
I've played with k8s just enough to know that I want to spend more time digging deep. I miss the old
Docker Swarm functionality. With every sentence I write here, I remember how many Things I've used
that never made it to this CV.

* Python 2/3
  * The fancy new asycio with coroutines
  * FastAPI / alembic / Pydantic / SQLAlchemy
  * Django
  * pyenv / pipenv / poetry
  * boto3 for AWS
* Javascript / Frontend
  * ReactJS
  * jQuery
* Public Cloud
  * Amazon Web Services
  * DigitalOcean
* Docker (much experience)
  * Everything at https://hub.docker.com/orgs/aptplatforms is mine
* Kubernetes (limited practical experience)
* Augeas (and I pronounce it almost like *obvious*)

### 10/2012 - 2/2016 / *Cisco Systems, Inc.* / Software Engineer, DNCS Platform

This position defined much of my career. The "Platform" responsibility is
more systems integration and automation than software engineer. I'm
responsible for making our products installable by "any passerby on the street
with no computer experience". I've learned to write scripts of all types: Bourne
shell, Korn shell, BASH, Perl, Python, Ruby, etc. The product was initially
shipped on Sun SPARC hardware. From there, we worked on recompiling to SunOS
i386 and installing it on VMware. My job is creating the glue required to make
upgrading versions happen with as little downtime as possible. Moving a running
application stack from SunOS SPARC to SunOS i386 under VMware, while migrating a
half terabyte Informix database requires a lot of tools and an ability to make
things work together that were never designed to.

* Cisco
  * Nexus 5000/7000
  * Nexus 1000v
  * UCS Manager
* VMware
  * ESXi (through 5.5)
  * vSphere (through 5.5)
  * PowerCLI
* Linux
  * RedHat Kickstart
  * Cobbler
  * Puppet
  * OpenStack
  * MySQL
* Solaris administration
  * Jumpstart
  * Openboot
  * ZFS
* Oracle RDBMS
* Informix Online Server

### 02/2011 - 10/2012 / *Cisco Systems, Inc.* / DevOps, Femtocell

I was recruited out of DNCS Platform to help automate the development
infrastructure for the Femtocell project. This involved installation and
management of the continuous integration environment and converting the builds
from ant and custom "build.sh" scripts into Maven, with full artifact release
integration with Artifactory. This one was a lot of fun right up until the
project was moved offshore to reduce OpEx.

* Maven
* ant
* Jenkins
* Trac
* Artifactory
* Sonatype Nexus
* Git
* Gerrit
* Sonar
* Derby
* Groovy
* Veritas VxFS

<div style="page-break-before: always;">
<div align="right">Christopher S. Cosby</div>
</div>

<br/>

### 03/2005 - 02/2011 / *Scientific-Atlanta, a Cisco Company* / Software Engineer, DNCS Platform

See 2012-10 - Current section above. Same job, just split around a brief foray
into the world of cell phone micro-towers.

### 07/2000 - 03/2005 / *Scientific-Atlanta, Inc.* / Network Engineer, SciCare Software Services

This position started as a "Level 3" support engineer. Duties were initially
limited to resolving problems with our application stack running on Solaris.
They very soon included maintaining site-to-site VPN connectivity to customer
locations, creating a website to provide security for the VPN connections, and
other development duties. It went on to be a small application development
group, doing a great deal of PHP websites that we used to bring profit to a
pure cost center.

* PHP
* Cisco IOS

### 06/1999 - 07/2000 / *West Building Materials* / Developer, IT Specialist

West Building Materials was a 100 year old building materials store that
didn't survive the market incursion by Home Depot and Lowe's. My
responsibilities here were centered around rollout of a new point of sale
system to 30+ store locations in the US southeast. I also wrote many of the
custom reports and applications (Progress 4GL again) that replaced the
outgoing POS system. This job also kickstarted my desire to automate
everything. Executing the rollout of the stores was started by another
employee who didn't take the time to make all of the servers an easily
maintainable homogenous environment ??? every one was a little different. I
fixed that with a couple of carefully crafted backup tapes and good old
Lone-Tar.

* SCO UnixWare 7
* WAN concepts and hardware (T1, CSU/DSU, Frame Relay)
* Token Ring Networking
* IBM OS/400 and AS/400

### 05/1996 - 05/1999 / *Health Data, Inc.* / Lead Developer

Health Data is where I cut my technical teeth. This was a data-entry job that
turned into a software engineering role and escalated from there. I started
with maintaining and improving an aging data entry application (Progress 4GL),
while learning the language. From there I moved into developing drug use
review software and eventually a DICOM and HL7 compliant medical imaging
application suite. My small team of 2 developers built applications in
Progress 4GL and Visual Basic to provide a workstation to scan X-ray films,
receive a feed from the CT, MRI, and ultrasound machines and display them in a
Windows application that was located both inside the hospital and at the home
of the radiologist on call. I also rebuilt and managed the building LAN, built
and maintained all of the Windows workstations, the SCO OpenServer 5 Progress
database servers, and the Linux mail/web/DNS gateway.

* Progress 4GL
* Visual Basic
* Database Normalization/Optimization
* EIA-568 Wiring Standards
* DICOM
* HL7
* Wavelet Transforms
* SCO OpenServer 5
* Linux (Slackware, RedHat, Debian)
* Basics of IP Networking

## 1099 History
### 06/1999 - Current / *Krengel Technology*

I had the excellent fortune while at West Building Materials to meet an
enterprising young consultant who would help shape my career. Quentin Krengel
helped me develop a real passion for digging deeply into a problem and
creating a solution. Since that meeting, I have consulted on many
projects with him and his company.

* Built websites on hosted hardware before The Cloud was new.
* Migrated those websites to AWS EC2 after The Cloud came to be.
* Helped a customer get their indoor air quality monitoring device off the
  ground. Learned a lot about uCLinux&trade; and embedded devices. Wrote some
  PHP and Lua and a tiny web templating engine in awk.
* Many more small projects, and hopefully many more to come.

## Official Education
### Auburn University -- BSBA, Management Information Systems (1999)