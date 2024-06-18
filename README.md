# nagap-aerial-glacier-photographs
Data for "Aerial Glacier Photographs": https://www.beautifulpublicdata.com/aerial-glacier-photographs/

Over 40 years, the USGS’ North American Glacier Aerial Photography (NAGAP) project captured thousands of striking high-resolution photos of glaciers and their surroundings. 

Researchers from University of Washington scanned around 20,000 of the 100,000 images in this collection, and they are hosted at the NSF [Arctic Data Center]( https://arcticdata.io/catalog/view/doi:10.18739/A2VH5CJ8K).

Research paper: "Historical Structure from Motion (HSfM): Automated processing of historical aerial photographs for long-term topographic change analysis", Knuth, et al. 2022.
https://doi.org/10.1016/j.rse.2022.113379

I've collected the list of files in this spreadsheet. 

Each photo has a thumbnail, a JPEG and a 16-bit greyscale TIFF. 

## URL structure for downloading
To download any of these files, you need to use the photo ID.

For example, to download `NAGAP_74V1_007.tif` you need its TIFF photo ID: `urn:uuid:53b0adfe-a567-4fde-9311-e90e622a591f`

So to download it you would use curl like this:

```
curl -o NAGAP_74V1_007.tif https://arcticdata.io/metacat/d1/mn/v2/object/urn:uuid:53b0adfe-a567-4fde-9311-e90e622a591f
```


## Data Dictionary
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: left;">
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
        <tr>
            <td><strong>Year</strong></td>
            <td>Yeah photo was taken</td>
        </tr>
        <tr>
            <td><strong>Roll</strong></td>
            <td>Film roll ID</td>
        </tr>
        <tr>
            <td><strong>fileName_tn</strong></td>
            <td>Filename of thumbnail</td>
        </tr>
        <tr>
            <td><strong>size_tn</strong></td>
            <td>Size of thumbnail (bytes)</td>
        </tr>
        <tr>
            <td><strong>pid_tn</strong></td>
            <td>Thumbnail photo ID</td>
        </tr>
        <tr>
            <td><strong>fileName_jpeg</strong></td>
            <td>JPEG filename</td>
        </tr>
        <tr>
            <td><strong>size_jpeg</strong></td>
            <td>Size of JPEG (bytes)</td>
        </tr>
        <tr>
            <td><strong>pid_jpeg</strong></td>
            <td>JPEG photo ID</td>
        </tr>
        <tr>
            <td><strong>fileName_tiff</strong></td>
            <td>TIFF filename</td>
        </tr>
        <tr>
            <td><strong>size_tiff</strong></td>
            <td>Size of TIFF (bytes)</td>
        </tr>
        <tr>
            <td><strong>pid_tiff</strong></td>
            <td>TIFF photo ID</td>
        </tr>
    </tbody>
</table>

    
  </tbody>
</table>