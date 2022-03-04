---
layout: default
---

# HTA CRC Atlas 1 primary data

V1.0 ReadMe

April 8, 2021

This data in this folder represent minimally processed (Level 2) image data
relevant to HMS HTAN Center CRC Atlas 1. Images are subjected to additional
quality control, segmentation and quantification to generate final data. Primary
image data files below are OME-TIFF tiled pyramid images, and spatial feature
tables are zipped CSV files. The total data size is 3.2 TB.

Data were collected using cyclic immunofluorescence as described in
<https://dx.doi.org/10.17504/protocols.io.bjiukkew>. Each file corresponds to a
multiplexed image mosaic for ~1.5 cm x ~1.5 cm FFPE tissue section 5 microns
thick. Each image is assembled from a series of ~400 successive megapixel image
tiles stitched together and flat-fielded using MCMICRO software to generate
whole-slide images each with ~10^9 pixels. Tiles were collected for each CyCIF
round (8 in total) and these are combined in the mosaic image to generate a
composite with 25 or more channels.

The data were collected on a RareCyte Inc. CyteFinder slide scanning
fluorescence microscope using a 20x 0.75 NA objective.

Files CRC01-001 to CRC01-106 derive from specimen CRC1, provided by the
Cooperative Human Tissue Network (CHTN) and resected from the cecum of a 69-year
old male; pathology revealed a poorly differentiated stage IIIB adenocarcinoma
(pT3N1bM0) with microsatellite instability (MSI-H) and a BRAFV600E (c.1799T>A)
mutation. The tumor had an extended front invading into the muscularis propria
and connective tissue.

Files CRC02 to CRC17 derive from additional patients from the Brigham and
Women’s Hospital.

Additional information on antibodies and specimen are available at
<https://labsyspharm.github.io/HTA-CRCATLAS-1/>.

All files below may be downloaded directly. For bulk downloads you may use wish
to use an Amazon Web Services S3 compatible download tool, connecting to the
following address:

`s3://lin-2021-crc-atlas/data/`

## OME-TIFF primary image data

* [CRC01-001](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-001.ome.tif) (12 GB)
* [CRC01-002](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-002.ome.tif) (88 GB)
* [CRC01-006](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-006.ome.tif) (11 GB)
* [CRC01-007](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-007.ome.tif) (80 GB)
* [CRC01-013](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-013.ome.tif) (11 GB)
* [CRC01-014](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-014.ome.tif) (72 GB)
* [CRC01-019](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-019.ome.tif) (12 GB)
* [CRC01-020](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-020.ome.tif) (83 GB)
* [CRC01-024](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-024.ome.tif) (11 GB)
* [CRC01-025](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-025.ome.tif) (83 GB)
* [CRC01-028](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-028.ome.tif) (10 GB)
* [CRC01-029](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-029.ome.tif) (74 GB)
* [CRC01-033](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-033.ome.tif) (11 GB)
* [CRC01-034](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-034.ome.tif) (82 GB)
* [CRC01-038](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-038.ome.tif) (11 GB)
* [CRC01-039](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-039.ome.tif) (80 GB)
* [CRC01-043](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-043.ome.tif) (11 GB)
* [CRC01-044](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-044.ome.tif) (76 GB)
* [CRC01-048](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-048.ome.tif) (11 GB)
* [CRC01-049](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-049.ome.tif) (76 GB)
* [CRC01-050](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-050.ome.tif) (80 GB)
* [CRC01-051](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-051.ome.tif) (76 GB)
* [CRC01-052](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-052.ome.tif) (80 GB)
* [CRC01-053](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-053.ome.tif) (10 GB)
* [CRC01-054](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-054.ome.tif) (74 GB)
* [CRC01-058](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-058.ome.tif) (10 GB)
* [CRC01-059](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-059.ome.tif) (80 GB)
* [CRC01-063](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-063.ome.tif) (10 GB)
* [CRC01-064](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-064.ome.tif) (74 GB)
* [CRC01-068](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-068.ome.tif) (10 GB)
* [CRC01-069](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-069.ome.tif) (69 GB)
* [CRC01-073](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-073.ome.tif) (9 GB)
* [CRC01-074](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-074.ome.tif) (69 GB)
* [CRC01-077](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-077.ome.tif) (10 GB)
* [CRC01-078](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-078.ome.tif) (69 GB)
* [CRC01-083](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-083.ome.tif) (9 GB)
* [CRC01-084](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-084.ome.tif) (69 GB)
* [CRC01-085](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-085.ome.tif) (10 GB)
* [CRC01-086](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-086.ome.tif) (72 GB)
* [CRC01-090](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-090.ome.tif) (9 GB)
* [CRC01-091](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-091.ome.tif) (72 GB)
* [CRC01-096](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-096.ome.tif) (10 GB)
* [CRC01-097](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-097.ome.tif) (74 GB)
* [CRC01-101](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-101.ome.tif) (10 GB)
* [CRC01-102](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-102.ome.tif) (72 GB)
* [CRC01-105](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-105.ome.tif) (9 GB)
* [CRC01-106](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-106.ome.tif) (69 GB)
* [CRC02](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC02.ome.tif) (93 GB)
* [CRC03](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC03.ome.tif) (72 GB)
* [CRC04](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC04.ome.tif) (70 GB)
* [CRC05](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC05.ome.tif) (54 GB)
* [CRC06](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC06.ome.tif) (74 GB)
* [CRC07](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC07.ome.tif) (61 GB)
* [CRC08](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC08.ome.tif) (86 GB)
* [CRC09](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC09.ome.tif) (68 GB)
* [CRC10](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC10.ome.tif) (62 GB)
* [CRC11](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC11.ome.tif) (59 GB)
* [CRC12](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC12.ome.tif) (76 GB)
* [CRC13](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC13.ome.tif) (49 GB)
* [CRC14](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC14.ome.tif) (75 GB)
* [CRC15](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC15.ome.tif) (75 GB)
* [CRC16](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC16.ome.tif) (81 GB)
* [CRC17](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC17.ome.tif) (79 GB)

## Spatial feature tables (CSV)

* [CRC01-002](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-002-features.zip) (46 MB)
* [CRC01-007](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-007-features.zip) (45 MB)
* [CRC01-014](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-014-features.zip) (41 MB)
* [CRC01-020](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-020-features.zip) (38 MB)
* [CRC01-025](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-025-features.zip) (39 MB)
* [CRC01-029](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-029-features.zip) (41 MB)
* [CRC01-034](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-034-features.zip) (54 MB)
* [CRC01-039](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-039-features.zip) (45 MB)
* [CRC01-044](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-044-features.zip) (36 MB)
* [CRC01-049](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-049-features.zip) (52 MB)
* [CRC01-050](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-050-features.zip) (49 MB)
* [CRC01-051](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-051-features.zip) (60 MB)
* [CRC01-052](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-052-features.zip) (55 MB)
* [CRC01-054](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-054-features.zip) (49 MB)
* [CRC01-059](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-059-features.zip) (46 MB)
* [CRC01-064](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-064-features.zip) (57 MB)
* [CRC01-069](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-069-features.zip) (48 MB)
* [CRC01-074](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-074-features.zip) (56 MB)
* [CRC01-078](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-078-features.zip) (54 MB)
* [CRC01-084](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-084-features.zip) (56 MB)
* [CRC01-086](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-086-features.zip) (55 MB)
* [CRC01-091](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-091-features.zip) (49 MB)
* [CRC01-097](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-097-features.zip) (55 MB)
* [CRC01-102](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-102-features.zip) (55 MB)
* [CRC01-106](https://lin-2021-crc-atlas.s3.amazonaws.com/data/WD-76845-106-features.zip) (53 MB)
* [CRC02](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC02-features.zip) (58 MB)
* [CRC03](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC03-features.zip) (50 MB)
* [CRC04](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC04-features.zip) (75 MB)
* [CRC05](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC05-features.zip) (57 MB)
* [CRC06](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC06-features.zip) (39 MB)
* [CRC07](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC07-features.zip) (51 MB)
* [CRC08](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC08-features.zip) (67 MB)
* [CRC09](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC09-features.zip) (22 MB)
* [CRC10](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC10-features.zip) (41 MB)
* [CRC11](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC11-features.zip) (34 MB)
* [CRC12](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC12-features.zip) (69 MB)
* [CRC13](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC13-features.zip) (24 MB)
* [CRC14](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC14-features.zip) (32 MB)
* [CRC15](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC15-features.zip) (56 MB)
* [CRC16](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC16-features.zip) (22 MB)
* [CRC17](https://lin-2021-crc-atlas.s3.amazonaws.com/data/CRC17-features.zip) (79 MB)
