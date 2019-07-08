# ![LOGO](logo.png) Real-Time Bus Predictions **flow**ground Connector

## Description

A generated **flow**ground connector for the Real-Time Bus Predictions API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/wmata.com/bus-realtime/1.0/swagger.json<br/>
Generated at: 2019-07-08T14:36:02+03:00

## API Description

Real-time bus prediction methods.<br/>

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### XML - Next Buses
<blockquote><h4 class="text-primary">Description</h4>

<p>Returns next bus arrival times at a stop.</p>

<h4 class="text-primary">Response Elements</h4>

<table class="table table-condensed table-hover">
<thead>
<tr>
<th class="col-md-3">Element</th>

<th>Description</th>
</tr>
</thead>

<tbody>
<tr>
<td>Predictions</td>

<td>
Array containing bus predictions (<a href=
"#NextBusPrediction">NextBusPrediction</a>).
</td>
</tr>

<tr>
<td>StopName</td>

<td>Full name of the given StopID.</td>
</tr>

<tr>
<td colspan="2">
<div class="text-primary" style="margin-top: 1em">
<a id="NextBusPrediction" name=
"NextBusPrediction">NextBusPrediction Elements</a>
</div>
</td>
</tr>

<tr>
<td>DirectionNum</td>

<td>Denotes a binary direction (0 or 1) of the bus. There is no
specific mapping to direction, but a different value for the same
route signifies that the buses are traveling in opposite
directions. Use the DirectionText element to show the actual
destination of the bus.</td>
</tr>

<tr>
<td>DirectionText</td>

<td>Customer-friendly description of direction and destination for
a bus.</td>
</tr>

<tr>
<td>Minutes</td>

<td>Minutes until bus arrival at this stop. Numeric value.</td>
</tr>

<tr>
<td>RouteID</td>

<td>Base route name as shown on the bus. This can be used in other
bus-related methods. Note that all variants will be shown as their
base route names (i.e.: 10Av1 and 10Av2 will be shown as 10A).</td>
</tr>

<tr>
<td>TripID</td>

<td>Trip identifier. This can be correlated with the data in our
bus schedule information as well as bus positions.</td>
</tr>

<tr>
<td>VehicleID</td>

<td>Bus identifier. This can be correlated with results returned
from bus positions.</td>
</tr>
</tbody>
</table></blockquote>

#### Input Parameters
* `StopID` - _required_ - 7-digit regional stop ID.<br/>
    Possible values: 1001195.

### JSON - Next Buses
<blockquote><h4 class="text-primary">Description</h4>

<p>Returns next bus arrival times at a stop.</p>

<h4 class="text-primary">Response Elements</h4>

<table class="table table-condensed table-hover">
<thead>
<tr>
<th class="col-md-3">Element</th>

<th>Description</th>
</tr>
</thead>

<tbody>
<tr>
<td>Predictions</td>

<td>
Array containing bus predictions (<a href=
"#NextBusPrediction">NextBusPrediction</a>).
</td>
</tr>

<tr>
<td>StopName</td>

<td>Full name of the given StopID.</td>
</tr>

<tr>
<td colspan="2">
<div class="text-primary" style="margin-top: 1em">
<a id="NextBusPrediction" name=
"NextBusPrediction">NextBusPrediction Elements</a>
</div>
</td>
</tr>

<tr>
<td>DirectionNum</td>

<td>Denotes a binary direction (0 or 1) of the bus. There is no
specific mapping to direction, but a different value for the same
route signifies that the buses are traveling in opposite
directions. Use the DirectionText element to show the actual
destination of the bus.</td>
</tr>

<tr>
<td>DirectionText</td>

<td>Customer-friendly description of direction and destination for
a bus.</td>
</tr>

<tr>
<td>Minutes</td>

<td>Minutes until bus arrival at this stop. Numeric value.</td>
</tr>

<tr>
<td>RouteID</td>

<td>Base route name as shown on the bus. This can be used in other
bus-related methods. Note that all variants will be shown as their
base route names (i.e.: 10Av1 and 10Av2 will be shown as 10A).</td>
</tr>

<tr>
<td>TripID</td>

<td>Trip identifier. This can be correlated with the data in our
bus schedule information as well as bus positions.</td>
</tr>

<tr>
<td>VehicleID</td>

<td>Bus identifier. This can be correlated with results returned
from bus positions.</td>
</tr>
</tbody>
</table></blockquote>

#### Input Parameters
* `StopID` - _required_ - 7-digit regional stop ID.<br/>
    Possible values: 1001195.

## License

**flow**ground :- Telekom iPaaS / wmata-com-bus-realtime-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
