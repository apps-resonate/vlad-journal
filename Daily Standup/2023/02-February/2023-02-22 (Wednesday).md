#daily-notes | #February-2023

## What I did today


### General

- Daily Stand-up: Excused because Deployment in Astra

### Display featured properties first on marketplace when sorted by availability

- Monday: https://resonateasia.monday.com/boards/2892335277/views/86997785/pulses/3874667529?term=featured

- Github: https://github.com/resonate-dev/saturn/pull/205

-   Ransackified the search filters  
    -"Property Type"
    -   "Unit Status (Transaction Type)" -- ransackified to avoid issues with ransort.
    -   "Location"
    -   Size (for condominium)
    -   Search bar to search for project name OR reference ID
    -   Min and Max prices are ransackified to avoid issues with ransort.

-   Ransortified sorting of listings
    -   Fixed Unit Status (Availability)
    -   added second sorting by "Recommendations" after availability for SortBy option "Availability" -- this is the actual solution to the story (display featured properties first in marketplace)
    -   Prices High to Low and Low to High are now Ransort

- Also fixed search ability in show page.
-   Grouped up common actions/controller methods for both show and index

### To Do


### To Ask


## Concerns For Huddle

