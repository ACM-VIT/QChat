<h1 align="center"><a href="https://organize.mlh.io/participants/events/4390-kickstarting-hacktoberfest-with-acm-vit">Kicking Off Hacktoberfest with ACM-VIT!</a></h1>
<p align="center">
<img src="https://user-images.githubusercontent.com/67265786/194695103-47903f06-20aa-450f-af56-78b9cc860d6f.png">
</p>

<h2 align="center"> QChat </h2>

<p align="center"> 
Mobile chat application with end-to-end encryption using Quantum Key Distribution (QKD)
</p>

<p>
  <a href="https://acmvit.in/" target="_blank">
    <img alt="made-by-acm" src="https://img.shields.io/badge/MADE%20BY-ACM%20VIT-blue?style=for-the-badge" />
  </a>
    <!-- Uncomment the below line to add the license badge. Make sure the right license badge is reflected. -->
    <!-- <img alt="license" src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" /> -->
    <!-- forks/stars/tech stack in the form of badges from https://shields.io/ -->
</p>

---
## Submitting a Pull Request

 * Fork the repository by clicking the fork button on top right corner of the page
 * Clone the target repository. To clone, click on the clone button and copy the https address. Then run 
 <pre><code>git clone [HTTPS-ADDRESS]</code></pre>
* Go to the cloned directory by running 
<pre><code>cd [NAME-OF-REPO]</code></pre>
* Create a new branch. Use 
<pre><code> git checkout -b [YOUR-BRANCH-NAME]</code></pre>
* Make your changes to the code. Add changes to your branch by using 
<pre><code>git add .</code></pre>
* Commit the chanes by executing
<pre><code>git commit -m "your msg"</code></pre>
* Push to remote. To do this, run 
<pre><code>git push origin [YOUR-BRANCH-NAME]</code></pre>
* Create a pull request. Go to the target repository and click on the "Compare & pull request" button. **Make sure your PR description mentions which issues you're solving.**
<img src="https://drive.google.com/u/1/uc?id=1f9JKAR-kRvCRGxIs_SAvegaYDPx53T9G&export=download"></img>
* Wait for your request to be accepted. 

---
## Guidelines for Pull Request

<!-- general guidelines here -->
  * Avoid pull requests that :
      * are automated or scripted
      * that are plagarized from someone else's branch
  * Do not spam
  * Project maintainer's decision on validity of PR is final.

  For additional guidelines, refer to [participation rules](https://hacktoberfest.digitalocean.com/details#rules)

---
## Overview
This project aims to make a flutter mobile app for chatting purposes. The app will have a simple and clean UI with an easy login and logout feature. Then the user can use their username to send others friend requests. The way this works is when a user sends a request, a string of qubits in random state is generated in the backend. If the other user decides to accept the request, they will measure the incoming set of qubits to generate a private key using Quantum Key Distrubition(QKD). This key will be used to secure their chats by end to end encryption of their texts. We will be using BB84 protocol, based on the polarization of a single photon

---
## Usage
<!-- How To, Features, Installation etc. as subheadings in this section. example-->

Lets get started!
```console
git remote add
git fetch
git merge
```

---
## Authors

**Authors:** [Manav Taluja](https://github.com/Mayan-Ryan) 

**Contributors:** 

<a href="https://github.com/Mayan-Ryan/QChat/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Mayan-Ryan/QChat" />
</a>

