Download Link: https://assignmentchef.com/product/solved-machinelearning-assignment-1
<br>



<ul>

 <li><strong>Problem 1</strong></li>

</ul>

Import the numpy package under the name np

Create a vector or 1D array with 10 zeros and print it

Find the memory size of this array

[ ]: array([0., 0., 0., 0., 0., 0., 0., 0., 0., 0.])

[ ]: print(“The Size of the array is”, arr.itemsize*arr.size, “Bytes”)

The Size of the array is 80 Bytes

<ul>

 <li><strong>Problem 2:</strong></li>

</ul>

Create another vector or 1D array with values ranging from 10 to 20

Reverse the created vector (first element becomes last) — Is there any NumPy method that you can use?

[ ]: array([10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20])

[ ]: array([20, 19, 18, 17, 16, 15, 14, 13, 12, 11, 10])

<ul>

 <li><strong>Problem 3:</strong></li>

</ul>

Create a 3×4 array with random values (standard normal distribution) and find the minimum and maximum values

[ ]: array([[8672, 9272, 6342],

[3784, 5232, 7887],

[5001, 4270, 3926],

[6843, 5154, 7836]])

[ ]: arr3.max()

[ ]: 9272

[ ]: arr3.min()

[ ]: 3784

<ul>

 <li><strong>Problem 4:</strong></li>

</ul>

Given the following 1D array, negate all elements which are between 3 and 8, in place. (include both 3 and 8 in conditional statements)

<h1>[ ]: Z</h1>

[ ]: array([ 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10])

[ ]: array([ 0, 1, 2, -3, -4, -5, -6, -7, -8, 9, 10])

Given the 1D array Z, find the closest value to the given scalar v?

<h1>[ ]: Z</h1>

[ ]: array([ 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21,

22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38,

39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55,

56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72,

73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89,

90, 91, 92, 93, 94, 95, 96, 97, 98, 99])

Closet Value is %d 33

Subtract the mean of each row of the following matrix

␣

<em>,</em><sub>→</sub>—————————————————————————

NameError                                                                    Traceback (most recent call␣

<em>,</em><sub>→</sub>last)

&lt;ipython-input-1-3b30b7c6267b&gt; in &lt;module&gt;() —-&gt; 1 np.random.seed(2)

<ul>

 <li>X = np.random.rand(3, 4)</li>

 <li>print(X)</li>

</ul>

NameError: name ‘np’ is not defined

[ ]: array([[0.3617265 , 0.3617265 , 0.3617265 , 0.3617265 ],

[0.39365556, 0.39365556, 0.39365556, 0.39365556],

[0.42918947, 0.42918947, 0.42918947, 0.42918947]])

[[ 0.0742684 -0.33580027 0.18793598 0.07359589] [ 0.02671225 -0.06332073 -0.18900692 0.22561541]

[-0.1295348 -0.16236219 0.19194436 0.09995263]]

Timing comparison for multiplication of 4 arrays. Find the fastest way to compute the multiplication ABCD. Make sure you report the elapsed time. (hint: you can find relevant information at https://youtu.be/SeBRHg9ZrSs) Complete the following:

<strong>5    Problem 5</strong>

Import and print the file ’parks.csv’ (Park Code should be the index column)

&lt;IPython.core.display.HTML object&gt;

[ ]:                                                                                               Park Name         … Longitude

Park Code                                                                                                    …

<table width="565">

 <tbody>

  <tr>

   <td width="85">ACAD</td>

   <td colspan="2" width="427">                                                     Acadia National Park           …</td>

   <td width="53">-68.21</td>

  </tr>

  <tr>

   <td width="85">ARCH</td>

   <td colspan="2" width="427">                                                     Arches National Park           …</td>

   <td width="53">-109.57</td>

  </tr>

  <tr>

   <td width="85">BADL</td>

   <td colspan="2" width="427">Badlands National Park …</td>

   <td width="53">-102.50</td>

  </tr>

  <tr>

   <td width="85">BIBE</td>

   <td colspan="2" width="427">Big Bend National Park …</td>

   <td width="53">-103.25</td>

  </tr>

  <tr>

   <td width="85">BISC</td>

   <td colspan="2" width="427">Biscayne National Park …</td>

   <td width="53">-80.08</td>

  </tr>

  <tr>

   <td width="85">BLCA</td>

   <td colspan="2" width="427">              Black Canyon of the Gunnison National Park              …</td>

   <td width="53">-107.72</td>

  </tr>

  <tr>

   <td width="85">BRCA</td>

   <td colspan="2" width="427">                                          Bryce Canyon National Park           …</td>

   <td width="53">-112.18</td>

  </tr>

  <tr>

   <td width="85">CANY</td>

   <td colspan="2" width="427">                                            Canyonlands National Park           …</td>

   <td width="53">-109.93</td>

  </tr>

  <tr>

   <td width="85">CARE</td>

   <td colspan="2" width="427">                                           Capitol Reef National Park            …</td>

   <td width="53">-111.17</td>

  </tr>

  <tr>

   <td width="85">CAVE</td>

   <td colspan="2" width="427">                                   Carlsbad Caverns National Park            …</td>

   <td width="53">-104.44</td>

  </tr>

  <tr>

   <td width="85">CHIS</td>

   <td colspan="2" width="427">                                      Channel Islands National Park             …</td>

   <td width="53">-119.42</td>

  </tr>

  <tr>

   <td width="85">CONG</td>

   <td colspan="2" width="427">Congaree National Park …</td>

   <td width="53">-80.78</td>

  </tr>

  <tr>

   <td width="85">CRLA</td>

   <td colspan="2" width="427">                                            Crater Lake National Park            …</td>

   <td width="53">-122.10</td>

  </tr>

  <tr>

   <td width="85">CUVA</td>

   <td colspan="2" width="427">                                     Cuyahoga Valley National Park            …</td>

   <td width="53">-81.55</td>

  </tr>

  <tr>

   <td width="85">DENA</td>

   <td width="373">Denali National Park and Preserve</td>

   <td width="53">…</td>

   <td width="53">-150.50</td>

  </tr>

  <tr>

   <td width="85">DEVA</td>

   <td width="373">Death Valley National Park</td>

   <td width="53">…</td>

   <td width="53">-116.82</td>

  </tr>

  <tr>

   <td width="85">DRTO</td>

   <td width="373">Dry Tortugas National Park</td>

   <td width="53">…</td>

   <td width="53">-82.87</td>

  </tr>

  <tr>

   <td width="85">EVER</td>

   <td width="373">Everglades National Park</td>

   <td width="53">…</td>

   <td width="53">-80.93</td>

  </tr>

  <tr>

   <td width="85">GAAR</td>

   <td width="373">Gates Of The Arctic National Park and Preserve</td>

   <td width="53">…</td>

   <td width="53">-153.30</td>

  </tr>

  <tr>

   <td width="85">GLAC</td>

   <td width="373">Glacier National Park</td>

   <td width="53">…</td>

   <td width="53">-114.00</td>

  </tr>

  <tr>

   <td width="85">GLBA</td>

   <td width="373">Glacier Bay National Park and Preserve</td>

   <td width="53">…</td>

   <td width="53">-137.00</td>

  </tr>

  <tr>

   <td width="85">GRBA</td>

   <td width="373">Great Basin National Park</td>

   <td width="53">…</td>

   <td width="53">-114.30</td>

  </tr>

  <tr>

   <td width="85">GRCA</td>

   <td width="373">Grand Canyon National Park</td>

   <td width="53">…</td>

   <td width="53">-112.14</td>

  </tr>

  <tr>

   <td width="85">GRSA</td>

   <td width="373">Great Sand Dunes National Park and Preserve</td>

   <td width="53">…</td>

   <td width="53">-105.51</td>

  </tr>

  <tr>

   <td width="85">GRSM</td>

   <td width="373">Great Smoky Mountains National Park</td>

   <td width="53">…</td>

   <td width="53">-83.53</td>

  </tr>

  <tr>

   <td width="85">GRTE</td>

   <td width="373">Grand Teton National Park</td>

   <td width="53">…</td>

   <td width="53">-110.80</td>

  </tr>

  <tr>

   <td width="85">GUMO</td>

   <td width="373">Guadalupe Mountains National Park</td>

   <td width="53">…</td>

   <td width="53">-104.87</td>

  </tr>

  <tr>

   <td width="85">HALE</td>

   <td width="373">Haleakala National Park</td>

   <td width="53">…</td>

   <td width="53">-156.17</td>

  </tr>

  <tr>

   <td width="85">HAVO</td>

   <td width="373">Hawaii Volcanoes National Park</td>

   <td width="53">…</td>

   <td width="53">-155.20</td>

  </tr>

  <tr>

   <td width="85">HOSP</td>

   <td width="373">Hot Springs National Park</td>

   <td width="53">…</td>

   <td width="53">-93.05</td>

  </tr>

  <tr>

   <td width="85">ISRO</td>

   <td width="373">Isle Royale National Park</td>

   <td width="53">…</td>

   <td width="53">-88.55</td>

  </tr>

  <tr>

   <td width="85">JOTR</td>

   <td width="373">Joshua Tree National Park</td>

   <td width="53">…</td>

   <td width="53">-115.90</td>

  </tr>

  <tr>

   <td width="85">KATM</td>

   <td width="373">Katmai National Park and Preserve</td>

   <td width="53">…</td>

   <td width="53">-155.00</td>

  </tr>

  <tr>

   <td width="85">KEFJ</td>

   <td width="373">Kenai Fjords National Park</td>

   <td width="53">…</td>

   <td width="53">-149.65</td>

  </tr>

  <tr>

   <td width="85">KOVA</td>

   <td width="373">Kobuk Valley National Park</td>

   <td width="53">…</td>

   <td width="53">-159.28</td>

  </tr>

  <tr>

   <td width="85">LACL</td>

   <td width="373">Lake Clark National Park and Preserve</td>

   <td width="53">…</td>

   <td width="53">-153.42</td>

  </tr>

  <tr>

   <td width="85">LAVO</td>

   <td width="373">Lassen Volcanic National Park</td>

   <td width="53">…</td>

   <td width="53">-121.51</td>

  </tr>

  <tr>

   <td width="85">MACA</td>

   <td width="373">Mammoth Cave National Park</td>

   <td width="53">…</td>

   <td width="53">-86.10</td>

  </tr>

  <tr>

   <td width="85">MEVE</td>

   <td width="373">Mesa Verde National Park</td>

   <td width="53">…</td>

   <td width="53">-108.49</td>

  </tr>

  <tr>

   <td width="85">MORA</td>

   <td width="373">Mount Rainier National Park</td>

   <td width="53">…</td>

   <td width="53">-121.75</td>

  </tr>

  <tr>

   <td width="85">NOCA</td>

   <td width="373">North Cascades National Park</td>

   <td width="53">…</td>

   <td width="53">-121.20</td>

  </tr>

  <tr>

   <td width="85">OLYM</td>

   <td width="373">Olympic National Park</td>

   <td width="53">…</td>

   <td width="53">-123.50</td>

  </tr>

  <tr>

   <td width="85">PEFO</td>

   <td width="373">Petrified Forest National Park</td>

   <td width="53">…</td>

   <td width="53">-109.78</td>

  </tr>

  <tr>

   <td width="85">PINN</td>

   <td width="373">Pinnacles National Park</td>

   <td width="53">…</td>

   <td width="53">-121.16</td>

  </tr>

  <tr>

   <td width="85">REDW</td>

   <td width="373">Redwood National Park</td>

   <td width="53">…</td>

   <td width="53">-124.00</td>

  </tr>

  <tr>

   <td width="85">ROMO</td>

   <td width="373">Rocky Mountain National Park</td>

   <td width="53">…</td>

   <td width="53">-105.58</td>

  </tr>

  <tr>

   <td width="85">SAGU</td>

   <td width="373">Saguaro National Park</td>

   <td width="53">…</td>

   <td width="53">-110.50</td>

  </tr>

  <tr>

   <td width="85">SEKI</td>

   <td width="373">Sequoia and Kings Canyon National Parks</td>

   <td width="53">…</td>

   <td width="53">-118.68</td>

  </tr>

  <tr>

   <td width="85">SHEN</td>

   <td width="373">Shenandoah National Park</td>

   <td width="53">…</td>

   <td width="53">-78.35</td>

  </tr>

  <tr>

   <td width="85">THRO</td>

   <td width="373">Theodore Roosevelt National Park</td>

   <td width="53">…</td>

   <td width="53">-103.45</td>

  </tr>

  <tr>

   <td width="85">VOYA</td>

   <td width="373">Voyageurs National Park</td>

   <td width="53">…</td>

   <td width="53">-92.88</td>

  </tr>

  <tr>

   <td width="85">WICA</td>

   <td width="373">Wind Cave National Park</td>

   <td width="53">…</td>

   <td width="53">-103.48</td>

  </tr>

  <tr>

   <td width="85">WRST</td>

   <td width="373">Wrangell – St Elias National Park and Preserve</td>

   <td width="53">…</td>

   <td width="53">-142.00</td>

  </tr>

  <tr>

   <td width="85">YELL</td>

   <td width="373">Yellowstone National Park</td>

   <td width="53">…</td>

   <td width="53">-110.50</td>

  </tr>

  <tr>

   <td width="85">YOSE</td>

   <td colspan="2" width="427">Yosemite National Park …</td>

   <td width="53">-119.50</td>

  </tr>

  <tr>

   <td width="85">ZION</td>

   <td colspan="2" width="427">                                                        Zion National Park           …</td>

   <td width="53">-113.05</td>

  </tr>

 </tbody>

</table>

[56 rows x 5 columns]

Print all column names

[ ]: list(parks.columns) [‘Park Name ‘, ‘State ‘, ‘Acres ‘, ‘Latitude ‘, ‘Longitude ‘] Make sure tha all letters are lower case and replace space with _

[ ]: parks = parks.astype(str).apply(<strong>lambda </strong>x: x.str.lower())

[ ]: parks = parks.astype(str).apply(<strong>lambda </strong>x: x.str.rstrip())

[ ]: parks = parks.astype(str).apply(<strong>lambda </strong>x: x.str.replace(‘ ‘,’_’))

[ ]: parks[“State “] = parks[“State “].apply(<strong>lambda </strong>state: state.replace(‘_’,”)) Which state has the smallest national park?

[ ]: 5550

[ ]:                                                       Park Name State               Acres Latitude Longitude

Park Code

HOSP                 hot_springs_national_park              ar        5550          34.51           -93.05

State is Arkansas

Produce a histogram plot that shows the distribution of ’acres’.

[ ]:<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/272.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/272.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>