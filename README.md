Download Link: https://assignmentchef.com/product/solved-stat-292-assignment-4
<br>
There are four questions, worth a total of 100 marks. Question 1 starts on page 2.

<h1>Assignment Guidelines (once more)</h1>

You are encouraged to discuss assignments with other students, but your submitted work must be your own.

The following Assignment Guidelines are helpful for all the assignments in Parts 2 and 3 of the course.

When you carry out a statistical test of hypothesis, you should state the following, <strong>when relevant</strong>:

<ul>

 <li>Model equation.</li>

 <li>Assumptions about the data, and comments about whether diagnostic graphs support those assumptions.</li>

 <li>Null and alternative hypotheses.</li>

 <li>ANOVA Table (if relevant), <em>p</em>-values.</li>

 <li>Statistical conclusions. For example, “We reject H<sub>0 </sub>and conclude H<em><sub>A</sub></em>, that <em>µ</em><sub>1 </sub>and <em>µ</em><sub>2 </sub>differ at the 5% significance level”.</li>

 <li>Interpretation of the statistical conclusions back to the original problem, using the original meaning of the response variable and any factors or covariates. For example, if comparing heights of two groups, “Female and male adults have different mean heights, with males being taller on average”.</li>

</ul>

<em>Assignment Guidelines</em>

<h2>1. Comprehension Test</h2>

Children in a school class are given a test of comprehension of English, marked out of 100. The children are from three different ethnic groups, which is thought to be an important factor. The question of interest is whether there are sex differences after allowing for ethnicity. The data follow:

<table width="575">

 <tbody>

  <tr>

   <td width="126"> </td>

   <td width="197">Females</td>

   <td width="253">Males</td>

  </tr>

  <tr>

   <td rowspan="3" width="126">Ethnic group E1 E2E3</td>

   <td width="197">67 66 75 76 71 70 72</td>

   <td width="253">63 72 62 61 69 64 71 68 56</td>

  </tr>

  <tr>

   <td width="197">69 57 55 63 65 55</td>

   <td width="253">59 47 49</td>

  </tr>

  <tr>

   <td width="197">30 47</td>

   <td width="253">39 33</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>A two-way ANOVA was run on the data, with SAS output given on pages 3 to 6. Present the results from the ANOVA following the usual Assignment Guidelines, as given on page 1.</li>

 <li>If a one-way ANOVA is done with factor Sex, the resulting ANOVA table is:</li>

</ul>

<table width="457">

 <tbody>

  <tr>

   <td width="61">Source</td>

   <td width="38">DF</td>

   <td width="122">Sum of Squares</td>

   <td width="105">Mean Square</td>

   <td width="66">F value</td>

   <td width="64"><em>p</em>-value</td>

  </tr>

  <tr>

   <td width="61">Sex</td>

   <td width="38">1</td>

   <td width="122">144.166</td>

   <td width="105">144.166</td>

   <td width="66">0.99</td>

   <td width="64">0.3292</td>

  </tr>

  <tr>

   <td width="61">Error</td>

   <td width="38">27</td>

   <td width="122">3942.662</td>

   <td width="105">146.025</td>

   <td width="66"> </td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="61">Total</td>

   <td width="38">28</td>

   <td width="122">4086.828</td>

   <td width="105"> </td>

   <td width="66"> </td>

   <td width="64"> </td>

  </tr>

 </tbody>

</table>

Briefly discuss the outcomes of the separate tests for Sex presented in parts (a) and (b). Are the conclusions different? Give reasons to explain your answer.

<h2>                                        SAS Output for Comprehension Test</h2>

<strong> </strong>

<strong>Linear Models  </strong>




<strong>The GLM Procedure </strong>




<table width="163">

 <tbody>

  <tr>

   <td colspan="3" width="163"><strong>Class Level Information </strong></td>

  </tr>

  <tr>

   <td width="59"><strong>Class </strong></td>

   <td width="42"><strong>Levels</strong></td>

   <td width="62"><strong> Values </strong></td>

  </tr>

  <tr>

   <td width="59">Ethnicity</td>

   <td width="42">3</td>

   <td width="62"> E1 E2 E3</td>

  </tr>

  <tr>

   <td width="59">Sex</td>

   <td width="42">2</td>

   <td width="62"> F M</td>

  </tr>

 </tbody>

</table>




<table width="212">

 <tbody>

  <tr>

   <td width="196">Number of Observations Read</td>

   <td width="17"> 29</td>

  </tr>

  <tr>

   <td width="196">Number of Observations Used</td>

   <td width="17">29</td>

  </tr>

 </tbody>

</table>







<table width="605">

 <tbody>

  <tr>

   <td width="246"><strong>Dependent Variable: Comprehension   </strong></td>

   <td width="359"><strong> </strong></td>

  </tr>

 </tbody>

</table>




<table width="400">

 <tbody>

  <tr>

   <td width="101"><strong>Source </strong></td>

   <td width="18"><strong>DF</strong></td>

   <td width="102"><strong> Sum of Squares</strong></td>

   <td width="84"><strong>Mean Square</strong></td>

   <td width="48"><strong> F Value</strong></td>

   <td width="46"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="101">Model</td>

   <td width="18">5</td>

   <td width="102">    3365.438697</td>

   <td width="84">673.087739</td>

   <td width="48"> 21.46</td>

   <td width="46">&lt;.0001</td>

  </tr>

  <tr>

   <td width="101">Error</td>

   <td width="18">23</td>

   <td width="102">      721.388889</td>

   <td width="84">31.364734</td>

   <td width="48"> </td>

   <td width="46"> </td>

  </tr>

  <tr>

   <td width="101">Corrected Total</td>

   <td width="18">28</td>

   <td width="102">    4086.827586</td>

   <td width="84"> </td>

   <td width="48"> </td>

   <td width="46"> </td>

  </tr>

 </tbody>

</table>




<table width="330">

 <tbody>

  <tr>

   <td width="62"><strong>R-Square</strong></td>

   <td width="62"><strong> Coeff Var</strong></td>

   <td width="65"><strong> Root MSE</strong></td>

   <td width="141"><strong>Comprehension Mean</strong></td>

  </tr>

  <tr>

   <td width="62">0.823484</td>

   <td width="62"> 9.275400</td>

   <td width="65"> 5.600423</td>

   <td width="141">60.37931</td>

  </tr>

 </tbody>

</table>




<table width="373">

 <tbody>

  <tr>

   <td width="91"><strong>Source </strong></td>

   <td width="18"><strong>DF</strong></td>

   <td width="85"><strong>      Type I SS</strong></td>

   <td width="85"><strong> Mean Square</strong></td>

   <td width="48"><strong> F Value</strong></td>

   <td width="46"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="91">Ethnicity</td>

   <td width="18">2</td>

   <td width="85"> 3060.640086</td>

   <td width="85"> 1530.320043</td>

   <td width="48"> 48.79</td>

   <td width="46">&lt;.0001</td>

  </tr>

  <tr>

   <td width="91">Sex</td>

   <td width="18">1</td>

   <td width="85"> 275.113176</td>

   <td width="85"> 275.113176</td>

   <td width="48">     8.77</td>

   <td width="46">0.0070</td>

  </tr>

  <tr>

   <td width="91">Ethnicity*Sex</td>

   <td width="18">2</td>

   <td width="85">    29.685435</td>

   <td width="85">    14.842718</td>

   <td width="48">     0.47</td>

   <td width="46">0.6289</td>

  </tr>

 </tbody>

</table>










<h3>                                        SAS Output for Comprehension Test</h3>

<strong> </strong>

<strong>Linear Models  </strong>




<strong>The GLM Procedure </strong>

1










<h3>                                        SAS Output for Comprehension Test</h3>













<h3>                                        SAS Output for Comprehension Test</h3>










Note: E1 is the top line, E2 the middle line and E3 the lowest. (The lines are different colours, but that doesn’t show up if viewed or printed in black and white.)

<h4>2. Invertebrates in Mussel Clumps</h4>

The following data are from Peake and Quinn (1993), Temporal variation in speciesarea curves for invertebrates in clumps of an intertidal mussel, <em>Ecography </em><strong>16</strong>, 269277. The two variables used in this question are:

<em>x </em>= log<sub>10</sub>(Area) of each of 25 mussel clumps (in dm<sup>2</sup>), and

<em>Y </em>= number of different species of macroinvertebrates in each clump.

<em>Note: Using log(Area) gives a straighter regression line than Area, which is why it is used. This is a transformation of x, not Y ; it has been done to improve linearity, not to stabilise variances.</em>

The data follow. Decide if there is a useful linear relationship between <em>x </em>and <em>Y </em>, i.e. if <em>x </em>is a useful linear predictor of <em>Y </em>.

<table width="195">

 <tbody>

  <tr>

   <td width="70">Clump</td>

   <td width="68">logArea</td>

   <td width="57">Species</td>

  </tr>

  <tr>

   <td width="70">1</td>

   <td width="68">2.71</td>

   <td width="57">3</td>

  </tr>

  <tr>

   <td width="70">2</td>

   <td width="68">2.67</td>

   <td width="57">7</td>

  </tr>

  <tr>

   <td width="70">3</td>

   <td width="68">2.66</td>

   <td width="57">6</td>

  </tr>

  <tr>

   <td width="70">4</td>

   <td width="68">2.97</td>

   <td width="57">8</td>

  </tr>

  <tr>

   <td width="70">5</td>

   <td width="68">3.13</td>

   <td width="57">10</td>

  </tr>

  <tr>

   <td width="70">6</td>

   <td width="68">3.25</td>

   <td width="57">9</td>

  </tr>

  <tr>

   <td width="70">7</td>

   <td width="68">3.23</td>

   <td width="57">10</td>

  </tr>

  <tr>

   <td width="70">8</td>

   <td width="68">3.25</td>

   <td width="57">11</td>

  </tr>

  <tr>

   <td width="70">9</td>

   <td width="68">3.49</td>

   <td width="57">16</td>

  </tr>

  <tr>

   <td width="70">10</td>

   <td width="68">3.60</td>

   <td width="57">9</td>

  </tr>

  <tr>

   <td width="70">11</td>

   <td width="68">3.65</td>

   <td width="57">13</td>

  </tr>

  <tr>

   <td width="70">12</td>

   <td width="68">3.65</td>

   <td width="57">14</td>

  </tr>

  <tr>

   <td width="70">13</td>

   <td width="68">3.70</td>

   <td width="57">12</td>

  </tr>

  <tr>

   <td width="70">14</td>

   <td width="68">3.65</td>

   <td width="57">14</td>

  </tr>

  <tr>

   <td width="70">15</td>

   <td width="68">3.74</td>

   <td width="57">20</td>

  </tr>

  <tr>

   <td width="70">16</td>

   <td width="68">3.87</td>

   <td width="57">22</td>

  </tr>

  <tr>

   <td width="70">17</td>

   <td width="68">3.85</td>

   <td width="57">15</td>

  </tr>

  <tr>

   <td width="70">18</td>

   <td width="68">3.96</td>

   <td width="57">20</td>

  </tr>

  <tr>

   <td width="70">19</td>

   <td width="68">4.01</td>

   <td width="57">22</td>

  </tr>

  <tr>

   <td width="70">20</td>

   <td width="68">3.97</td>

   <td width="57">21</td>

  </tr>

  <tr>

   <td width="70">21</td>

   <td width="68">4.14</td>

   <td width="57">15</td>

  </tr>

  <tr>

   <td width="70">22</td>

   <td width="68">4.31</td>

   <td width="57">24</td>

  </tr>

  <tr>

   <td width="70">23</td>

   <td width="68">4.39</td>

   <td width="57">25</td>

  </tr>

  <tr>

   <td width="70">24</td>

   <td width="68">4.43</td>

   <td width="57">25</td>

  </tr>

  <tr>

   <td width="70">25</td>

   <td width="68">4.42</td>

   <td width="57">24</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>A scatterplot of the data is given on page 8. Give comments on whether youthink the plot shows (i) linearity, (ii) constant variance.</li>

 <li>Output from a simple linear regression using logArea to predict the numberof species is given on pages 9 and 10. Present a report on this analysis that includes (as usual) the model equation, hypotheses, assumptions, comments on whether the analysis is valid, plus statistical conclusions and interpretation.</li>

</ul>

<h4>                                         SAS Output for Mussel Clumps</h4>







<strong>Scatter Plot  </strong>










<h2>                                         SAS Output for Mussel Clumps</h2>




<strong>Linear Regression Results  </strong>




<strong>The REG Procedure </strong>

<strong> </strong>

<strong>Model: Linear_Regression_Model </strong>

<strong> </strong>

<strong>Dependent Variable: Species  </strong>




<table width="212">

 <tbody>

  <tr>

   <td width="196">Number of Observations Read</td>

   <td width="17"> 25</td>

  </tr>

  <tr>

   <td width="196">Number of Observations Used</td>

   <td width="17">25</td>

  </tr>

 </tbody>

</table>




<table width="359">

 <tbody>

  <tr>

   <td colspan="6" width="359"><strong>Analysis of Variance </strong></td>

  </tr>

  <tr>

   <td width="101"><strong>Source </strong></td>

   <td width="18"><strong>DF</strong></td>

   <td width="77"><strong>Sum of</strong><strong>Squares</strong></td>

   <td width="69"><strong>         Mean</strong><strong>      Square</strong></td>

   <td width="48"><strong> </strong><strong> F Value</strong></td>

   <td width="46"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="101">Model</td>

   <td width="18">1</td>

   <td width="77">868.50179</td>

   <td width="69"> 868.50179</td>

   <td width="48"> 117.85</td>

   <td width="46">&lt;.0001</td>

  </tr>

  <tr>

   <td width="101">Error</td>

   <td width="18">23</td>

   <td width="77">169.49821</td>

   <td width="69">    7.36949</td>

   <td width="48"> </td>

   <td width="46"> </td>

  </tr>

  <tr>

   <td width="101">Corrected Total</td>

   <td width="18"> 24</td>

   <td width="77">1038.00000</td>

   <td width="69"> </td>

   <td width="48"> </td>

   <td width="46"> </td>

  </tr>

 </tbody>

</table>




<table width="277">

 <tbody>

  <tr>

   <td width="111">Root MSE</td>

   <td width="61">2.71468</td>

   <td width="62"> R-Square</td>

   <td width="45"> 0.8367</td>

  </tr>

  <tr>

   <td width="111">Dependent Mean</td>

   <td width="61"> 15.00000</td>

   <td width="62"> Adj R-Sq</td>

   <td width="45"> 0.8296</td>

  </tr>

  <tr>

   <td width="111">Coeff Var</td>

   <td width="61">18.09787</td>

   <td width="62"> </td>

   <td width="45"> </td>

  </tr>

 </tbody>

</table>




<table width="290">

 <tbody>

  <tr>

   <td colspan="6" width="290"><strong>Parameter Estimates </strong></td>

  </tr>

  <tr>

   <td width="57"><strong>Variable </strong></td>

   <td width="18"><strong>DF</strong></td>

   <td width="66"><strong>Parameter</strong><strong> Estimate</strong></td>

   <td width="58"><strong> Standard</strong><strong>       Error</strong></td>

   <td width="44"><strong> </strong><strong> t Value</strong></td>

   <td width="46"><strong> Pr &gt; |t|</strong></td>

  </tr>

  <tr>

   <td width="57">Intercept</td>

   <td width="18"> 1</td>

   <td width="66"> -25.64136</td>

   <td width="58"> 3.78287</td>

   <td width="44"> -6.78</td>

   <td width="46"> &lt;.0001</td>

  </tr>

  <tr>

   <td width="57">logArea</td>

   <td width="18">1</td>

   <td width="66"> 11.20214</td>

   <td width="58"> 1.03189</td>

   <td width="44"> 10.86</td>

   <td width="46"> &lt;.0001</td>

  </tr>

 </tbody>

</table>










<h2>                                         SAS Output for Mussel Clumps</h2>




<strong>Linear Regression Results  </strong>



















<h3>3. Coarse Woody Debris in Lakes</h3>

Christensen <em>et al. </em>(1996, <em>Ecological Applications </em><strong>6(4)</strong>, 1143-1149) studied the relationships between coarse woody debris (CWD), shoreline vegetation and lake development in a sample of 16 lakes in North America. Coarse woody debris is useful in providing a habitat for various fish species. It is known to be related to the riparian (river-bank, lake-edge) tree density, irrespective of whether or not humans are present. The objective is to find out whether, after allowing for riparian tree density, human habitation is having an effect on the CWD.

The variables below were taken around the shoreline and near-shore water:

L10CABIN = log<sub>10 </sub>of 1 + density of cabins (number km<sup>−1</sup>),

RIP.DENS = density of riparian trees (trees km<sup>−1</sup>), and CWD.BASA = basal area of coarse woody debris (m<sup>2 </sup>km<sup>−1</sup>).

<table width="437">

 <tbody>

  <tr>

   <td width="91">LAKE</td>

   <td width="61">AREA</td>

   <td width="90">RIP.DENS</td>

   <td width="103">CWD.BASA</td>

   <td width="93">L10CABIN</td>

  </tr>

  <tr>

   <td width="91">Bay</td>

   <td width="61">69</td>

   <td width="90">1270</td>

   <td width="103">121</td>

   <td width="93">0</td>

  </tr>

  <tr>

   <td width="91">Bergner</td>

   <td width="61">9</td>

   <td width="90">1210</td>

   <td width="103">41</td>

   <td width="93">0</td>

  </tr>

  <tr>

   <td width="91">Crampton</td>

   <td width="61">24</td>

   <td width="90">1800</td>

   <td width="103">183</td>

   <td width="93">0</td>

  </tr>

  <tr>

   <td width="91">Long</td>

   <td width="61">8</td>

   <td width="90">1875</td>

   <td width="103">130</td>

   <td width="93">0</td>

  </tr>

  <tr>

   <td width="91">Roach</td>

   <td width="61">20</td>

   <td width="90">1300</td>

   <td width="103">127</td>

   <td width="93">0</td>

  </tr>

  <tr>

   <td width="91">Tenderfoot</td>

   <td width="61">175</td>

   <td width="90">2150</td>

   <td width="103">134</td>

   <td width="93">0.20412</td>

  </tr>

  <tr>

   <td width="91">Palmer</td>

   <td width="61">254</td>

   <td width="90">1330</td>

   <td width="103">65</td>

   <td width="93">0.462398</td>

  </tr>

  <tr>

   <td width="91">Street</td>

   <td width="61">22</td>

   <td width="90">964</td>

   <td width="103">52</td>

   <td width="93">0.6627578</td>

  </tr>

  <tr>

   <td width="91">Laura</td>

   <td width="61">240</td>

   <td width="90">961</td>

   <td width="103">12</td>

   <td width="93">0.7075702</td>

  </tr>

  <tr>

   <td width="91">Annabelle</td>

   <td width="61">85</td>

   <td width="90">1400</td>

   <td width="103">46</td>

   <td width="93">0.763428</td>

  </tr>

  <tr>

   <td width="91">Joyce</td>

   <td width="61">12</td>

   <td width="90">1280</td>

   <td width="103">54</td>

   <td width="93">0.845098</td>

  </tr>

  <tr>

   <td width="91">Lake hills</td>

   <td width="61">25</td>

   <td width="90">976</td>

   <td width="103">97</td>

   <td width="93">0.8864907</td>

  </tr>

  <tr>

   <td width="91">Towanda</td>

   <td width="61">58</td>

   <td width="90">771</td>

   <td width="103">1</td>

   <td width="93">1.10721</td>

  </tr>

  <tr>

   <td width="91">Black oak</td>

   <td width="61">234</td>

   <td width="90">833</td>

   <td width="103">4</td>

   <td width="93">1.1238516</td>

  </tr>

  <tr>

   <td width="91">Johnson</td>

   <td width="61">31</td>

   <td width="90">883</td>

   <td width="103">1</td>

   <td width="93">1.2552725</td>

  </tr>

  <tr>

   <td width="91">Arrowhead</td>

   <td width="61">40</td>

   <td width="90">956</td>

   <td width="103">4</td>

   <td width="93">1.40824</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Let <em>Y </em>= CWD.BASA, <em>X</em><sub>1 </sub>= RIP.DENS and <em>X</em><sub>2 </sub>= L10CABIN. Plots of <em>Y </em> <em>X</em><sub>1</sub>, <em>Y </em>vs. <em>X</em><sub>2 </sub>and <em>X</em><sub>1 </sub>vs. <em>X</em><sub>2 </sub>are given on page 12. Comment on any relationships you see.</li>

 <li>SAS output for the following models is presented on pages 13 to 16. Diagnosticgraphs are shown for the last model.</li>

</ul>

<ol>

 <li>Regression of <em>Y </em>on the predictor <em>X</em><sub>1 </sub>ii. Regression of <em>Y </em>on the predictor <em>X</em><sub>2</sub></li>

</ol>

iii. Regression of <em>Y </em>on the two predictors <em>X</em><sub>1 </sub>and <em>X</em><sub>2</sub>

For each analysis above, present the model equation, hypotheses and conclusions. For the third analysis, comment on whether or not the model assumptions are satisfied.

<ul>

 <li>Which of the hypothesis tests from the three presented models gives the answerto the question of interest in this situation? Explain the answer.</li>

</ul>

L10CABIN                                                                                   RIP.DENS

L10CABIN

<em>Scatterplots: CWD by L10CABIN, CWD by RIP.DENS, RIP.DENS by L10CABIN</em>

<h2>                               Coarse Woody Debris        SAS Output</h2>







<h3>Linear Regression Results</h3>

<strong>The REG Procedure </strong>

<strong> </strong>

<strong>Model: Linear_Regression_Model </strong>

<strong> </strong>

<strong>Dependent Variable: CWD.BASA  </strong>




<table width="213">

 <tbody>

  <tr>

   <td colspan="3" width="67"> </td>

   <td colspan="11" width="194"><strong>Number of Observations Read</strong></td>

   <td colspan="2" width="19">16</td>

   <td colspan="5" width="67"> </td>

  </tr>

  <tr>

   <td colspan="3" width="67"> </td>

   <td colspan="11" width="194"><strong>Number of Observations Used</strong></td>

   <td colspan="2" width="19">16</td>

   <td colspan="5" width="67"> </td>

  </tr>

  <tr>

   <td colspan="21" width="347"><strong>Analysis of Variance </strong></td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Source </strong></td>

   <td colspan="2" width="21"><strong>DF</strong></td>

   <td colspan="3" width="56"><strong>Sum of Squares</strong></td>

   <td colspan="3" width="74"><strong>Mean Square</strong></td>

   <td colspan="5" width="51"><strong>F Value</strong></td>

   <td colspan="3" width="44"><strong>Pr &gt; F </strong></td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Model </strong></td>

   <td colspan="2" width="21">1</td>

   <td colspan="3" width="56">32054</td>

   <td colspan="3" width="74">32054</td>

   <td colspan="5" width="51">24.30</td>

   <td colspan="3" width="44">0.0002</td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Error </strong></td>

   <td colspan="2" width="21">14</td>

   <td colspan="3" width="56">18466</td>

   <td colspan="3" width="74">1318.96866</td>

   <td colspan="5" width="51"> </td>

   <td colspan="3" width="44"> </td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Corrected Total</strong></td>

   <td colspan="2" width="21"><strong> </strong>15</td>

   <td colspan="3" width="56">50520</td>

   <td colspan="3" width="74"> </td>

   <td colspan="5" width="51"> </td>

   <td colspan="3" width="44"> </td>

  </tr>

  <tr>

   <td colspan="2" width="36"> </td>

   <td colspan="6" width="109"><strong>Root MSE </strong></td>

   <td colspan="3" width="60">36.31761</td>

   <td colspan="4" width="62"><strong>R-Square</strong></td>

   <td colspan="4" width="45">0.6345</td>

   <td colspan="2" width="35"> </td>

  </tr>

  <tr>

   <td colspan="2" width="36"> </td>

   <td colspan="6" width="109"><strong>Dependent Mean</strong></td>

   <td colspan="3" width="60">67.00000</td>

   <td colspan="4" width="62"><strong>Adj R-Sq</strong></td>

   <td colspan="4" width="45">0.6084</td>

   <td colspan="2" width="35"> </td>

  </tr>

  <tr>

   <td colspan="2" width="36"> </td>

   <td colspan="6" width="109"><strong>Coeff Var </strong></td>

   <td colspan="3" width="60">54.20539</td>

   <td colspan="4" width="62"><strong>  </strong></td>

   <td colspan="4" width="45"> </td>

   <td colspan="2" width="35"> </td>

  </tr>

  <tr>

   <td width="20"> </td>

   <td colspan="19" width="308"><strong>Parameter Estimates </strong></td>

   <td width="19"> </td>

  </tr>

  <tr>

   <td width="20"> </td>

   <td colspan="3" width="66"><strong>Variable </strong></td>

   <td colspan="2" width="21"><strong>DF</strong></td>

   <td colspan="3" width="69"><strong>Parameter Estimate</strong></td>

   <td colspan="3" width="61"><strong>Standard Error</strong></td>

   <td colspan="5" width="47"><strong>t Value</strong></td>

   <td colspan="3" width="44"><strong>Pr &gt; |t|</strong></td>

   <td width="19"> </td>

  </tr>

  <tr>

   <td width="20"> </td>

   <td colspan="3" width="66"><strong>Intercept </strong></td>

   <td colspan="2" width="21">1</td>

   <td colspan="3" width="69">-77.09908</td>

   <td colspan="3" width="61">30.60801</td>

   <td colspan="5" width="47">-2.52</td>

   <td colspan="3" width="44">0.0246</td>

   <td width="19"> </td>

  </tr>

  <tr>

   <td width="20"> </td>

   <td colspan="3" width="66"><strong>RIP.DENS</strong></td>

   <td colspan="2" width="21"><strong> </strong>1</td>

   <td colspan="3" width="69">0.11552</td>

   <td colspan="3" width="61">0.02343</td>

   <td colspan="5" width="47">4.93</td>

   <td colspan="3" width="44">0.0002</td>

   <td width="19"> </td>

  </tr>

  <tr>

   <td width="11"></td>

   <td width="16"></td>

   <td width="31"></td>

   <td width="18"></td>

   <td width="16"></td>

   <td width="5"></td>

   <td width="16"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="3"></td>

   <td width="26"></td>

   <td width="31"></td>

   <td width="16"></td>

   <td width="9"></td>

   <td width="5"></td>

   <td width="13"></td>

   <td width="3"></td>

   <td width="20"></td>

   <td width="8"></td>

   <td width="16"></td>

   <td width="19"></td>

  </tr>

 </tbody>

</table>




<h3>Linear Regression Results</h3>

<strong>The REG Procedure </strong>

<strong> </strong>

<strong>Model: Linear_Regression_Model </strong>

<strong> </strong>

<strong>Dependent Variable: CWD.BASA  </strong>




<table width="213">

 <tbody>

  <tr>

   <td colspan="3" width="67"> </td>

   <td colspan="11" width="194"><strong>Number of Observations Read</strong></td>

   <td colspan="2" width="19">16</td>

   <td colspan="5" width="67"> </td>

  </tr>

  <tr>

   <td colspan="3" width="67"> </td>

   <td colspan="11" width="194"><strong>Number of Observations Used</strong></td>

   <td colspan="2" width="19">16</td>

   <td colspan="5" width="67"> </td>

  </tr>

  <tr>

   <td colspan="21" width="347"><strong>Analysis of Variance </strong></td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Source </strong></td>

   <td colspan="2" width="21"><strong>DF</strong></td>

   <td colspan="3" width="56"><strong>Sum of Squares</strong></td>

   <td colspan="3" width="74"><strong>Mean Square</strong></td>

   <td colspan="5" width="51"><strong>F Value</strong></td>

   <td colspan="3" width="44"><strong>Pr &gt; F </strong></td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Model </strong></td>

   <td colspan="2" width="21">1</td>

   <td colspan="3" width="56">32840</td>

   <td colspan="3" width="74">32840</td>

   <td colspan="5" width="51">26.00</td>

   <td colspan="3" width="44">0.0002</td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Error </strong></td>

   <td colspan="2" width="21">14</td>

   <td colspan="3" width="56">17680</td>

   <td colspan="3" width="74">1262.86950</td>

   <td colspan="5" width="51"> </td>

   <td colspan="3" width="44"> </td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Corrected Total</strong></td>

   <td colspan="2" width="21"><strong> </strong>15</td>

   <td colspan="3" width="56">50520</td>

   <td colspan="3" width="74"> </td>

   <td colspan="5" width="51"> </td>

   <td colspan="3" width="44"> </td>

  </tr>

  <tr>

   <td colspan="2" width="36"> </td>

   <td colspan="6" width="109"><strong>Root MSE </strong></td>

   <td colspan="3" width="60">35.53688</td>

   <td colspan="4" width="62"><strong>R-Square</strong></td>

   <td colspan="4" width="45">0.6500</td>

   <td colspan="2" width="35"> </td>

  </tr>

  <tr>

   <td colspan="2" width="36"> </td>

   <td colspan="6" width="109"><strong>Dependent Mean</strong></td>

   <td colspan="3" width="60">67.00000</td>

   <td colspan="4" width="62"><strong>Adj R-Sq</strong></td>

   <td colspan="4" width="45">0.6250</td>

   <td colspan="2" width="35"> </td>

  </tr>

  <tr>

   <td colspan="2" width="36"> </td>

   <td colspan="6" width="109"><strong>Coeff Var </strong></td>

   <td colspan="3" width="60">53.04011</td>

   <td colspan="4" width="62"><strong>  </strong></td>

   <td colspan="4" width="45"> </td>

   <td colspan="2" width="35"> </td>

  </tr>

  <tr>

   <td width="18"> </td>

   <td colspan="19" width="310"><strong>Parameter Estimates </strong></td>

   <td width="18"> </td>

  </tr>

  <tr>

   <td width="18"> </td>

   <td colspan="3" width="68"><strong>Variable </strong></td>

   <td colspan="2" width="21"><strong>DF</strong></td>

   <td colspan="3" width="69"><strong>Parameter Estimate</strong></td>

   <td colspan="3" width="61"><strong>Standard Error</strong></td>

   <td colspan="5" width="47"><strong>t Value</strong></td>

   <td colspan="3" width="44"><strong>Pr &gt; |t|</strong></td>

   <td width="18"> </td>

  </tr>

  <tr>

   <td width="18"> </td>

   <td colspan="3" width="68"><strong>Intercept </strong></td>

   <td colspan="2" width="21">1</td>

   <td colspan="3" width="69">121.96875</td>

   <td colspan="3" width="61">13.96871</td>

   <td colspan="5" width="47">8.73</td>

   <td colspan="3" width="44">&lt;.0001</td>

   <td width="18"> </td>

  </tr>

  <tr>

   <td width="18"> </td>

   <td colspan="3" width="68"><strong>L10CABIN</strong></td>

   <td colspan="2" width="21"><strong> </strong>1</td>

   <td colspan="3" width="69">-93.30142</td>

   <td colspan="3" width="61">18.29646</td>

   <td colspan="5" width="47">-5.10</td>

   <td colspan="3" width="44">0.0002</td>

   <td width="18"> </td>

  </tr>

  <tr>

   <td width="11"></td>

   <td width="18"></td>

   <td width="31"></td>

   <td width="19"></td>

   <td width="15"></td>

   <td width="6"></td>

   <td width="15"></td>

   <td width="23"></td>

   <td width="30"></td>

   <td width="2"></td>

   <td width="26"></td>

   <td width="32"></td>

   <td width="15"></td>

   <td width="9"></td>

   <td width="5"></td>

   <td width="13"></td>

   <td width="4"></td>

   <td width="19"></td>

   <td width="8"></td>

   <td width="17"></td>

   <td width="18"></td>

  </tr>

 </tbody>

</table>










<h3>Linear Regression Results</h3>

<strong>The REG Procedure </strong>

<strong> </strong>

<strong>Model: Linear_Regression_Model </strong>

<strong> </strong>

<strong>Dependent Variable: CWD.BASA  </strong>




<table width="213">

 <tbody>

  <tr>

   <td colspan="3" width="63"> </td>

   <td colspan="11" width="194"><strong>Number of Observations Read</strong></td>

   <td colspan="2" width="19">16</td>

   <td colspan="5" width="63"> </td>

  </tr>

  <tr>

   <td colspan="3" width="63"> </td>

   <td colspan="11" width="194"><strong>Number of Observations Used</strong></td>

   <td colspan="2" width="19">16</td>

   <td colspan="5" width="63"> </td>

  </tr>

  <tr>

   <td colspan="21" width="340"><strong>Analysis of Variance </strong></td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Source </strong></td>

   <td colspan="2" width="21"><strong>DF</strong></td>

   <td colspan="3" width="56"><strong>Sum of Squares</strong></td>

   <td colspan="3" width="66"><strong>Mean Square</strong></td>

   <td colspan="5" width="51"><strong>F Value</strong></td>

   <td colspan="3" width="44"><strong>Pr &gt; F </strong></td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Model </strong></td>

   <td colspan="2" width="21">2</td>

   <td colspan="3" width="56">38041</td>

   <td colspan="3" width="66">19020</td>

   <td colspan="5" width="51">19.81</td>

   <td colspan="3" width="44">0.0001</td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Error </strong></td>

   <td colspan="2" width="21">13</td>

   <td colspan="3" width="56">12479</td>

   <td colspan="3" width="66">959.93185</td>

   <td colspan="5" width="51"> </td>

   <td colspan="3" width="44"> </td>

  </tr>

  <tr>

   <td colspan="5" width="101"><strong>Corrected Total</strong></td>

   <td colspan="2" width="21"><strong> </strong>15</td>

   <td colspan="3" width="56">50520</td>

   <td colspan="3" width="66"> </td>

   <td colspan="5" width="51"> </td>

   <td colspan="3" width="44"> </td>

  </tr>

  <tr>

   <td colspan="2" width="32"> </td>

   <td colspan="6" width="109"><strong>Root MSE </strong></td>

   <td colspan="3" width="60">30.98277</td>

   <td colspan="4" width="62"><strong>R-Square</strong></td>

   <td colspan="4" width="45">0.7530</td>

   <td colspan="2" width="32"> </td>

  </tr>

  <tr>

   <td colspan="2" width="32"> </td>

   <td colspan="6" width="109"><strong>Dependent Mean</strong></td>

   <td colspan="3" width="60">67.00000</td>

   <td colspan="4" width="62"><strong>Adj R-Sq</strong></td>

   <td colspan="4" width="45">0.7150</td>

   <td colspan="2" width="32"> </td>

  </tr>

  <tr>

   <td colspan="2" width="32"> </td>

   <td colspan="6" width="109"><strong>Coeff Var </strong></td>

   <td colspan="3" width="60">46.24294</td>

   <td colspan="4" width="62"><strong>  </strong></td>

   <td colspan="4" width="45"> </td>

   <td colspan="2" width="32"> </td>

  </tr>

  <tr>

   <td width="15"> </td>

   <td colspan="19" width="310"><strong>Parameter Estimates </strong></td>

   <td width="15"> </td>

  </tr>

  <tr>

   <td width="15"> </td>

   <td colspan="3" width="68"><strong>Variable </strong></td>

   <td colspan="2" width="21"><strong>DF</strong></td>

   <td colspan="3" width="69"><strong>Parameter Estimate</strong></td>

   <td colspan="3" width="61"><strong>Standard Error</strong></td>

   <td colspan="5" width="47"><strong>t Value</strong></td>

   <td colspan="3" width="44"><strong>Pr &gt; |t|</strong></td>

   <td width="15"> </td>

  </tr>

  <tr>

   <td width="15"> </td>

   <td colspan="3" width="68"><strong>Intercept </strong></td>

   <td colspan="2" width="21">1</td>

   <td colspan="3" width="69">18.16485</td>

   <td colspan="3" width="61">46.22822</td>

   <td colspan="5" width="47">0.39</td>

   <td colspan="3" width="44">0.7007</td>

   <td width="15"> </td>

  </tr>

  <tr>

   <td width="15"> </td>

   <td colspan="3" width="68"><strong>RIP.DENS </strong></td>

   <td colspan="2" width="21">1</td>

   <td colspan="3" width="69">0.06572</td>

   <td colspan="3" width="61">0.02823</td>

   <td colspan="5" width="47">2.33</td>

   <td colspan="3" width="44">0.0367</td>

   <td width="15"> </td>

  </tr>

  <tr>

   <td width="15"> </td>

   <td colspan="3" width="68"><strong>L10CABIN</strong></td>

   <td colspan="2" width="21"><strong> </strong>1</td>

   <td colspan="3" width="69">-56.26481</td>

   <td colspan="3" width="61">22.53059</td>

   <td colspan="5" width="47">-2.50</td>

   <td colspan="3" width="44">0.0267</td>

   <td width="15"> </td>

  </tr>

  <tr>

   <td width="9"></td>

   <td width="18"></td>

   <td width="31"></td>

   <td width="19"></td>

   <td width="19"></td>

   <td width="2"></td>

   <td width="19"></td>

   <td width="19"></td>

   <td width="30"></td>

   <td width="6"></td>

   <td width="23"></td>

   <td width="32"></td>

   <td width="11"></td>

   <td width="13"></td>

   <td width="5"></td>

   <td width="13"></td>

   <td width="4"></td>

   <td width="15"></td>

   <td width="12"></td>

   <td width="17"></td>

   <td width="15"></td>

  </tr>

 </tbody>

</table>













<h4>4. Age of Teeth</h4>

In forensic work, scientists estimate the age of a skeleton by counting teeth cementum annulation (i.e. growth rings). Two teeth preparation methods, A and B, are compared by estimating the ages (<em>Y </em>) of twenty teeth of known age (<em>X</em>). The teeth are randomly allocated to the two methods, ten to each, as follows.

<table width="537">

 <tbody>

  <tr>

   <td width="94">Method A</td>

   <td width="136"><em>X </em>= true age</td>

   <td width="40">49</td>

   <td width="32">13</td>

   <td width="32">38</td>

   <td width="32">55</td>

   <td width="32">44</td>

   <td width="32">56</td>

   <td width="24">7</td>

   <td width="32">66</td>

   <td width="32">18</td>

   <td width="24">39</td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="136"><em>Y </em>= estimated age</td>

   <td width="40">50</td>

   <td width="32">14</td>

   <td width="32">38</td>

   <td width="32">57</td>

   <td width="32">44</td>

   <td width="32">55</td>

   <td width="24">7</td>

   <td width="32">63</td>

   <td width="32">20</td>

   <td width="24">38</td>

  </tr>

  <tr>

   <td width="94">Method B</td>

   <td width="136"><em>X </em>= true age</td>

   <td width="40">51</td>

   <td width="32">59</td>

   <td width="32">32</td>

   <td width="32">37</td>

   <td width="32">12</td>

   <td width="32">38</td>

   <td width="24">4</td>

   <td width="32">28</td>

   <td width="32">58</td>

   <td width="24">24</td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="136"><em>Y </em>= estimated age</td>

   <td width="40">51</td>

   <td width="32">59</td>

   <td width="32">29</td>

   <td width="32">34</td>

   <td width="32">10</td>

   <td width="32">35</td>

   <td width="24">5</td>

   <td width="32">25</td>

   <td width="32">57</td>

   <td width="24">22</td>

  </tr>

 </tbody>

</table>

A confirmatory analysis using a model with terms True Age (i.e. <em>X</em>), Method and True Age×Method is required.

<ul>

 <li>Give the model equation for the required confirmatory analysis.</li>

 <li>SAS output from a fitted model is given on pages 18 to 20. Present a report on this analysis that includes any necessary assumptions, comments on their validity, hypotheses, statistical conclusions at a 5% significance level, and interpretation plus discussion.</li>

</ul>







<h3>Linear Models</h3>




<strong>The GLM Procedure </strong>




<table width="166">

 <tbody>

  <tr>

   <td colspan="3" width="166"><strong>Class Level Information</strong></td>

  </tr>

  <tr>

   <td width="61"><strong>Class </strong></td>

   <td width="52"><strong>Levels</strong></td>

   <td width="54"><strong> Values </strong></td>

  </tr>

  <tr>

   <td colspan="3" width="166">Method            2 A B</td>

  </tr>

 </tbody>

</table>




<table width="235">

 <tbody>

  <tr>

   <td width="216">Number of Observations Read</td>

   <td width="19"> 20</td>

  </tr>

  <tr>

   <td width="216">Number of Observations Used</td>

   <td width="19"> 20</td>

  </tr>

 </tbody>

</table>







<table width="665">

 <tbody>

  <tr>

   <td width="169"><strong>Dependent Variable: Y   </strong></td>

   <td width="496"><strong> </strong></td>

  </tr>

 </tbody>

</table>




<table width="445">

 <tbody>

  <tr>

   <td width="112"><strong>Source </strong></td>

   <td width="21"><strong>DF</strong></td>

   <td width="113"><strong> Sum of Squares</strong></td>

   <td width="94"><strong>Mean Square</strong></td>

   <td width="54"><strong> F Value</strong></td>

   <td width="51"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="112">Model</td>

   <td width="21">3</td>

   <td width="113">     6543.664660</td>

   <td width="94"> 2181.221553</td>

   <td width="54"> 946.16</td>

   <td width="51">&lt;.0001</td>

  </tr>

  <tr>

   <td width="112">Error</td>

   <td width="21">16</td>

   <td width="113">         36.885340</td>

   <td width="94">       2.305334</td>

   <td width="54"> </td>

   <td width="51"> </td>

  </tr>

  <tr>

   <td width="112">Corrected Total</td>

   <td width="21">19</td>

   <td width="113">     6580.550000</td>

   <td width="94"> </td>

   <td width="54"> </td>

   <td width="51"> </td>

  </tr>

 </tbody>

</table>




<table width="270">

 <tbody>

  <tr>

   <td width="67"><strong>R-Square</strong></td>

   <td width="67"><strong>Coeff Var</strong></td>

   <td width="71"><strong> Root MSE</strong></td>

   <td width="66"><strong> Y Mean</strong></td>

  </tr>

  <tr>

   <td colspan="4" width="270">0.994395 4.258997 1.518333 35.65000</td>

  </tr>

 </tbody>

</table>




<table width="396">

 <tbody>

  <tr>

   <td width="77"><strong>Source </strong></td>

   <td width="21"><strong>DF</strong></td>

   <td width="94"><strong>       Type I SS</strong></td>

   <td width="94"><strong> Mean Square</strong></td>

   <td width="59"><strong> F Value</strong></td>

   <td width="51"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="77">X</td>

   <td width="21">1</td>

   <td width="94"> 6525.535206</td>

   <td width="94"> 6525.535206</td>

   <td width="59"> 2830.62</td>

   <td width="51">&lt;.0001</td>

  </tr>

  <tr>

   <td width="77">Method</td>

   <td width="21">1</td>

   <td width="94">    15.413619</td>

   <td width="94">    15.413619</td>

   <td width="59">       6.69</td>

   <td width="51">0.0199</td>

  </tr>

  <tr>

   <td width="77">X*Method</td>

   <td width="21">1</td>

   <td width="94">       2.715836</td>

   <td width="94">      2.715836</td>

   <td width="59">       1.18</td>

   <td width="51">0.2938</td>

  </tr>

 </tbody>

</table>




<table width="396">

 <tbody>

  <tr>

   <td width="77"><strong>Source </strong></td>

   <td width="21"><strong>DF</strong></td>

   <td width="94"><strong>     Type III SS</strong></td>

   <td width="94"><strong> Mean Square</strong></td>

   <td width="59"><strong> F Value</strong></td>

   <td width="51"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="77">X</td>

   <td width="21">1</td>

   <td width="94"> 6350.006837</td>

   <td width="94"> 6350.006837</td>

   <td width="59"> 2754.48</td>

   <td width="51">&lt;.0001</td>

  </tr>

  <tr>

   <td width="77">Method</td>

   <td width="21">1</td>

   <td width="94">    10.463729</td>

   <td width="94">    10.463729</td>

   <td width="59">       4.54</td>

   <td width="51">0.0490</td>

  </tr>

  <tr>

   <td width="77">X*Method</td>

   <td width="21">1</td>

   <td width="94">       2.715836</td>

   <td width="94">      2.715836</td>

   <td width="59">       1.18</td>

   <td width="51">0.2938</td>

  </tr>

 </tbody>

</table>
















Data and fitted lines: Method A line (dashed) is above Method B line (solid)

True age