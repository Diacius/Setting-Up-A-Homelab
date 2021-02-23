# Homelab guide

(I appologise that this is one page, if you know how to make html sections in markdown or can get jekyll links to work properly, please reply to the issue and pull request)

A homelab is great! So I'm writing a guide to help you make one.

It will help if you read these in order, but if you need help with a specific topic, just go straight there.

---

## Contents

1. [Prerequisites](#Prerequisites)
2. [Applications](#Applications)
3. [Options](#Options)

---

## Prerequisites

What you will need

- 1 or more computers
- IT experience
- Depending on what you want to run, some form of OS

---

## Applications
You can do many things with a homelab:

- Run a game server
- Run virtual machines
- Host your files and run a media centre.
- [& Much More!](https://github.com/awesome-selfhosted/awesome-selfhosted)

---

## Options

One of the first things you need to do, is decide how to run your homelab.
You have two main options, you can either
1. [Option one][1] Run all applications in [VMs][wiki_vm] using a hypervisor and or use [Containers][wiki_containers] which can run on top of lnux. [Go Here to start][1]

2. [Option two][2] Run all applications on the host OS at the same time (This sometimes wont work due to applications needing completly different setups)
[Go here to start][2]


[1]: https://diacius.github.io/Setting-Up-A-Homelab/option1
[2]: https://diacius.github.io/Setting-Up-A-Homelab/option2
[wiki_vm]: https://en.wikipedia.org/wiki/Virtual_machine
[wiki_containers]: https://en.wikipedia.org/wiki/OS-level_virtualization
