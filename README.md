# esx_taxijob

ESX Taxi Job adds driving cabs as a service, and more including NPC missions.

## Requirements

* Auto mode
  * [esx_service](https://github.com/ESX-Org/esx_service)

* Player management (billing and boss actions)
  * [esx_society](https://github.com/ESX-Org/esx_society)
  * [esx_billing](https://github.com/ESX-Org/esx_billing)

## Download & Installation

### Download via GIT

Clone the repository directly into your ESX folder.
This will allow you to easily update

```
cd resources
git clone https://github.com/lachee/esx_taxijob [esx]/esx_taxijob
```

If you need to update

```
cd resources/[esx]/esx_taxijob
git pull
```


### Installation
1. Import `esx_taxijob.sql` in your database
2. Copy `sample-config.lua` to `config.lua`.
3. If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
4. Add this to your `server.cfg`:

```
start esx_taxijob
```

# Legal
### License
esx_taxijob

Copyright (C) 2015-2020 Jérémie N'gadi

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
