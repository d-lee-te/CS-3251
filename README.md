# CS 3251 - Computer Networking I (Spring 2023)
I took CS 3251 in Spring of 2023.

Lectured by Jun "Jim" Xu.

## About
[Official course listing page](https://oscar.gatech.edu/bprod/bwckctlg.p_disp_course_detail?cat_term_in=202202&subj_code_in=CS&crse_numb_in=3251).

This class was taught with Python and tested using a provided Ubuntu environment on a VM (VirtualBox).
### Course Curriculum
- Learn how the internet works
- Learn about protocols such as
    - TCP (Transmission Control Protocol)
    - IP (Internet Protocol)
    - BGP (Border Gateway Protocol)
    - OSPF (Open Shortest Path First)
    - RIP (Routing Information Protocol) and more
- Learn about fundamental concepts related to computer networking
- With an emphasis on first understanding the fundamentals and second, looking at the Internet as a "successful case study"
### Projects
1. Python Chatroom
    - Create a server program based on a specific port
      - Accept or reject clients into the chatroom
      - Parse, process, and echo all text messages across all clients on server
    - Create a client program able to join this server
      - Requires display name and passcode
2. P2P (peer-to-peer) File Transfer System
      - P2PTracker
        - Tracks clients and possible missing files
        - Routes missing files from client to client
      - P2PClient
        - Tracks local files
        - Computes hashes of local file and updates tracker
        - Requests missing files from Tracker
        - Connects to other clients w/o disconnecting from tracker

### Debrief
I got to make a chatroom. Need I say more?

Testing was a bit tedious, but the programming projects for this class perfectly lined up with what I had wanted to make at the time.



# Disclaimer
As most of the course content belongs to either the College or the Professors, I am transcribing my work and assignments to record the course.

As such, many assignments and files **may not include detailed descriptions or solutions**. This is done to avoid violations, avoid doxing myself and others, and any number of other reasons. If, for any reason, the full repo must be accessed, all assignments, descriptions, solutions, and class files are stored in a private version of the repo (so contact me. If you're a current student, don't bother since I won't give you access and it wouldn't help you anyway xp).

If possible, portions of the class will be linked to a separate readme explaining more about the linked assignment/solution/description/other.

If there exist any honor code violations or any problems/solutions are *too* in-depth, please contact me. The intention of each public class repo is to record my experience and assignments of each class taken.
