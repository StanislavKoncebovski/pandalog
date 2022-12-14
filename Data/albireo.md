# Source
The data in albireo.csv are borrowed from http://www.astronexus.com/hyg 

(originally called there hygfull.csv). It contains all stars brighter than magnitude +9.0, or closer than 50 parsecs (87476 stars at the time of downloading.)

# Contents

| Value | Description |
|:---   | :---        |
| StarID | The database primary key from a larger "master database" of stars. |
| Hip    | The star's ID in the Hipparcos Catalog (https://en.wikipedia.org/wiki/Hipparcos#Hipparcos_Input_Catalogue). |
| HD     | The star's ID in the Henry Draper catalog, if known. |
| HR     | The star's ID in the Harvard Revised catalog, which is the same as its number in the Yale Bright Star Catalog. |
| Gliese | The star's ID in the third edition of the Gliese Catalog of Nearby Stars. |
| BayerFlamsteed |The Bayer / Flamsteed designation, from the Fifth Edition of the Yale Bright Star Catalog. This is a combination of the two designations. The Flamsteed number, if present, is given first; then a three-letter abbreviation for the Bayer Greek letter; the Bayer superscript number, if present; and finally, the three-letter constellation abbreviation. Thus Alpha Andromedae has the field value "21Alp And", and Kappa1 Sculptoris (no Flamsteed number) has "Kap1Scl". |
| ProperName | A common name for the star, such as "Barnard's Star" or "Sirius". I have taken these names primarily from the Hipparcos project's web site, which lists representative names for the 150 brightest stars and many of the 150 closest stars. I have added a few names to this list. Most of the additions are designations from catalogs mostly now forgotten (e.g., Lalande, Groombridge, and Gould ["G."]) except for certain nearby stars which are still best known by these designations. |
| RA    | The star's right ascension for epoch 2000.0. Stars present only in the Gliese Catalog, which uses 1950.0 coordinates, have had these coordinates precessed to 2000. |
| Dec   | Star's declination. (see comment for RA). |
| Distance | The star's distance in parsecs, the most common unit in astrometry. To convert parsecs to light years, multiply by 3.262. A value of 10000000 indicates missing or dubious (e.g., negative) parallax data in Hipparcos. |
| Mag | The star's apparent visual magnitude. |
| AbsMag | The star's absolute visual magnitude (its apparent magnitude from a distance of 10 parsecs). |
| Spectrum | The star's spectral type, if known. |
| ColorIndex | The star's color index (blue magnitude - visual magnitude), where known. |
