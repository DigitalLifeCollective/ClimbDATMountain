# ClimbDATMountain
Official repository for tools created for the Climb DAT Mountain project

The objective of this project is to identify advantages of decentralized web technologies for online and offline education.
We also want to be open about the limitations of current technologies (for example, IP addresses can be disclosed if you are not using an anonymizer service), so that educators can determine whether these technologies fit with their organization's threat model.  This project will have dependencies on future versions of the DAT protocol and Beaker Browser, so it will evolve as new features such as DAT Mounts, Identity, and Multiwriter are released.

The current model is expected to include the following features:
* Instructor creates webpages for class using components developed in Polymer lit-element.
* Instructor creates worksheets for students as pages within the class.
* Instructor creates data files that describe linkages among webpages and externalize any data used by the pages.
* Instructor controls which webpages are made available to the class based on the class schedule.  Nice to have: webpages are made available based on individual student mastery.
* All versions of the webpages developed by the instructor are automatically archived and accessible using Beaker Browser.
* DAT Identity will provide a way for the Instructor and Students to authenticate to a class without logging in - it will be based on a personal webpage they create and select.  The class will further authorize students for specific functions based on the public key of their personal webpage.
* Students will register for a class and will be able to decide what profile information they want to share with the class.
* Students will use Beaker to make an editable copy of the class for offline use.  Certain pages of the class will be designated as worksheets where the instructor will provide instructions on how to edit them to complete assignments.
* Students will create new Beaker websites to be used for information they wish to share with their instructor and other students.  An introductory self-paced class on how to install and use the Beaker browser will be made available.
* Students who need help may request a mentor from their instructor.  The instructor may either informally assign a student who has mastered a topic to work with the student needing help, or arrange a formal mentorship in which the student will contract to meet with a mentor at a specific time to discuss a specific topic, and both parties are responsible for keeping that commitment and notifying each other in a reasonable time period if they are unable to do so.

Another objective is to identify use cases that can support multiple learning styles and learning paths.  Experiments will be conducted of various mentoring protocols and pay-it-forward models of mentoring.  Eventually mentorships may result in new learning paths that we hope to be able to integrate into classes via a pull-request model.

The current prototype attempts to demonstrate features of an online class which enable an instructor to publish web pages within a framework based on Polymer (a client-side framework similar to Node.js).  There is a desire to implement concepts described by Ted Nelson in order to use EDL's (edit-decision lists) in the construction of the pages and navigation links, preserving links and transclusions (material cited from original sources).  Future DAT encryption technologies (such as the Noise framework) may also provide a means to enable TransCopyright, where users can make micropayments for content they want to license.

To see the current prototype, visit the following URL in Beaker Browser:

dat://erangell-climb-dat-mountain-prototype.hashbase.io/

Note that Beaker Browser currently has issues which may cause it to hang.  The developers are aware of the issues and are working on a solution.

This project is being managed by the Digital Life collective (https://diglife.coop) using an Agile methodology with the Taiga tool for Agile work item tracking and planning.
