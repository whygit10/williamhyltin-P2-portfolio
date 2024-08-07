# processed-data

This folder contains data that has been processed and cleaned by code.

Any files located in here are based on the raw data and can be re-created running the various processing/cleaning code scripts in the `code` folder.

Code Book is included here, copied from the source code book.


| Field                       | Description                                                                                                  |
|------------------------------|------------------------------------------|
| Incident Number             | Incident report number                                                                                       |
| Highest Offense Description | Description                                                                                                  |
| Highest Offense Code        | Code                                                                                                         |
| Family Violence             | Incident involves family violence? Y = yes, N = no                                                           |
| Occurred Date Time          | Date and time (combined) incident occurred                                                                   |
| Occurred Date               | Date the incident occurred                                                                                   |
| Occurred Time               | Time the incident occurred                                                                                   |
| Report Date Time            | Date and time (combined) incident was reported                                                               |
| Report Date                 | Date the incident was reported                                                                               |
| Report Time                 | Time the incident was reported                                                                               |
| Location Type               | General description of the premise where the incident occurred                                               |
| Address                     | Incident location                                                                                            |
| Zip code                    | Zip code where incident occurred                                                                             |
| Council District            | Austin city council district where the incident occurred                                                     |
| APD Sector                  | APD sector where incident occurred                                                                           |
| APD District                | APD district where incident occurred                                                                         |
| PRA                         | APD police reporting area where incident occurred                                                            |
| Census Tract                | Census tract where incident occurred                                                                         |
| Clearance Status            | How/whether crime was solved (see Clearance lookup)                                                          |
| Clearance Date              | Date crime was solved                                                                                        |
| UCR Category                | Code for the most serious crimes identified by the FBI as part of its Uniform Crime Reporting program        |
| Category Description        | Description for the most serious crimes identified by the FBI as part of its Uniform Crime Reporting program |
| X-coordinate                | X-coordinate where the incident occurred                                                                     |
| Y-coordinate                | Y-coordinate where incident occurred                                                                         |
| Latitude                    | Latitude where incident occurred                                                                             |
| Longitude                   | Longitude where the incident occurred                                                                        |
| Location                    | 3rd party generated spatial column                                                                           |

| Clearance lookup |                      |
|------------------|----------------------|
| C                | Cleared by Arrest    |
| O                | Cleared by Exception |
| N                | Not cleared          |
