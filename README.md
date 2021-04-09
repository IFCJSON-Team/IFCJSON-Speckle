# IFCJSON-Speckle

As you know in this group we are super excited about making it easier to work collaboratively with building data over the web. To do this we don't want to reinvent the wheel but to use standard vanilla web tools to do this. This provides our initial motivation for JSON and also opens the door to collaboration with tonnes of other people that are doing awesome stuff with building data over the web, including for instance, HYPAR, IFC.js, BHOM and obviously for this repo, Speckle. 

The IFCJSON-Speckle project initially focused on Speckle 1.0, but is now being revisited to look at Speckle 2.0 and the potential integration with IFCJSON.

Therefore to play along it assumes that you ....

1. have been lucky and been granted your beta access to [Speckle 2.0](https://speckle.systems/getstarted/) or are part of an amazing organisation that already has a license.
2. then followed the awesome [zero to Speckle ASAP tutorial](https://speckle.guide/user/quickstart.html) 
3. then set up the [speckle-py](https://speckle.guide/dev/python.html) working folder (I know, python again, but we really like it!)
4. cool, now follow the [tutorials](https://speckle.guide/dev/py-sample.html) to start doing some automation on the speckle streams.

## Ok cool, so now the IFC bit

We are thinking about this is in the following ways and these experiments are documented here.

- the original idea was to write a [speckle kit](https://speckle.guide/dev/kits.html) for IFC, this is still an awesome idea and someone should defo do it....
- Traditional linked data  enables us to query the building information properties associations and relationships. Ontologies can open or fixed. There is an implied disassociation between the linked data format and the data it is linking to. what seems exciting about Speckle2.0 is is objectifies the link thereby enabling the data that is being linked to to have its own structure. We are still at the early stages of exploring this, but below is a rough sketch of a set of streams that could be organised ....
  - project
  - site
  - building
  - floor
  - structure etc.
  
  In previous speckle this would have been problematic because we couldn't send data from different users to the same stream but that is now possible in Speckle2.0. This is work in progress but we are really interested to talk about it.

