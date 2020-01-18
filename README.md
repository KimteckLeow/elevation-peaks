# Elevation Peaks in Malaysia

A few years ago I created _Elevation Peaks in Malaysia_, a map that contains a collection of elevation peak records. It was a simple web demo created using Google Map API. The elevation peak data contains the peak name, GPS coordinates, elevation profile and remark. The data is recorded in JSON format.

[Demo](https://codepen.io/heiswayi/full/rjJjEz)

### Data

I don't hike as much as others, so I don't have much details for the local peaks that people used to go for hike. Other data are simply grabbed from the Internet and their GPS coordinates may not be so accurate. I hosted the data file (`data.json`) on [GitHub](https://github.com/heiswayi/elevation-peaks/blob/master/data.json) if you would like to see.

Example data format for each peak:

```json
{
  "lat": 5.787534,
  "lng": 100.433707,
  "title": "Gunung Jerai",
  "remark": "-",
  "elevation": 1217
}
```

**VOLUNTARY CONTRIBUTION WANTED!** If you think this project is interesting and would like to contribute for the data or make the project better, you are encourage to contact me at _heiswayi (at) nrird (dot) com_ to discuss in details or make some PR on [GitHub](https://github.com/heiswayi/elevation-peaks). Your contribution is really really appreciated.
