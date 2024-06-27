# NXVapps
Project repository explaining the project and sub-projects

## What is NXVapps
This project is to provide resources and containers to provide virtual GPU accelerated
workstations app into a new state. Mostly, until now, apps have been run from VM's or
machines with remote desktop. This is restrictive, expensive, and slow to spin up.

After looking at how AL/ML functions with Kubernetes and as Serverless, where it really
thrives, we examined how that could be applied to some of our existing offerings with
virtual workstations. So NXVapps was born.

The goal is to wrap apps up so they can be GPU accelerated on the backend and served
via a web browser without the need of remote desktop, or a desktop at all. Just the app.

This reduces costs, allows multi-tenancy, and reduces spin up time while also exploding
the available options for things such as storage, queuing, facilitation, and other features.

Serverless for virtual workstation!

## The base app, vapp
The base app that facilitates this project is vapp. This is the underlying app that is powering
all our applications and containers.

https://github.com/nxvapps/vapp

## Getting Started
If you want to produce your own serverless virtual workstation app, we have provided a barebones
template for you to extend to build your app from. This should greatly reduce the complexity and
difficulty in the process while remaining flexible enough for any app.

https://github.com/nxvapps/vapp-template

## Apps we currently offer
We offer a library of apps ready to go for any purpose or need. You can find out current offering
here,

* [ncast (OBS)](https://github.com/nxvapps/ncast)
* [nblender (Blender)](https://github.com/nxvapps/nblender)
* [nfreecad (FreeCad)](https://github.com/nxvapps/nfreecad)

## Contributing
We encourage all contributions here. Get in on the ground floor of a completely new way of serving
virtual workstation apps! If you have a project you want to start let us know and we can get you
setup and started!
