# Windsor, ON

Windsor, ON is supported by the generic [ICS](/doc/source/ics.md) source. For all available configuration options, please refer to the source description.


## How to get the configuration arguments

- Go to the [garbage collection schedule page](https://www.citywindsor.ca/residents/Waste-And-Recycling/Collection-Schedule/Pages/Garbage-Collection.aspx) on the City of Windsor website.
- Find out which zone your address is associated with by either looking at the map or postal code chart.
- Append the zone identifier to the URL after `?location=`.

## Examples

### 1a

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=1a
```
### 1b

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=1b
```
### 2a

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=2a
```
### 3b

```yaml
waste_collection_schedule:
  sources:
    - name: ics
      args:
        url: http://opendata.citywindsor.ca/api/events/wasteCollection/ical/?location=3b
```
