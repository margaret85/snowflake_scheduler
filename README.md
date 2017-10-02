# _Snowflake Scheduler_

#### _Implementing Snowflake Scheduler in Ruby, 10.05.2017_

#### By _Margaret Berry, Michael Brooks, Dan Kiss, and Dan Garcia_

## Description

_This app allows users to create a profile with a group and a group role. Users can put in their availability, and the app will show which days most members are available in any given week._

## User Stories

* _As a user, I want to create a group._
* _As a user, I want to create a member._
* _As a user, I want to be able to view all groups and members._
* _As a user, I want to be able to edit a group._
* _As a user, I want to be able to delete a group._
* _As a user, I want to be able to edit a member._
* _As a user, I want to be able to delete a member._
* _As a user, I want to be able to view all members in a group._
* _As a user, I want to be able to view a member's group._
* _As a user, I want to be able to add members to a group._
* _As a user, I want to be able to add a group to a member._
* _As a user, I want to be able to add my availability._
* _As a user, I want to be able to see the group's availability._

## Specs

| Spec                       | Input                                                                                                | Output                          |
|----------------------------|------------------------------------------------------------------------------------------------------|---------------------------------|
| Create a group             | One Way Train                                                                                        | Groups: One Way Train           |
| Create a member            | Margaret                                                                                             | Members: Margaret               |
| Edit a group               | Margaret -> Maggie                                                                                   | Members: Maggie                 |
| Edit a member              | One Way Train -> One Way Plane                                                                       | One Way Plane                   |
| Delete a group             | One Way Plane - > Delete                                                                             | Groups:                         |
| Delete a member            | Maggie -> Delete                                                                                     | Members:                        |
| Add a group to a member    | Maggie -> Add group -> One Way Plane                                                                 | Maggie's groups: One Way Plane  |
| Add a member to a group    | One Way Plane -> Maggie                                                                              | One Way Plane's members: Maggie |
| Add availability to member | Maggie: Monday, Thursday, Saturday                                                                   | Maggie's availability: M W S    |
| See group availability     | Maggie's availability: Monday, Wednesday, Saturday  Steve's availability: Tuesday, Wednesday, Friday | Group availability: Wednesday   |

## Setup/Installation Requirements`

1. _Clone the repository and open Terminal or a similar program._
2. _Run bundle in the root file to make sure all necessary gems are installed._
3. _Run rake db:create._
4. _Run rake db:migrate._

![Database Architecture](/DatabaseArchitecture.png)

## Known Bugs

_There are no known bugs at this time._

## Support and contact details

_If you have any updates or suggestions please contact [Margaret] & [Michael] & [Dan K] & [Dan G] or make a contribution yourself._

[Margaret]: mailto:margaretshelaghmcgovern@gmail.com
[Michael]: mailto:mikealphabravo1982@gmail.com
[Dan K]: mailto:flowfast47@gmail.com
[Dan G]: mailto:danny.garcia80@hotmail.com

### License

MIT License

Copyright (c) 2017 Margaret Berry, Michael Brooks, Dan Kiss, and Dan Garcia