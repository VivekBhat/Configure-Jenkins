# HW #1B - Configuring Servers
#### Name: Vivek Bhat
#### Unity ID: vbhat

##Tasks
- 30% Ansible scripts for configuring jenkins.
- 30% Meeting constraints
- 20% Concepts
- 20% Screencast and following instructions

##Task 1 & 2: Ansible Playbook

PlayBook for configuring jenkins :

* [site.yml](http://github.ncsu.edu/vbhat/hw1-b/site.yml)  

##Task 3: Concepts

###Q1. What are some benefits of continuous integration?
There are various benefits that the developers claim over the use of continuous integration. Some of them are:
<ol>
<li>Projects that use CI have higher code quality</li>
<li>Developers on projects with CI are more productive</li>
<li>CI allows a system to be tested on
all major platforms (Windows, Linux, and OS X), without
each environment being setup locally by each developer</li>
<li>CI makes integration easier</li>
<li>CI offers a global mechanism for feedback about failure, enabling developers to have more confidence in making their changes.</li>


</ol>


###Q2. What are some risks of not using continuous integration?

<ol>
<li><b>CI helps catch bug earlier:</b> Preventing the deployment of
broken code is a major concern for developers. Finding and
fixing bugs in production can be an expensive and stressful
endeavor. If one doesn't use CI then he/she might commit bugs in the code, without detecting it earlier.</li>

<li><b>Providing a common build environment</b>: By starting the CI
process with a clean environment, fetching all the dependencies,
and then building the code each time, developers can be assured
that they can always build their code. This is not possible without CI.</li>
<li><b>Enforcing a specific workflow:</b> Prior to CI, there was no
common way for tools to enforce a specific workflow (e.g.,
ensuring all tests are run before accepting changes). Hence, using CI a specific workflow can be ensured.</li>
<li><b>Difficulty in maintaining development and testing environments:</b> CI allows for better tool integration.
</li>
<li>Little or no confidence in whether we could even build the software
</li>
<li>Lengthy integration phases before delivering the software internally (to test teams) or externally (customer), during which nothing else got done</li>

</ol>

###Q3. What are some reasons why a company may use a dedicated build team?

Having a dedicated build team has many advantages 
<ol>
<li>Build teams take over the role of building software.</li>
<li>Can serve as gatekeepers on code integration.</li>
<li>Create build configuration and sometimes verification scripts</li>
<li>Putting out fires, helping with build failures</li>
</ol>

###Q4. What are some barriers to applying continuous integration in Proprietary contexts? 
There are various barriers to applying continuous integration in Proprietary contexts such as: 
<ol>
<li>Barriers to adopting CI</li>
	<ul>
	<li>Developers who wish to adopt technology solutions thatwill help them be more productive are often stymied byinstitutional hurdles.</li>

</ul>

<li>Barriers when using CI
<ul> 
<li><b>Difficulty troubleshooting a CI build failure</b></li>
In some situations identifying the reason for build failure can become really difficult.
<li><b>Overly long build times</b></li> The build times can be small to very long depending upon the size of the project. This causes some wastage of time according to some set of developers.
<li><b>User interfaces for modifying CI configurations</b></li> Most of the CI tools are administred using configuration scripts. A user interface to edit these config files can make the work easier.
<li><b>Debugging assistance</b></li> One of the most popular ways of debugging test failures is getting console output and start their search there. The length of these logs can be very long. This can create quite a challenge when trying to find a specific failure.
<li><b>Better container/virtualization support</b></li>Each build in CI should be done in a clean environment. It should not depend on the environment containing the output from any previous builds.
</ul>
</li>

</ol>

##Task 4: Screencast

 Screencast of the assignment:

 * [Screencast](https://youtu.be/iGHKJgjOu4Q)  

