# Obtaining Data

This directory includes instructions and scripts related to obtaining 311 data collected by New York City.

## Background

Anyone who wants to report a non-emergency problem or request information about government services in New York City can do so via 311.

A good constituent-facing website that allows for 311 requests is located at https://portal.311.nyc.gov/.  Frequently requested categories for 311 requests include things like:

* Noise from Neighbor
* Noise from Street or Sidewalk
* Apartment Maintenance Complaint
* Illegal Parking
* Wild Animal
* Sidewalk Grating Complaint
* Food Safety Complaint


## Data Access

This data is available on New York's Open Data website, at https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9.  Information on this page includes access to the dataset itself, access to a (partial) data dictionary, and metadata such as last updated date and the size of the dataset.

A side note about data size: this data contains tens of millions of rows.  It is advisable to access it using Socrata Open Data API (SODA) tools, which allow for selecting a certain number of rows only or selecting a subset of data according to column contents.  Socrata has many features that go beyond the scope of this introduction, but you can find out more at https://dev.socrata.com/.  
