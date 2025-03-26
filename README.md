# Key Indicators of Customer Satisfaction for Android Devices

<b> The data </b>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>battery</th>
      <th>camera</th>
      <th>display</th>
      <th>memory</th>
      <th>name</th>
      <th>price</th>
      <th>processor</th>
      <th>rating</th>
      <th>reviews</th>
      <th>warranty</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>5000 mAh Battery</td>
      <td>12MP + 2MP | 8MP Front Camera</td>
      <td>15.8 cm (6.22 inch) HD+ Display</td>
      <td>4 GB RAM | 64 GB ROM | Expandable Upto 512 GB</td>
      <td>Redmi 8 (Ruby Red, 64 GB)</td>
      <td>9999</td>
      <td>Qualcomm Snapdragon 439 Processor</td>
      <td>4.4</td>
      <td>55,078 Reviews</td>
      <td>Brand Warranty of 1 Year Available for Mobile and 6 Months for Accessories</td>
    </tr>
    <tr>
      <td>5000 mAh Battery</td>
      <td>12MP + 8MP + 2MP + 2MP | 8MP Front Camera</td>
      <td>16.56 cm (6.52 inch) HD+ Display</td>
      <td>4 GB RAM | 64 GB ROM</td>
      <td>Realme 5i (Aqua Blue, 64 GB)</td>
      <td>10999</td>
      <td>Qualcomm Snapdragon 665 2 GHz Processor</td>
      <td>4.5</td>
      <td>20,062 Reviews</td>
      <td>Sunrise Design</td>
    </tr>
    <tr>
      <td>5000 mAh Battery</td>
      <td>12MP + 8MP + 2MP + 2MP | 8MP Front Camera</td>
      <td>16.56 cm (6.52 inch) HD+ Display</td>
      <td>4 GB RAM | 128 GB ROM</td>
      <td>Realme 5i (Aqua Blue, 128 GB)</td>
      <td>11999</td>
      <td>Qualcomm Snapdragon 665 (2 GHz) Processor</td>
      <td>4.5</td>
      <td>20,062 Reviews</td>
      <td>Sunrise Design</td>
    </tr>
  </tbody>
</table>

The dataset consists of the <b>market performance metrics</b> (price, rating, and reviews) and various <b>device specifications</b> (battery, camera, display etc) of 984 android devices sold on the e-commerce website Flipkart. This analysis provides insights into how various factors influence customer satisfaction.
- The dataset only includes products listed on Flipkart and may not represent the entire Android market
- Before analysis, the dataset underwent wrangling to remove inconsistencies and to fine tune the information contained in each column
- Since the dataset lacks a direct "customer satisfaction" variable, ratings conditioned on a significant number of reviews was chosen as a proxy metric
- Justification for the chosen metric through theoretical knowledge and data evidence is provided

You can view the Jupyter Notebook here:
https://github.com/Teohhanyang/Android-Devices-Analysis/blob/main/Key%20Indicators%20of%20Customer%20Satisfaction%20for%20Adroid%20Devices.ipynb 
