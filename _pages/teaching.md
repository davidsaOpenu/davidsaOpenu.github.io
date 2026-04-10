---
layout: page
permalink: /teaching/
title: OSW-2026b 
description: Operating systems workshop 2026b
nav: true 
nav_order: 6
---

## Registration Process

To register for the workshop, the following prerequisites must be fulfilled by the beginning of the spring semester:

- Successfully completed the [**Operating Systems**](https://www.openu.ac.il/courses/20594.htm) course.
- Accumulated at least **36 credit points** in [**Computer Science**](https://www3.openu.ac.il/ouweb/owa/catalog_eng.sksub_list?v_kod_nose=4720).
- Completed [**English proficiency requirements**](https://academic.openu.ac.il/english/pages/requirements.aspx) and [**Bibliographic Guidance**](https://www.openu.ac.il/library/services/pages/bibliographic_guidance.aspx).

### Registration Steps

<details>
<summary><b>Step 1: Fulfill Registration Prerequisites</b></summary>

Complete all required prerequisite tasks before moving to the next step.
</details>

<details>
<summary><b>Step 2: Schedule a 30-min "Meeting Expectations" Talk with Instructor</b></summary>

Contact the course instructor to arrange a time for the required orientation meeting.
</details>

<details>
<summary><b>Step 3: Register for the Course</b></summary>

Complete the official registration process through the registration system.
</details>

<details>
<summary><b>Step 4: Send Notification Email to the Instructor</b></summary>

Send a confirmation email to the course instructor after completing registration.
</details>

**Note**: If you are currently enrolled in the Operating Systems course during the autumn semester, you must take the first exam (Moed Aleph) and meet all requirements before the spring semester begins.

---

## Course Timeframes

### Spring Semester

The course will consist of **7 Zoom meetings** throughout the semester. The activities during the semester include:
- Learning the required material for project preparation.
- Completing **2 project-related assignments**, each requiring approximately **8–16 hours of work**.
- Delivering a **50-minute presentation** related to the selected project requiring approximately **8 hours of work**.
- Preparing a project specification and dividing the project into **7–8 implementation stages** requiring approximately **24 hours of work**

### Summer Semester

The activities during the summer semester include:
- Participating in a **30-minute weekly synchronization meeting** with other students via Google Meet.
- Progressing through the project stages according to the plan, with each stage taking approximately **16–20 hours of work**.

---

## Course Objectives

- **Significant Contribution to Open Source Projects**
  - Contribute to one of the open-source projects listed in **Tab1**.
  - Aim for:
    - 112-192 work hours (assignments, prsentatoin, project specifcation and implemntation)

- **Presentation Skills**


- **Agile Workflow & Collaboration**
  - Break work into **small, manageable tasks**.
  - Use a **project management board**.
  - Perform pair **code reviews (CRs)**.
  - **Interpret logs** from the **continuous integration (CI)** system.

---
## Important Due Dates
- **Maman 11** – due by **22 May 2026** - 3%
- **Maman 12** – due by **19 June 2026** - 7%
- **Maman 13** - Project Presentation – to be scheduled **between 1 May and 19 June 2026** - 6%
- **Maman 14** - Project Specification – due by **15 July 2026** - 20%
- **Maman 15** - Final Project Implementation – due by **30 September 2026** - 64%

Note:
- Due date does not include weekends and holidays; i.e., 22 May 2026 is Friday, therefore submitting before 23:59 on 23 May 2026 Saturday implies no penalty.
- Missing due date for an unjustified reason implies -2 points per week. For example, submitting anytime between 00:00 on 24 May 2026 and 23:59 on 30 May 2026 implies a -2 points reduction.     

Amendment: Due to holidays in September 2026, we are extending the grace period to the end of October 30. During October, we will keep sync meetings; they will stop afterwards. It is absolutely critical to have Maman 14 graded by 9 October 2026. Without a passing mark on Maman 14, it makes no sense to continue working on Maman 15. I will review the code, but without an agreed project spec and without sync meetings, the chances to create something meaningful are low. Besides, the deduction policy will be applied, and every week will cost -2 points.

### Clarification Regarding the Tasks During the Semester

#### First and Second Assignments (Maman 11/12)

- Assignments (Maman 11/12) are published on the Trello board.
- Each student should choose an epic from the **eVSSIM**, or **Swift** boards and identify which assignments are related to that epic.
- Each student should assign themselves to an epic (no more than **2 students per epic**) and also to the Trello cards related to the epic.
- Assignments labeled *"can be done in pairs"* may be completed in pairs as indicated. All other assignments are **individual**.

#### Student Talks (Maman 13)

- Each student is expected to assign themselves to the Trello card related to a **student talk topic** associated with the chosen epic.
- Each epic includes a link to a Trello card describing the **mandatory student talk**.
- **Google Slides** (in English) should be shared with the instructor **at least one week before a scheduled talk** for comments and feedback.
- Reuse and improvement of existing slides (attached to the corresponding Trello card) is encouraged.


#### Fourth Assignment (Maman 14)

- Maman 14 **can be done in pairs**.
- Each student (or pair) is expected to:
  - Create a **Trello card** and link it from the assignments checklist in the appropriate epic Trello card.
  - Assign themselves to the card.
  - Create a **Google Doc** containing the project specification, following the format described in *"HOWTO Submit a Project Spec"*.

- Each epic includes a checklist of implementation steps. The student’s mission in Maman 13 is to:
  - Translate the checklist into a **well-documented**:
    - Functional specification
    - Implementation plan
    - Testing specification
  - Create **7 to 8 Trello cards** (stories), each representing about 1-2 weeks of effort (approximately 16–24 hours of focused work).
    - Each card must include a **Definition of Done (DoD)** that clearly describes:
        - Features implemented at this stage
        - Corresponding tests for the implemented code
- Toward the end of the semester, after work on Maman 13 begins, **30-minute weekly sync meetings** for the **eVSSIM**, and **Swift** tracks will be scheduled.


#### Assignment (maman 11/12) / Story Submissions & CI

- Gerrit change requests must **pass CI regression checks**.
- Each student (or pair) is responsible for obtaining **peer reviews** from **at least two reviewers from their track** (eVSSIM, or Swift) by requesting reviews via the appropriate WhatsApp group.
- **Instructors will assess the quality of the peer reviews**.
  - Review quality will impact the **reviewer’s own assignment grade**.
- After a Gerrit change is merged, a **text file** containing 
  - links to the Gerrit change
  - to the Gerrit change review performed for another Maman/Story
  - First and last names of 2 peers performed peer reviews for the submitted assignment.
should be submitted via the university's **electronic submission system**.

Detailed description on Code Reviews including scoreing that impacts the Maman/Story grade is avialabe [here](https://docs.google.com/document/d/1SGfbdBjPmZa9fKiH9QKYfxB6MXNwQPDtbs_k52ztMUk/edit?usp=sharing)

#### Talk submission

Submit via electronic submission system a text file that contains a link to the presentation. See the doc at the beginning of your epic's description that specifies how a talk should be organized and what influences the grade. Note that presentations are subject to instructor approval, and it takes at least one week to finish the review cycles. Plan your time accordingly.

#### Project Spec Submission 

Submit via electronic submission system a text file that contains a link to the Google Doc with the spec. See the doc at the beginning of your epic's description that specifies how a project spec should look. Note that the project spec is subject to instructor approval, and it takes at least one week to finish the review cycles. Plan your time accordingly.

### Clarification Regarding the Tasks During the Summer Semester

#### Final Assignment (Maman 15)

- Maman 15 **can be done in pairs**.
- Each student (or pair) is expected to:
  - Implement stories according to the specification and plan created during Maman 14.
  - Participate in **30-minute weekly sync meetings**. During these meetings, each student will:
    - Briefly present the progress made on their current story  
    - Share the plan for the upcoming week  
    - Raise any flags, unresolved issues, or questions requiring broader input
- Students are encouraged **not to wait** for the meetings to raise issues. They should use the appropriate WhatsApp groups (general or track-specific for eVSSIM, or Swift) to share problems or concerns as early as possible. The same applies to concerns about the **merge order of change requests**.
- **Assignment Submissions & CI** rules apply to every story.
- After all 7 to 8 Gerrit change requests related to the stories are merged, a **text file** containing links to the Gerrit changes should be submitted via the university’s **electronic submission system**.






---

## Projects


| Project   | Description | HW/SW Requirements | Skills | Resources |
|-----------|-------------|---------------------|-----------|-----------|
| **eVSSIM** | SSD simulator based on QEMU/KVM, exposing NVMe protocol to guest OS. Used to evaluate SSD performance under various firmware designs. | 4–64 GB RAM<br><br> 150 GB disk<br><br> Cosmos OpenSSD Platform (for one epic)<br><br>Ubuntu 24.04 (bare-metal) | C (high)<br><br> C++ (basic)<br><br> Python (basic) | <br><br> [VSSIM article](https://oslab.kaist.ac.kr/wp-content/uploads/esos_files/publication/conferences/international/VSSIM_Yoo_MSST_2013.pdf)<br><br> [eVSSIM architecture](https://docs.google.com/document/d/1VFnmmh0g-RThOu-YD6GB5WaUsFgF3pS1poOxfimpdtE/edit?usp=sharing)<br><br> [Project management board](https://trello.com/b/eMxey6Rr/evssim)<br><br> [Analytical modelling article](https://oslab.kaist.ac.kr/wp-content/uploads/esos_files/publication/conferences/international/VSSIM_IOSimulator.pdf)<br><br> [NVMe spec](https://nvmexpress.org/specification/nvm-express-base-specification/) |
| **Swift** | OpenStack Object Store for scalable unstructured data storage and retrieval via a simple API. Designed for high availability and concurrency. |  4–64 GB RAM<br><br> 150 GB disk<br><br> Ubuntu 24.04 (bare-metal) |  Python (high) <br><br> Testing frameworks<br><br> Design patterns| [OpenStack Swift book](https://homepages.dcc.ufmg.br/~guimaluf/OpenStack%20Swift.pdf)<br><br> [Project management board](https://trello.com/b/BNO7afbX/swift)<br><br> [Swit - PPT](https://object-storage-ca-ymq-1.vexxhost.net/swift/v1/6e4619c416ff4bd19e1c087f27a43eea/www-assets-prod/presentation-media/Intel-OpenStack-Summit-Session-Nov13-Final.pptx)<br><br> [Implementing cloud storage with Openstack Swift - wiki](https://wiki.openstack.org/wiki/Swift) |

---

## Meetings {#meetings}

| Date | Track | Presenter | Agenda  | Materials |
| :---- | :---- | :----------------- | :---- | :---- |
| 10/04  |    |    |  |   |
| |  all  |  David S  | OSW Intro <br><br> Project demos, epics <br><br>**Bottom line**<br>During the next two weeks, read the materials covered today and assign yourself to one of the tracks (**eVSSIM**, or **Swift**).  | [slides](https://docs.google.com/presentation/d/1DVeQqusbW9-aeaO2kOeI0BXuaFloUJt0I9gsgdJPdA4/edit?slide=id.p1#slide=id.p1)  |
| 19/04  |    |    |  |   |
| |  eVSSIM  |  Michael Somekh, Amit Pur  | Linux VFS Evolution: 5.0.0 → 7.0.2 Case Study Using ramfs | [slides](https://docs.google.com/presentation/d/1xCAOuidF4_mH05gb-Lio5wN62X-gacR4ctEMuBZ4GFs/edit?usp=sharing)  |
| |  eVSSIM  |Yuri Khordal, Aviv Barak Etedgui | | |



---
## Linux kernel bucket

| \# | Date/Time/Duration | Track/Presenter | Agenda  | presentation |
| :---- | :---- | :---- | :---- | :---- |
| 3 | \[TBD\] 60m | \[kernel\]/\[First and last Name\] | Linux kernel (based on R. Loves’ book): Interrupts and Interrupt Handlers  Bottom Halves | [Slides](https://www.dropbox.com/s/bayps17o020djra/OSW-ppts.zip?dl=0) |
| 5 | \[TBD\] 40m | \[kernel\]/\[First and last Name\] | Linux kernel (based on R. Loves’ book): Block I/O layer | [Slides](https://www.dropbox.com/s/bayps17o020djra/OSW-ppts.zip?dl=0) |
| 6 | \[TBD\] 40m | \[kernel\]/\[First and last Name\] | Linux kernel (based on R. Loves’ book): VFS | [Slides](https://www.dropbox.com/s/bayps17o020djra/OSW-ppts.zip?dl=0) |
| 7 | \[TBD\] 40m  | \[kernel\]/\[First and last Name\] | Linux kernel (based on R. Loves’ book): The Page Cache and Page Writeback | [Slides](https://www.dropbox.com/s/bayps17o020djra/OSW-ppts.zip?dl=0) |
| 8 | \[TBD\] 40m\]  |  \[kernel\]/\[First and last Name\] | Blk-mq and nvme-core.c [Article](https://kernel.dk/blk-mq.pdf) [slides](https://kernel-recipes.org/en/2015/talks/solving-the-linux-storage-scalability-bottlenecks/) |  |

---
## eVSSIM bucket 
see TALKS column on the Trello board 

---
## Swift bucket
see TALKS column on the Trello board

---
## Resources

**Linux containers**

* [https://www.nccgroup.com/media/eoxggcfy/\_ncc\_group\_understanding\_hardening\_linux\_containers-1-1.pdf](https://www.nccgroup.com/media/eoxggcfy/_ncc_group_understanding_hardening_linux_containers-1-1.pdf)  
* [https://github.com/lxc/lxc](https://github.com/lxc/lxc)  
* [https://linuxcontainers.org/lxc/getting-started/](https://linuxcontainers.org/lxc/getting-started/)  
* [https://en.wikipedia.org/wiki/LXC](https://en.wikipedia.org/wiki/LXC)  
* [https://www.ibm.com/developerworks/linux/library/l-lxc-containers/](https://www.ibm.com/developerworks/linux/library/l-lxc-containers/)  
* [https://wiki.deimos.fr/LXC\_:\_Install\_and\_configure\_the\_Linux\_;Containers](https://wiki.deimos.fr/LXC_:_Install_and_configure_the_Linux_Containers)

**Docker**

* [Docker containers \- building and running](https://www.materialscloud.org/learn/data/learn/files/RpDQa7DO1CkL/1-3_Innocente_docker-intro_REVISED.pdf%20% 9)   
* [https://www.simplilearn.com/tutorials/docker-tutorial/what-is-dockerfile](https://www.simplilearn.com/tutorials/docker-tutorial/what-is-dockerfile)

**Linux kernel namespaces and cgroups**

* [https://blog.lizzie.io/linux-containers-in-500-loc.html](https://blog.lizzie.io/linux-containers-in-500-loc.html)   
* [http://www.haifux.org/lectures/299/netLec7.pdf](http://www.haifux.org/lectures/299/netLec7.pdf)   
  * audio track [http://www.haifux.org/lectures/299/](http://www.haifux.org/lectures/299/)  
* [http://www.haifux.org/lectures/320/netLec8\_final.pdf](http://www.haifux.org/lectures/320/netLec8_final.pdf)  
* [http://man7.org/conf/](http://man7.org/conf/) \- Conference presenttaions  
* [http://man7.org/training/index.html](http://man7.org/training/index.html) \- trainings (not only about the $subject)  
* [https://man7.org/conf/ndctechtown2019/Linux-namespaces-NDC-TechTown-2019-Kerrisk.pdf](https://man7.org/conf/ndctechtown2019/Linux-namespaces-NDC-TechTown-2019-Kerrisk.pdf) \- a good namespaces presentation  
* [Managing Linux Resources with cgroups](https://share.confex.com/share/125/webprogram/Handout/Session17308/Managing%20Resources%20with%20cgroups.pdf) \- a good cgroups presentation

**History of conteiner technology**

* [https://www.slideshare.net/insideHPC/linux-container-technology-101](https://www.slideshare.net/insideHPC/linux-container-technology-101) \- history and 101  
* [https://dzone.com/articles/evolution-of-linux-containers-future](https://dzone.com/articles/evolution-of-linux-containers-future)  
* [https://blog.aquasec.com/a-brief-history-of-containers-from-1970s-chroot-to-docker-2016](https://blog.aquasec.com/a-brief-history-of-containers-from-1970s-chroot-to-docker-2016)  
* [http://www.cs.ucr.edu/\~nael/cs202/containers.pdf](http://www.cs.ucr.edu/~nael/cs202/containers.pdf) \- article on process containers (a milestone)  
* [https://lwn.net/Articles/531114/](https://lwn.net/Articles/531114/) \- lwn article (a milestone)  
* [http://linuxbsdos.com/2015/10/01/whats-a-type-c-hypervisor/](http://linuxbsdos.com/2015/10/01/whats-a-type-c-hypervisor/)


**Linux**

* [https://github.com/torvalds/linux/](https://github.com/torvalds/linux/)  
* [https://elixir.bootlin.com/linux/v4.16.10/source](https://elixir.bootlin.com/linux/v4.16.10/source)  
* [https://www.kernel.org/doc/htmldocs/kernel-api/](https://www.kernel.org/doc/htmldocs/kernel-api/)  
* [https://lwn.net/Articles/719732](https://lwn.net/Articles/719732/) \- struct layout randomization plugin

**Ptrace and debugging**

* Ptrace Part 1 \- [https://www.linuxjournal.com/article/6100?page=0,1](https://www.linuxjournal.com/article/6100?page=0,1)  
* Ptrace Part 2 \- [https://www.linuxjournal.com/article/6210](https://www.linuxjournal.com/article/6210)  
  * Code \[ftp.linuxjournal.com/pub/lj/listings/issue104/6210.tgz\].  
* Debuggers (part1-3): [https://eli.thegreenplace.net/tag/debuggers](https://eli.thegreenplace.net/tag/debuggers)

**Meetups**

* [Meetup: Open meets Opensource](https://sites.google.com/site/openuopensource/home/meetup-2016-dec-18)


**OpenStack**

* OpenStack Cloud storage \- [SNIA \- Bright Talk](https://www.snia.org/sites/default/files/OpenStack_Cloud_Storage__BrightTalk_FInal.pdf)  (cinder, manila, swift)  
* [OpenStack deployment with netapp technologies](http://netapp.github.io/openstack-deploy-ops-guide/liberty/openstack-deployment-ops-guide.pdf)  
* [OpenStack 10 \- Architecture guide and Object Storage (swift)](https://docs.redhat.com/en/documentation/red_hat_openstack_platform/10/html-single/architecture_guide/index#comp-swift)  
* [OpenStack 16 \- Partner integration](https://docs.redhat.com/en/documentation/red_hat_openstack_platform/16.0/html/partner_integration/index)  
* [OpenStack services on Openshift \- 18.0](https://docs.redhat.com/en/documentation/red_hat_openstack_services_on_openshift/18.0)  
* [Manila presentation](https://www.snia.org/sites/default/files/RobertCallaway_OpenStack_Manilla.pdf)  
* [TripleO \- deploying openstack with tripleo](https://www.slideserve.com/freya/deploying-openstack-with-tripleo)  
* [TripleO \- Openstack on Openstack](https://www.slideshare.net/kiranmurari/tripleo)  
* [TripleO OpenStack Summit Boston 2017](https://www.openstack.org/assets/presentation-media/TripleO-OpenStack-Summit-Boston-2017.pdf)

**Simulators**

* [Copycat: A High Precision Real time NAND Simulator](https://arxiv.org/pdf/1612.04277.pdf)

**NVMe**

* [SNIA NVMe over Fabrics](https://www.youtube.com/watch?v=HfcZwkPzj4w) on youtube

**Storage**

* [SNIA Storage Virtualization](https://www.snia.org/sites/default/files/sniavirt.pdf#pagemode=bookmarks&page=6) \- pdf  
  



<script>
document.addEventListener("DOMContentLoaded", function () {
  if (window.location.hash) {
    const id = window.location.hash.substring(1);
    const el = document.getElementById(id);
    if (el) {
      el.scrollIntoView({ behavior: "smooth" });
    }
  }
});
</script>
