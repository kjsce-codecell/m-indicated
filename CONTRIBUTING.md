# Contributions to Vocabulary Builder

## File Name
The name starts with a capital letter.
One word per file.
For instance : `[startingStation]/[startTime].json`

## File Path
Add a train to an existing folder corresponding to the starting station of the word or create a folder.

## JSON File 

The file must contain 3 keys

```
timings: start time of the train from destination 
```
``` 
path: 
start: provide station code of starting station (all caps)
end: provide station code of destination station (all caps)
```
``` 
type: mark fast or slow trains using this tag
```

## Example file (Word with one definition) 

path: `startStation/startTime.json` (first letter needs to be capitalized)
```json
{
    "timing": "startTime_in_HH:MM_in 24 hour format",
    "path": {
        "start":"startStation",
        "end":"endStation"
    },
    "type": "Fast/Slow"
}