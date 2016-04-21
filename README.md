Boris-Bikes-Java
=============

London's [Boris Bikes](https://tfl.gov.uk/modes/cycling/santander-cycles) (well, 'Santander Cycles') are awesome. For a small fee, anyone can hire out a bike and ride it around London. Bikes are located at Docking Stations dotted throughout the city.

User stories.
-------------------------

```
As a person,
So that I can use a bike,
I'd like a docking station to release a bike.

As a person,
So that I can use a good bike,
I'd like to see if a bike is working

As a member of the public
So I can return bikes I've hired
I want to dock my bike at the docking station

As a member of the public
So I can decide whether to use the docking station
I want to see a bike that has been docked

As a member of the public,
So that I am not confused and charged unnecessarily,
I'd like docking stations not to release bikes when there are none available.

As a maintainer of the system,
So that I can control the distribution of bikes,
I'd like docking stations not to accept more bikes than their capacity.

As a system maintainer,
So that I can plan the distribution of bikes,
I want a docking station to have a default capacity of 20 bikes.

As a system maintainer,
So that busy areas can be served more effectively,
I want to be able to specify a larger capacity when necessary.

As a member of the public,
So that I reduce the chance of getting a broken bike in future,
I'd like to report a bike as broken when I return it.

As a maintainer of the system,
So that I can manage broken bikes and not disappoint users,
I'd like docking stations not to release broken bikes.

As a maintainer of the system,
So that I can manage broken bikes and not disappoint users,
I'd like docking stations to accept returning bikes (broken or not).

As a maintainer of the system,
So that I can manage broken bikes and not disappoint users,
I'd like vans to take broken bikes from docking stations and deliver them to garages to be fixed.

As a maintainer of the system,
So that I can manage broken bikes and not disappoint users,
I'd like vans to collect working bikes from garages and distribute them to docking stations.
```


The application needs to be driven by TDD and BDD by using Java, JUnit.


Technologies used
-----------------

  * Testing
    * JUnit 4.0

  * Back end framework
    * Java

  * Project structure
    * Maven

  * Continuous Integration
    * Travis CI


Testing and running environment setup
--------------------------------------

In order to edit, view or modify the source code, you will need to clone the repo shown below, access the folder and execute the following commands to be functional.


```sh
$ git clone https://github.com/Willibaur/boris-bikes-Java
$ cd boris-bikes-Java
```



Contributors
------------

* [William Bautista](https://github.com/Willibaur)