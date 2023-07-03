# 4DModeller tutorial data

This repository contains the data for the [4DModeller `fdmr` tutorials](https://4dmodeller.github.io/fdmr/articles/).

## Adding a new dataset

The `fdmr::retrieve_tutorial_data` function downloads `datasets.json` to check valid datasets and the date of their last update.
To add a new dataset copy and paste the following template into the end of the dictionry in `datasets.json` and complete `filename` and
`last_updated` fields.

```json
"dataset_name": {
      "filename": "tutorial_b_data.tar.bz2",
      "last_updated": "2024-01-01"
    },
```

Then add a note in `CHANGELOG.md` detailing what you've added and why.