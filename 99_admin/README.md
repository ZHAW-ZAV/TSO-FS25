# Admin notes

## Google Colab environments
Installing small packages with few dependencies is possible in Google Colab.
```python
!pip install package_name
```

However, it can take quite some time to install packages in Google Colab and needs to be repeated every time you restart the runtime. Additionally, the `traffic` package returns an error if installed with the command above.

Alternatively, you can create a new environment in Google Colab by following the instructions in `setup_tso_env.ipynb`. This will create a virtual environment on your Google Drive and install the necessary packages.

Once you set up the environment, you can include the code from `use_env.ipynb` in your notebooks to activate the environment. This way, you can use the environment in all your notebooks without having to install the packages every time. The environment can be shared and used by the students.

## Data sets
- **airports.csv**:
    - List of airports with their IATA codes and coordinates.
    - Source: [OurAirports](https://ourairports.com/data/), accessed on 7.1.2025.
    - Google Drive file ID: `1kMt6v9y99hsqgM9ths5Tsdy21VvRb_eB`
- **airports_europe.csv**:
  - List of airports with their IATA codes and coordinates, same as above, but limited to Europe.
  - Source: [OurAirports](https://ourairports.com/data/), accessed on 7.1.2025.
  - Google Drive file ID: `1htJ9M2E6uiJSyQq0vvxIvUqIefwa-L73`
- **co2_emmissions_by_state_2023.csv**:
  - CO2 emissions by EUROCONTROL member state for the year 2023.
  - Source: [EUROCONTROL](https://ansperformance.eu/data/), accessed on 7.1.2025.
  - Google Drive file ID: `1XsuqMub8M3SdP50X1MIwAci-lsYS0X9t`
- **co2_emmissions_by_state.csv**:
  - CO2 emissions by EUROCONTROL member state since 2010.
  - Source: [EUROCONTROL](https://ansperformance.eu/data/), accessed on 8.1.2025.
  - Google Drive file ID: `1-FxcOXUXMrXZzDzeLgarKoQfa2QN_sXO`
- **iso_country_codes.json**:
  - Mapping of ISO 2 and 3 character country codes to country names and other information.
  - Source: [GitHub](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/tree/master), accessed on 8.1.2025.
  - Google Drive file ID: `1me9ab-d8k1H0RVIq72U85Lr0p4Q1yhWn`
- **icao_country.json**:
  - Mapping ICAO country codes to ISO 2 character country codes.
  - Source: Unfortunately, I couldn't find this mapping, so I created it with the [this script](data_prep_scripts/icao_country_mapping.ipynb).
  - Google Drive file ID: `17CMqyq43tBbMJ-TId4TH_GF2KskyIUPP`
- **world_population.csv**:
  - World population by country and year.
  - Source: [World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL), accessed on 9.1.2025.
  - Google Drive file ID: `1eWJVsEqM52xG-pLffdvkEy880oRsaTyz`
