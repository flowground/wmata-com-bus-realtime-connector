# ![LOGO](logo.png) Real-Time Bus Predictions **flow**ground Connector

## Description

A generated **flow**ground connector for the Real-Time Bus Predictions API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/wmata.com/bus-realtime/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:58+03:00

## API Description

Real-time bus prediction methods.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### XML - Next Buses

> <h4 class="text-primary">Description</h4><br/>
> <br/>
> <p>Returns next bus arrival times at a stop.</p><br/>
> <br/>
> <h4 class="text-primary">Response Elements</h4><br/>
> <br/>
> <table class="table table-condensed table-hover"><br/>
> <thead><br/>
> <tr><br/>
> <th class="col-md-3">Element</th><br/>
> <br/>
> <th>Description</th><br/>
> </tr><br/>
> </thead><br/>
> <br/>
> <tbody><br/>
> <tr><br/>
> <td>Predictions</td><br/>
> <br/>
> <td><br/>
> Array containing bus predictions (<a href=<br/>
> "#NextBusPrediction">NextBusPrediction</a>).<br/>
> </td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>StopName</td><br/>
> <br/>
> <td>Full name of the given StopID.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td colspan="2"><br/>
> <div class="text-primary" style="margin-top: 1em"><br/>
> <a id="NextBusPrediction" name=<br/>
> "NextBusPrediction">NextBusPrediction Elements</a><br/>
> </div><br/>
> </td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>DirectionNum</td><br/>
> <br/>
> <td>Denotes a binary direction (0 or 1) of the bus. There is no<br/>
> specific mapping to direction, but a different value for the same<br/>
> route signifies that the buses are traveling in opposite<br/>
> directions. Use the DirectionText element to show the actual<br/>
> destination of the bus.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>DirectionText</td><br/>
> <br/>
> <td>Customer-friendly description of direction and destination for<br/>
> a bus.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>Minutes</td><br/>
> <br/>
> <td>Minutes until bus arrival at this stop. Numeric value.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>RouteID</td><br/>
> <br/>
> <td>Base route name as shown on the bus. This can be used in other<br/>
> bus-related methods. Note that all variants will be shown as their<br/>
> base route names (i.e.: 10Av1 and 10Av2 will be shown as 10A).</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>TripID</td><br/>
> <br/>
> <td>Trip identifier. This can be correlated with the data in our<br/>
> bus schedule information as well as bus positions.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>VehicleID</td><br/>
> <br/>
> <td>Bus identifier. This can be correlated with results returned<br/>
> from bus positions.</td><br/>
> </tr><br/>
> </tbody><br/>
> </table>

#### Input Parameters
* `StopID` - _required_ - 7-digit regional stop ID.
    Possible values: 1001195.

### JSON - Next Buses

> <h4 class="text-primary">Description</h4><br/>
> <br/>
> <p>Returns next bus arrival times at a stop.</p><br/>
> <br/>
> <h4 class="text-primary">Response Elements</h4><br/>
> <br/>
> <table class="table table-condensed table-hover"><br/>
> <thead><br/>
> <tr><br/>
> <th class="col-md-3">Element</th><br/>
> <br/>
> <th>Description</th><br/>
> </tr><br/>
> </thead><br/>
> <br/>
> <tbody><br/>
> <tr><br/>
> <td>Predictions</td><br/>
> <br/>
> <td><br/>
> Array containing bus predictions (<a href=<br/>
> "#NextBusPrediction">NextBusPrediction</a>).<br/>
> </td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>StopName</td><br/>
> <br/>
> <td>Full name of the given StopID.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td colspan="2"><br/>
> <div class="text-primary" style="margin-top: 1em"><br/>
> <a id="NextBusPrediction" name=<br/>
> "NextBusPrediction">NextBusPrediction Elements</a><br/>
> </div><br/>
> </td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>DirectionNum</td><br/>
> <br/>
> <td>Denotes a binary direction (0 or 1) of the bus. There is no<br/>
> specific mapping to direction, but a different value for the same<br/>
> route signifies that the buses are traveling in opposite<br/>
> directions. Use the DirectionText element to show the actual<br/>
> destination of the bus.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>DirectionText</td><br/>
> <br/>
> <td>Customer-friendly description of direction and destination for<br/>
> a bus.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>Minutes</td><br/>
> <br/>
> <td>Minutes until bus arrival at this stop. Numeric value.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>RouteID</td><br/>
> <br/>
> <td>Base route name as shown on the bus. This can be used in other<br/>
> bus-related methods. Note that all variants will be shown as their<br/>
> base route names (i.e.: 10Av1 and 10Av2 will be shown as 10A).</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>TripID</td><br/>
> <br/>
> <td>Trip identifier. This can be correlated with the data in our<br/>
> bus schedule information as well as bus positions.</td><br/>
> </tr><br/>
> <br/>
> <tr><br/>
> <td>VehicleID</td><br/>
> <br/>
> <td>Bus identifier. This can be correlated with results returned<br/>
> from bus positions.</td><br/>
> </tr><br/>
> </tbody><br/>
> </table>

#### Input Parameters
* `StopID` - _required_ - 7-digit regional stop ID.
    Possible values: 1001195.

## License

**flow**ground :- Telekom iPaaS / wmata-com-bus-realtime-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
