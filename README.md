# ![LOGO](logo.png) CFB v3 Scores **flow**ground Connector

## Description

A generated **flow**ground connector for the CFB v3 Scores API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/cfb-v3-scores/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:30+03:00

## API Description

CFB schedules, scores, team stats, odds, weather, and news API.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Are Games In Progress

> Returns <code>true</code> if there is at least one game being played at the time of the request or <code>false</code> if there are none.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.

### Current Season

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.

### Current Week

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.

### Schedules

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2018</code>, <code>2018PRE</code>, <code>2018POST</code>, <code>2018STAR</code>, <code>2019</code>, etc.

### Games by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.
* `date` - _required_ - 
          The date of the game(s).
          <br>Examples: <code>2016-SEP-01</code>, <code>2017-SEP-10</code>.
        

### Games by Week

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season.
          <br>Examples: <code>2015</code>, <code>2016</code>, etc.
        
* `week` - _required_ - 
          The week of the game(s).
          <br>Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc.
        

### Conference Hierarchy (with Teams)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.

### Stadiums

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.

### Team Game Stats by Week

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season.
          <br>Examples: <code>2015</code>, <code>2016</code>, etc.
        
* `week` - _required_ - 
          The week of the game(s).
          <br>Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc.
        

### Team Season Stats & Standings

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2017</code>, <code>2017POST</code>, <code>2018</code>.

### Teams

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>xml</code> or <code>json</code>.
    Possible values: XML, JSON.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-cfb-v-3-scores-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
