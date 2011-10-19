Supercell, the Cloud Platform for Online Game Development
=========================================================

Project Overview
----------------

Deploying an online game service can be a challenging and expensive
endeavor. The cost of maintaining the real-time experience for
end-users easily overruns the budget of many small and medium-sized
game studios. Because of this, we have spent years to develop a
complete MMO cloud computing solution based on patent pending GPU
technology. With the high performance network technology, one GPU
cluster can support over 10x the client capacity of current CPU-based
solutions. This opens the door to more complex game design choices
such as smarter AI, real-time physics, crowd simulation, path-finding,
and since game rules are enforced on the cloud - better game cheating protection.
Our cloud computing platform enables more game content to be created with less compromise.

Game developers can freely augment/enrich their gameworlds without the worry of
performance degradation and the burden of deployment and hosting.

Dependencies
------------
* Boost C++ Library v1.47 or later
* NVIDIA CUDA SDK 4.0 or later
* Apache Log4cxx
* Intel Threading Building Block (TBB) 3.0 or later
* OFED 1.5.2 or later

Build
-----

1. Download repo from here: http://code.google.com/p/git-repo/downloads/list
2. chmod +x repo (you can put it under /usr/sbin)
3. repo init -u git@github.com:zillians/platform_manifest_supercell.git
4. repo sync
5. repo forall -c git checkout -b master --track origin/master
6. repo forall -c git checkout -b develop --track origin/develop
7. cd platform; mkdir build; cd build;
8. cmake ..; make -j4

Installation
------------


Usage
-----


Testing
-------


Contributing
------------
