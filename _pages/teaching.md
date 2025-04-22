---
layout: page
permalink: /teaching/
title: courses 
description: 2025 b
nav: true 
nav_order: 6
---

# OSW Course Description

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

- **Maman 11** – due by **6 May 2025**
- **Maman 12** – due by **29 May 2025**
- **Project Presentation** – to be scheduled **between 6 May and 29 June 2025**
- **Maman 13** (Project Specification) – due by **29 June 2025**
- **Maman 14** (Final Project Implementation) – due by **30 September 2025**


### Clarification Regarding the Tasks During the Semester

#### First and Second Assignments (Maman 11/12)

- Assignments (Maman 11/12) are published on the Trello board.
- Each student should choose an epic from the **eVSSIM**, **Swift**, or **xv6** boards and identify which assignments are related to that epic.
- Each student should assign themselves to an epic (no more than **2 students per epic**) and also to the Trello cards related to the epic.
- Assignments labeled *"can be done in pairs"* may be completed in pairs as indicated. All other assignments are **individual**.

#### Third Assignment (Maman 13)

- Maman 13 **can be done in pairs**.
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
- Toward the end of the semester, after work on Maman 13 begins, **30-minute weekly sync meetings** for the **eVSSIM**, **Swift**, and **xv6** tracks will be scheduled.


#### Student Talks

- Each student is expected to assign themselves to the Trello card related to a **student talk topic** associated with the chosen epic.
- Each epic includes a link to a Trello card describing the **mandatory student talk**.
- **Google Slides** (in English) should be shared with the instructor **at least one week before a scheduled talk** for comments and feedback.
- Reuse and improvement of existing slides (attached to the corresponding Trello card) is encouraged.

#### Assignment Submissions & CI

- Gerrit change requests must **pass CI regression checks**.
- Each student (or pair) is responsible for obtaining **peer reviews** from **at least two reviewers from their track** (eVSSIM, Swift, or xv6) by requesting reviews via the appropriate WhatsApp group.
- **Instructors will assess the quality of the peer reviews**.
  - Review quality will impact the **reviewer’s own assignment grade**.
- After a Gerrit change is merged, a **text file** containing a link to the Gerrit change should be submitted via the university’s **electronic submission system**.


### Clarification Regarding the Tasks During the Summer Semester

#### Final Assignment (Maman 14)

- Maman 14 **can be done in pairs**.
- Each student (or pair) is expected to:
  - Implement stories according to the specification and plan created during Maman 13.
  - Participate in **30-minute weekly sync meetings**. During these meetings, each student will:
    - Briefly present the progress made on their current story  
    - Share the plan for the upcoming week  
    - Raise any flags, unresolved issues, or questions requiring broader input
- Students are encouraged **not to wait** for the meetings to raise issues. They should use the appropriate WhatsApp groups (general or track-specific for eVSSIM, Swift, or xv6) to share problems or concerns as early as possible. The same applies to concerns about the **merge order of change requests**.
- **Assignment Submissions & CI** rules apply to every story.
- After all 7 to 8 Gerrit change requests related to the stories are merged, a **text file** containing links to the Gerrit changes should be submitted via the university’s **electronic submission system**.






---

## Projects


| Project   | Description | HW/SW Requirements | Skills | Resources |
|-----------|-------------|---------------------|-----------|-----------|
| **eVSSIM** | SSD simulator based on QEMU/KVM, exposing NVMe protocol to guest OS. Used to evaluate SSD performance under various firmware designs. | 4–64 GB RAM<br><br> 150 GB disk<br><br> Cosmos OpenSSD Platform (for one epic)<br><br>Ubuntu 24.04 (bare-metal) | C (high)<br><br> C++ (basic)<br><br> Python (basic) | <br><br> [VSSIM article](https://oslab.kaist.ac.kr/wp-content/uploads/esos_files/publication/conferences/international/VSSIM_Yoo_MSST_2013.pdf)<br><br> [eVSSIM architecture](https://docs.google.com/document/d/1VFnmmh0g-RThOu-YD6GB5WaUsFgF3pS1poOxfimpdtE/edit?usp=sharing)<br><br> [Project management board](https://trello.com/b/eMxey6Rr/evssim)<br><br> [Analytical modelling article](https://oslab.kaist.ac.kr/wp-content/uploads/esos_files/publication/conferences/international/VSSIM_IOSimulator.pdf)<br><br> [NVMe spec](https://nvmexpress.org/specification/nvm-express-base-specification/) |
| **xv6** | Reimplementation of Sixth Edition Unix in ANSI C for x86 multiprocessor systems. Used in MIT's 6.828 Operating Systems course. | 4 GB RAM<br><br> 150 GB disk<br><br> Ubuntu 24.04 (bare-metal) |  C (high) | [Project management board](https://trello.com/b/whs0LS9B/xv6)<br><br> [Objfs spec](https://docs.google.com/document/d/1p8GKxLI8MVo4ND0PoggGx9n4QA1sabaNfr0jAo0FOGs/edit#heading=h.renznclxfaio)<br><br> [XV6 containers, namespaces, cgroups](https://docs.google.com/document/d/1iLGOXVAlkl9Ee2VLVfnYWHt4efNy5_NapldoVtK4Nzo/edit#heading=h.qlemqf813ps)<br><br> [Wiki](https://en.wikipedia.org/wiki/Xv6)<br><br> [xv6 book](https://pdos.csail.mit.edu/6.828/2014/xv6/book-rev8.pdf) |
| **Swift** | OpenStack Object Store for scalable unstructured data storage and retrieval via a simple API. Designed for high availability and concurrency. |  4–64 GB RAM<br><br> 150 GB disk<br><br> Ubuntu 24.04 (bare-metal) |  Python (high) <br><br> Testing frameworks<br><br> Design patterns| [OpenStack Swift book](https://homepages.dcc.ufmg.br/~guimaluf/OpenStack%20Swift.pdf)<br><br> [Project management board](https://trello.com/b/BNO7afbX/swift)<br><br> [Swit - PPT](https://object-storage-ca-ymq-1.vexxhost.net/swift/v1/6e4619c416ff4bd19e1c087f27a43eea/www-assets-prod/presentation-media/Intel-OpenStack-Summit-Session-Nov13-Final.pptx)<br><br> [Implementing cloud storage with Openstack Swift - wiki](https://wiki.openstack.org/wiki/Swift) |

---

## Meetings {#meetings}

| Date | Track | Presenter | Agenda  | Materials |
| :---- | :---- | :----------------- | :---- | :---- |
|  21/03 |  all  |  David S  | OSW Intro <br><br> Project demos, epics <br><br>**Bottom line**<br>During the next two weeks, read the materials covered today and assign yourself to one of the tracks (**eVSSIM**, **xv6**, or **Swift**) in Table #2.  | [slides](https://docs.google.com/presentation/d/1DVeQqusbW9-aeaO2kOeI0BXuaFloUJt0I9gsgdJPdA4/edit?slide=id.p1#slide=id.p1)  |
| 28/03  |    |    |  |   |
|  |  all  |  David S  | Epics (cont)   | [slides](https://docs.google.com/presentation/d/1DVeQqusbW9-aeaO2kOeI0BXuaFloUJt0I9gsgdJPdA4/edit?slide=id.g3267fe28fd1_0_0#slide=id.g3267fe28fd1_0_0)  |
|   |  eVSSIM  |  David S  | [NVME hands-on Lab](https://drive.google.com/file/d/0BxXKX8L4jdxTNzRLbVFWSzBwVWc/view?usp=sharing&resourcekey=0-apFWsUQejoBm5RlhcmUbCg) <br><br> [NVM express tutorial](https://www.flashmemorysummit.com/English/Collaterals/Proceedings/2013/20130812_PreConfD_Marks.pdf) <br><br> [Spec v1.3](https://nvmexpress.org/wp-content/uploads/NVM_Express_Revision_1.3.pdf) <br><br> [SSD performance](https://www.snia.org/sites/default/files/SNIASSSI.SSDPerformance-APrimer2013.pdf)  |   |
| 25/04  |  swift  |  David S  |  [Ansible](https://docs.redhat.com/en/documentation/red_hat_ansible_automation_platform/2.5/html/getting_started_with_playbooks/index)  |  |
|  |  swift  |  David S  |  Implementing Cloud Storage with OpenStack Swift - Chapter 1 - Cloud storage |  |
| 09/05  |  swift  |  David S  | Implementing Cloud Storage with OpenStack Swift - Chapter 2 - Swift architecture  |  |
|  |  swift  |  David S  | Implementing Cloud Storage with OpenStack Swift - Chapter 3 - Installing OpenStack Swift |  |
|  |  swift   |  David S  | Implementing Cloud Storage with OpenStack Swift - Chapter 4 - Using Swift  |  |
|  |  eVSSIM xv6  |  David S  | Linux kernel (based on R. Loves’ book): VFS <br> |  |
| 23/05  |  |  |  |  |
|  |  eVSSIM  | Alon A | FTL |  [slides](https://docs.google.com/presentation/d/1my5_bbWgFhnnlloTa5Pxkai4OSxgarVBsQhbhT6j2uI/edit?usp=sharing) |
|  |  eVSSIM  | Adam Z | exofs architecture | [slides](https://docs.google.com/presentation/d/1YUrBsL8GRwxbBPeSmUCVjxNU2_5Gaep4/edit?usp=sharing&ouid=114210043453285298284&rtpof=true&sd=true) |
|  |  xv6  | Michael K | container images | [slides](https://docs.google.com/presentation/d/1hrMXuFsIkfQDgCxA2O4ZCVTSRhQZNtnsPEndLp9HQAI/edit?usp=sharing) |
|  | all | David S | Interrupts and Interrupt handlers, Linux kernel (by R. Love)  | [slides](https://docs.google.com/presentation/d/1XO-YfB2qImLTjXIruGpXVJXeDrkmOgQ_/edit?usp=sharing&ouid=114210043453285298284&rtpof=true&sd=true) |
|  | all | David S | Bottom Halves and Defering Work, Linux kernel (by R. Love)  | [slides](https://docs.google.com/presentation/d/1ow_OR9B8cCFIzLCk9ozjRBIM6C32_SIN/edit?usp=sharing&ouid=114210043453285298284&rtpof=true&sd=true) |
|  | all | David S | Block I/O layer, Linux kernel (by R. Love)  | [slides](https://docs.google.com/presentation/d/1sgRUyOfvxcV24kkv7FOdFyna9TTeVB_X/edit?usp=sharing&ouid=114210043453285298284&rtpof=true&sd=true) |
| 20/06  |           |              | | |
|        | eVSSIM    |  Itai S      | garbage collector | [slides](https://docs.google.com/presentation/d/15x-MLIVZo0iQqsirbAuYS1h_Zp_YvYl2/edit?usp=sharing&ouid=114210043453285298284&rtpof=true&sd=true) |
|        | eVSSIM    |  Liel H      | eVSSIM tests - host | [slides](https://docs.google.com/presentation/d/1EQKOlzzC7mUnwzzrK4AQtr9CawkTEvLX/edit?usp=sharing&ouid=114210043453285298284&rtpof=true&sd=true) |  
|        | eVSSIM    |  Rami K      | OSD setup, tracing open/read/write/close system calls in exofs | [slides](https://docs.google.com/presentation/d/190otJLGDnLUoXT7WOKrgU2spyLWO9j7KKPUGwokx6QY/edit?usp=drive_link) |
|        | xv6       |  Naty M      | cgroups v1 | [slides](https://docs.google.com/presentation/d/1YrYPcJK6PvR7NO9Dp4133ibKObfI7oT1QG6OWmqJDjc/edit?usp=sharing) |
|        | xv6       |  Maayan F / Ron S    | cgroups v2 | [slides](https://docs.google.com/presentation/d/1_5giLpeOZjmUVo2MckEboZtxMBevz7RIagI4tONb2is/edit?usp=sharing) |
| 27/06  |           |              | | |      
|        | eVSSIM    |  Emil K      | eVSSIM tests - guest | slides - TBU  |
|        | swift     |  Yarin M     | object backend | [slides](https://docs.google.com/presentation/d/12R9bxEQH2NwA12QadWNF3EYV4YxDMvuNJqIgtOtIe6E/edit?usp=sharing) |
|        | xv6       |  Tomer S     | container runtimes | [slides](https://docs.google.com/presentation/d/1OLeOfIN7t4mzVLMeX-VvZduplRxxiyWOEfFt6X7d-lw/edit?usp=sharing) |
|        | eVSSIM    |  Ido T       | ONFI 1.0 | [slides](https://docs.google.com/presentation/d/12R9bxEQH2NwA12QadWNF3EYV4YxDMvuNJqIgtOtIe6E/edit?usp=sharing) |
|        | eVSSIM    |  Leon G      | ELK | [slides](https://docs.google.com/presentation/d/1quZIyvyNDiRHfyn4jah5tmv6xPqP_Jbh4dsomWfm0lM/edit?usp=sharing) |
|        | eVSSIM    |  Yonatan G   | jsonnet | [slides](https://docs.google.com/presentation/d/1k_ouD59qONIauOsDNHCS2KjvKN6AYTUzTBQcrddYrXo/edit?pli=1) |
| 20/07<br>Sunday<br>11:00 | all | [Schlomo Schapiro](https://schlomo.schapiro.org/) | [Backup and Disaster Recovery: Business as Usual or What Needs to Change Now?](https://devopscon.io/devsecops/backup-disaster-recovery) | [Schlomo Schapiro](http://go.schapiro.org/schlomo) is an Agile IT and Open Source enthusiast dedicated to advancing an agile mindset and a [DevOps-orientated culture](https://schlomo.schapiro.org/p/5-devops-principles.html) in IT. He works as Associate Partner / Principal Engineer at [Tektit Consulting](https://tektitconsulting.com/) in Berlin, is author of several Open Source projects, conference [speaker](https://schlomo.schapiro.org/p/publications.html) and regularly publishes [blog](https://schlomo.schapiro.org/) and [magazine articles](https://schlomo.schapiro.org/p/publications.html). Schlomo focuses on IT strategy, IT governance, technology and architecture management, security and compliance automation, related organisational changes, business continuity, open source and cloud technologies - and is available as a Principal Engineer for short-term support. |
                                                                    

---

## xv6 bucket

| \# | Date/Time/Duration | Track/Presenter | Agenda  | presentation |
| :---- | :---- | :---- | :---- | :---- |
| 1 | 80m  \[TBD\]  | \[xv6\]\[TBD\] | Linux: Functional description and implementation details of docker containers   | Resources to use to build slides   [1st blogpost](https://medium.com/@nagarwal/understanding-the-docker-internals-7ccb052ce9fe) [2nd blogspot](http://docker-saigon.github.io/post/Docker-Internals/) |
| 2 | 40m  \[TBD\]  | \[xv6\]\[TBD\] | Linux: Functional description and implementation details of OCI images | Resources to use to build slides [OCI images](https://github.com/saschagrunert/demystifying-containers/blob/master/part3-container-images/post.md) [CN landscape](https://landscape.cncf.io/) |
| 3 | 40m \[TBD\]  | \[xv6\]/\[TBD\] | Ch 0 \- OS organisation Ch 1 \- Processes Ch 2 \- Page tables | [Slides](https://docs.google.com/presentation/d/1q2slhIb8ChafAfNzwg0IdRlrKENv9FJd_BYl58_MkEo/edit?usp=sharing) [Readthedocs Ch0](https://pekopeko11.sakura.ne.jp/unix_v6/xv6-book/en/Operating_system_interfaces.html) [Readthedocs Ch1](https://pekopeko11.sakura.ne.jp/unix_v6/xv6-book/en/The_first_process.html) [Readthedocs Ch2](https://pekopeko11.sakura.ne.jp/unix_v6/xv6-book/en/Page_tables.html)  |
| 4 | 40m \[TBD\]  | \[xv6\]/\[TBD\] | Ch 3 \- Traps, interrupts, drivers Ch 4 \- Locking | [Slides](https://docs.google.com/presentation/d/1xFq0PQCV0SPw3LFCoPS-iPUipJKi1Pzp8u3zl7VKras/edit?usp=sharing) [Readthedocs Ch3](https://pekopeko11.sakura.ne.jp/unix_v6/xv6-book/en/Traps_interrupts_and_drivers.html) [Readthedocs Ch4](https://pekopeko11.sakura.ne.jp/unix_v6/xv6-book/en/Locking.html) |
| 5 | 40m \[TBD\]  | \[xv6\]/\[TBD\] | Ch 5 \- Scheduling Ch 6 \- File system |  [Slides](https://docs.google.com/presentation/d/1rpoOB8jCDSq301x_6YslPbH3IO6VRqNM-azPNgQxw-8/edit?usp=sharing) [Alexander’s slides](https://drive.google.com/file/d/14QpfZ6BdJzlZlrqaGX4x-Ks-33L9x1nH/view?usp=sharing) [Readthedocs Ch5](https://pekopeko11.sakura.ne.jp/unix_v6/xv6-book/en/Scheduling.html) [Readthedocs Ch6](https://pekopeko11.sakura.ne.jp/unix_v6/xv6-book/en/File_system.html)  |
| 6 | 40m  \[TBD\]  | \[xv6\]\[TBD\] | Object Stash VFS xv6-objfs kvector | Resources to use to build slides  [Object stash](https://docs.google.com/document/d/1YpDfT85IhfVCVH0u7MsKkB6S1c9IMvFeQJ9evFIceRw/edit?usp=sharing) [VFS](https://docs.google.com/document/d/1YpDfT85IhfVCVH0u7MsKkB6S1c9IMvFeQJ9evFIceRw/edit?usp=sharing) [Khhvector](https://docs.google.com/document/d/13Ty7odfMblpOsevRumxiUyczcxpWkJXc/edit)  |
| 7 | 60m \[TBD\]  | \[xv6\]/\[TBD\] | Linux: Functional description and implementation details of  user namespace pid namespace  | [Slides](https://docs.google.com/presentation/d/1Ybh89fosohFD_hGj_1kvLchambh3aPuU7-RNxUpkKbM/edit?usp=sharing)  Live demo with code/scripts [userns](https://drive.google.com/file/d/1u8R9zipkmuRS_Knp4n_6SOY8zXox9Gst/view?usp=sharing) Pidns \- [part 4](https://lwn.net/Articles/532748/) Pidns \- [part 3](https://lwn.net/Articles/532271/) Pidns \- [part 2](https://lwn.net/Articles/531381/) Pidns \- [part 1](https://lwn.net/Articles/531114/)  |
| 8 | 60m \[TBD\]  | \[xv6\]/\[TBD\] | Linux: Functional description and implementation details of Mount ns UTS ns cgroups    | [slides](https://docs.google.com/presentation/d/1xGywNANNmMKw6-SFsXZ7xX5mVoeXAJW1cp_96EKTnDM/edit?usp=sharing)  [Slides](https://docs.google.com/presentation/d/1J2FjVi63XpMh_Obhua-Iahap5Ub570CMn-qCOgGq5Ko/edit?usp=sharing) (same \+ cgroups \+ minor enhancements \- visibility)  Live demo with code/scripts [UTS namespaces demo](https://trello.com/c/JDOQMric/29-maman-12-linux-tests-for-uts-namespace) |

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

**Xv6**

* OS interfaces \- [system call workshop](https://github.com/ranl/xv6-public/wiki)

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
