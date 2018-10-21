---
title: "Ansible - A first look"
date: 2018-10-21T11:18:19+01:00
topics: ["tech"]
tags: ["ansible"] 
---

I recently started looking at ansible. I've created a playbook to install a master/slave dns-server for my domain. I was surprised at how easy it was to setup. Having used puppet and seeing the overhead of running a puppet agent/master, this was much quicker to get started with. Puppet has it's place (particularly in large scale environments), but ansible wins in terms of simplicity and ease of use to learn get stared with. For example, Ansible does things in the order you write it. In puppet, you need to explicitly state dependencies. You can get puppet to do things in order, but it doesn't come that way out of the box!

Ansible also gives you the ability to run ad-hoc commands. If you want to run a quick command on a handul of boxes, ansible will do it for you. I really like ansibles "push" method.

For now, ansible seems a lot nicer for start-ups and small/medium sized infrastructure. I can see both tools being used to complement each other very nicely, with puppet centrally managing you're large scale infrastructure, with ansible being used for those ad-hoc commands. 

