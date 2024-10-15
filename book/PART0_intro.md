# Welcome to the Course!

The objective of the course is "How to make publishable netCDF data".

NetCDF is one of the most widely used scientific data formats in the earth system science (ESS). This course targets at scientists who want to share their research data in an interoperable way, and aims at providing a systematic guide on creating publishable netCDF data.

The CF Conventions have a wide range of regulations and recommendations on netCDF data structure and metadata formatting. This course aims at making the adoptation of the metadata standard easier for users and focuses on the highly needed aspects which we also see as the core aspect; It is not covering every aspect of the CF Conventions. For advanced users, the CF Conventions documentation provides a more comprehensive reference. But for beginners, following this tutorial should be sufficient for producing netCDF datasets conforming to the CF Conventions.

In this course we will learn:

1. [What is netCDF?](01_netcdf_101.ipynb)
2. [Introducing Xarray](03_xr_intro.ipynb): Handle netCDF using xarray; we wanna show what xarray is capable (interact with other tools thus well integratable into data processing workflows), as an argument why we'll use this tool to show how to create netCDF file and standardize the metadata.
3. [What is the CF Conventions?](02_cf_101.ipynb)

4. create grid netcdf from scratch + DWD example
4. [How to generate a grid netCDF file conforming to the CF Conventions?](04_cf_grid_dwd.ipynb)

5. [How to generate a DSG netCDF file conforming to the CF Conventions?](05_cf_dsg.ipynb): Getting to know DSG, create point netCDF from scratch.
6. [DSG: Point](06_dsg_point.ipynb)
7. [DSG: Time Series](07_dsg_timeSeries.ipynb)
8. [DSG: Profile & Time Series of Profiles](08_dsg_profile.ipynb)
9. [DSG: Trajectory & Trajectory of Profiles](09_dsg_trajectory.ipynb)
10. [Sample solution to a few exercise ]


Add a final chapter to test if one of the generated netCDF (pick one with complex structure, like trajectory of profiles?) is readable by many softwares?