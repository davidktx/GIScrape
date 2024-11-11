# Texas

Data sets are available from the Railroad Commission of Texas at free of charge.

The conversion of the data and choice of conversion tools is the responsibility of the user.

If you have any questions about the data sets, email the RRC at [Publicassist@rrc.texas.gov](mailto:publicassist@rrc.texas.gov).

The Railroad Commission of Texas (RRC) maintains this website as a public service.

View the Digital Map Information GIS Data [Frequently Asked Questions](https://www.rrc.state.tx.us/about-us/faqs/general-faq/digital-map-information-gis-data/).

Geographic Coordinates; Latitude/Longitude Decimal Degrees, NAD 27

# State Data API

API: https://gis-txdot.opendata.arcgis.com/datasets/TXDOT::statewide-surface-wells/api


# State Data Location

Main Download Page: [Data Sets Available for Download](https://www.rrc.state.tx.us/resource-center/research/data-sets-available-for-download/)

## Drilling Permit Data

### Drilling Permit Master

This data set contains drilling permit information on every application to drill for an oil or gas well in Texas since 1976

Updated Monthly\
Available By the 7th working day.

### Drilling Permit Master and Trailer

This data set contains information on every application to drill for an oil or gas well in Texas since 1976,

### Drilling Permit Master and Trailer - Daily

This data set contains drilling permit information.

**Includes Latitudes and Longitudes**

The file has current month only and accumulates daily through the month. Available Daily

### Drilling Permits Master and Trailer - End of Month

This data set contains information on every application to drill for an oil or gas well in Texas since 1976.

**Includes Latitudes and Longitudes**

The file accumulates daily throughout the month and is produced the day after the last day of the month.

### Drilling Permits Pending Approval

**Includes Latitudes and Longitudes**

This data set contains information on pending drilling applications that have not yet been approved by the RRC.

## Latitudes and Longitudes

```
*****************************************************************
* DAW999A1 *
* WORKING-STORAGE COPY FOR SURFACE LOCATION DATA RETRIEVED FROM *
* THE GIS SYSTEM FOR OUTSIDE REQUEST. THIS *
* INFORMATION IS NOT RETRIEVED FROM THE *
* MAINFRAME IMS SYSTEM. NO IMS SEGMENT *
* CONTAINING THIS INFORMATION EXISTS. *
* *
*****************************************************************
*
01 DA-SURFACE-LOCATION-INFO.
05 DA-SURF-LOC-LONGITUDE PIC 9(5)V9(7) VALUE SPACES.
05 DA-SURF-LOC-LATITUDE PIC 9(5)V9(7) VALUE SPACES.
```

```
*****************************************************************
* DATA DICTIONARY FOR SURFACE LOCATION DATA RETRIEVED FROM *
* THE GIS SYSTEM FOR OUTSIDE REQUEST. THIS *
* INFORMATION IS NOT RETRIEVED FROM THE *
* MAINFRAME IMS SYSTEM. NO IMS SEGMENT *
* CONTAINING THIS INFORMATION EXISTS. *
*****************************************************************
------------------------
DA-SURFACE-LOCATION-INFO
------------------------
A SINGLE TYPE 14 SURFACE LOCATION RECORD WILL EXIST FOR A PERMIT
SEGMENT. EACH COORDINATE WILL SPAN 12 COLUMNS AND WILL HAVE 7
DIGITS TO THE RIGHT OF THE DECIMAL POINT. THIS RECORD CONTAINS A
GEOGRAPHIC COORDINATE PAIR THAT HAS BEEN EXTRACTED FROM THE RRC'S
GIS SYSTEM. THE LOCATION IS TYPICALLY DETERMINED BY CALCULATING
DIRECTIONS AND DISTANCES FROM THE RRC'S INTERPRETED ORIGINAL LAND
SURVEY BOUNDARIES. THE LATITUDE/LONGITUDE COORDINATE VALUES
HORIZONTALLY REFERENCED TO NORTH AMERICAN DATUM 1927(NAD27) ARE
THEN DERIVED FROM THE SPOTTED LOCATION. USERS OF THIS DATA
SHOULD BE AWARE THAT THE COORDINATES DO NOT NECESSARILY REPRESENT
A TRUE GEOGRAPHIC LOCATION AND ARE SUBJECT TO CHANGE UPON
MAINTENANCE TO THE RRC'S SURVEY BOUNDARIES.
---------------------
DA-SURF-LOC-LONGITUDE
---------------------
THE LONGITUDE COORDINATE VALUE OF THE SURFACE LOCATION OF THE
WELLBORE.
--------------------
DA-SURF-LOC-LATITUDE
--------------------
THE LATITUDE COORDINATE VALUE OF THE SURFACE LOCATION OF THE
WELLBORE.
```

```
*****************************************************************
* DAW999B1 *
* WORKING-STORAGE COPY FOR BOTTOM HOLE LOCATION DATA RETRIEVED *
* FROM THE GIS SYSTEM FOR OUTSIDE REQUEST. THIS *
* INFORMATION IS NOT RETRIEVED FROM THE *
* MAINFRAME IMS SYSTEM. NO IMS SEGMENT *
* CONTAINING THIS INFORMATION EXISTS. *
*****************************************************************
*
01 DA-BOTTOM-HOLE-INFO.
05 DA-BOTTOM-HOLE-LONGITUDE PIC 9(5)V9(7) VALUE SPACES.
05 DA-BOTTOM-HOLE-LATITUDE PIC 9(5)V9(7) VALUE SPACES.
```
