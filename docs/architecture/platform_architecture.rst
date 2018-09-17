.. ===============LICENSE_START=======================================================
.. Acumos CC-BY-4.0
.. ===================================================================================
.. Copyright (C) 2017-2018 AT&T Intellectual Property & Tech Mahindra. All rights reserved.
.. ===================================================================================
.. This Acumos documentation file is distributed by AT&T and Tech Mahindra
.. under the Creative Commons Attribution 4.0 International License (the "License");
.. you may not use this file except in compliance with the License.
.. You may obtain a copy of the License at
..
.. http://creativecommons.org/licenses/by/4.0
..
.. This file is distributed on an "AS IS" BASIS,
.. WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
.. See the License for the specific language governing permissions and
.. limitations under the License.
.. ===============LICENSE_END=========================================================

============
Architecture
============
.. topics to include:
.. diagram from wiki for an abstracted high level diagram for non-technical consumers
.. at least one entity-relationship diagram (classical architecture view)
.. reference points in the architecture and related APIs, at a high level
.. high-level description of each core component of the platform, and supporting
.. components: what they are, scope, role, how they interact/communicate, 
..   links to component guides
..     -- images/component-architecture-2017.png is outdated
.. images from wiki are in the images folder

Architecture Overview
=====================

.. image::  images/component-architecture-2017.png

Entity Relationships
====================

.. image:: images/acumos-architecture-detail.png

Interfaces and APIs
===================

External Interfaces and APIs
----------------------------

E1 - Toolkit Onboarding
.......................

E2 - Web APIs
.............

E3 - OA&M APIs
..............

E4 - Admin APIs
...............

E5 - Federation APIs
....................

E6 - Deployment APIs
....................

Internal Interfaces and APIs
----------------------------

Common Data Service
...................

Hippo CMS
.........

Portal Backend
..............

Federation Gateway
..................

Microservice Generation
.......................

Security Verification
.....................

Azure Client
............

OpenStack Client
................

Kubernetes Client
.................

Component Logging
.................

ELK Stack
.........

Nexus
.....

Docker
......

Kong
....

Core Components
===============
.. high level description of the components and link to more info

The following sections describe the scope, role, and interaction of the core
Acumos platform components and component libraries. The sections are organized
per the Acumos project teams that lead development on the components.

Portal and User Experience
--------------------------

Portal Frontend
...............

Portal Backend
..............

Hippo CMS
.........

Model Onboarding
----------------

Onboarding App
..............

Java Client
...........

Python Client
.............

R Client
........

Design Studio
-------------

Design Studio Composition Engine
................................

Data Broker
...........

Runtime Orchestrator ("Model Connector")
........................................

Proto Viewer ("Probe")
......................

Deployment
----------

Azure Client
............

Openstack Client
................

Kubernetes Client
.................

Docker Proxy
............

Catalog, Data Model and Data Management
---------------------------------------

Common Data Service
...................

Federation Gateway
..................

Model Schema
............

Common Services
---------------

Microservice Generation
.......................

Nexus Client
............

Generic Model Runner
....................

Python DCAE Model Runner
........................

Security Verification
.....................

Supporting Components
=====================
.. high level description of the components and link to more info

The following sections describe the scope, role, and interaction of supporting
Acumos platform components and tools.

Operations, Admin, and Maintenance (OAM)
----------------------------------------

System Integration
..................

Filebeat
........

Metricbeat
..........

ELK Stack
.........

Other Supporting Components
---------------------------

MariaDB
......

Nexus
.....

Kong
....

Docker-CE
.........

Kubernetes
..........
