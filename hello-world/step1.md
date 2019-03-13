This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command##**

`ls` {{execute}}



Adding Name Space BLUE

`ip netns add blue`{{execute}}

Adding Name Space RED

`ip netns add red`{{execute}}

`ovs-vsctl add-br net`{{execute}}

`ip link add tap1 type veth peer name bluetap1`{{execute}}
