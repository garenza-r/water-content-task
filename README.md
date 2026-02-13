# Water Content Analysis of Saarland and Mecklenburg-Vorpommern, 2024-2025
Water content analysis for 2024 and 2025 in Saarland and Mecklenburg-Vorpommern.

## Background
This work analyze the water content dynamics through the difference of remote sensing features between two different farming methods; _öko_ and _konvencionális_, across several areas in Mecklenburg-Vorpommern and Saarland between 2024-2025. The idea is to find any differences between _öko_ and _konvencionális_ by its water content and analyze patterns within the same crop code.

## Data and Methods
The data used in this work are Sentinel-1 SAR and Sentinel-2 MSI satellite images with time period between January 2024 until December 2025.

Several spectral indices are being used in this process, namely:
1. NDVI,
2. NDMI,
3. NDWI,
4. MSI, and
5. RVI.
  
NDVI, NDMI, NDWI, MSI from Sentinel-2, and RVI from Sentinel-1 are well-suited for detecting water content as they capture vegetation health, moisture, as well as structure influenced by irrigation. These indices incorporates water sensitive spectral indices, such as NIR and SWIR bands from multispectral images, as well as VV and VH radar backscatter to analyze the water content.

## Findings
For both years, many different crop codes with mutual appearances on both öko and konvencionális were found. In Mecklenburg-Vorpommern, 6 out of 8 crop codes appeared mutually in both the Mecklenburgische-Seenplatte and Ludwigslust-Parchim areas in 2024 and 2025. Meanwhile, in Saarland, for the year 2024, there are 64 out of 133, and for 2025, there are 73 out of 131 crop codes. Most of the codes show a similar pattern where when the values of NDVI, NDMI, and RVI rise, then the values of NDWI and MSI are the opposite. The rise of NDVI, NDMI, and RVI alongside low NDWI and MSI might point to healthy vegetation with low moisture stress and sufficient water content. The higher value of NDVI, NDMI, and RVI suggests strong enough chlorophyll activity and biomass density, as well as canopy structure and water content. This may also indicate plots with better soil moisture retention.
  
For most of the crop codes in öko farming methods, the value of NDMI is oftentimes a little bit higher than konvencionális. It might suggest that öko shows resilience and tends to store water better than konvencionális. However, the pattern of the spectral signature might be different. The period where each index value might rise or drop might be affected by the crop types, planting, and harvesting period.
  
For further results, see the codes attached.
