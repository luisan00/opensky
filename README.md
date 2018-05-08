# opensky-lib
-WORK IN PROGRESS-

Dependency free node.js library for tracking real time flight data
thanks to the great work of The OpenSky Network, http://www.opensky-network.org

## Installation
Using npm:
```bash
npm install opensky-lib
```
## Usage
```js
const opensky = require('opensky-lib');

// Create an instance as anonymous user:
const openSky = new opensky();

// With credentials:
const openSky = new opensky('your_user_name', 'your_account_password');

// Alternatively you can use an object with your credentials as the following example shows:
const openSky = new opensky({user: 'user_name', pass: 'account_password'});


// ..to be continue
```
## Contributing
I'll be happy to hear your ideas or fix some bug.
Please feel free to send me a message or create a new issue.

## LICENSE
Copyright (C) 2018 luisan00
Licensed under the GNU General Public License version v3.0 (GPL-3)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
This software is licensed under the GPL-3
