# Windsor, ON

Windsor, ON is supported by the generic [ICS](/doc/source/ics.md) source. For all available configuration options, please refer to the source description.


## How to get the configuration arguments

1. Go to the [garbage collection schedule page](https://www.citywindsor.ca/residents/Waste-And-Recycling/Collection-Schedule/Pages/Garbage-Collection.aspx) on the City of Windsor website.
2. Find out which zone your address is associated with by either looking at the map or postal code chart.
3. Append the zone identifier to the URL after `?location=`.

## Examples

### Zone 1a

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=1a
```
### Zone 1b

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=1b
```
### Zone 2a

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=2a
```
### Zone 3b

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=3b
```
