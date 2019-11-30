# what is this?

Get perfect shadow every time for the non-designer.

#installation

```javascript
npm i salt

```
then ...
 
 ``` javascript
 import {salt} from 'salt';

 salt ({
     shadow_type: 'soft',
     padding: false
 })

 ```
# options
Salt support 2 options, both of which are optional:
* *shadow_type* - _hard | soft_ (Default to soft)
* *padding* - _boolean_ (Default to false