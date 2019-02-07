![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Remote APIs

### Author: Fletcher LaRue

### Links and Resources
* [repo](https://github.com/asdFletcher/33-remote-apis)
* [code sandbox, official version](https://codesandbox.io/s/pm4po3j00j)
* [code sandbox no-thunk version, not complete](https://codesandbox.io/s/74lyzrvq06)


### Description

The front end react redux application is linked to the star wars API.

State is stored in memory.

There is initial state stored with a couple people.

To update the list of people, there is a button to fetch a new list of 10 people from the Star Wars API (SWAPI)

To view details on a person , click their name. This makes another API call if the person's detail information is not already stored. So successive calls to the same person's detail information will be quicker.

