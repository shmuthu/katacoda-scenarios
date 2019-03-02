This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command##**

`ip netns add blue`{{execute}}
`ip netns add red`{{execute}}
`ovs-vsctl add-br net`{{execute}}

`ip link add tap1 type veth peer name bluetap1`{{execute}}
