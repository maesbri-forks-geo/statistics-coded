statistics-coded
====================

 Resources for reproducing the outputs of _Eurostat_ Statistics Explained articles.
---

**About**

The code source files provided herein can be used to (re)produce some of the statistical results presented in _Eurostat_ [**Statistics Explained**](https://ec.europa.eu/eurostat/statistics-explained/index.php/Main_Page) articles. For some articles, the published figures can be directly generated using the open data disseminated on _Eurostat_ online database by running the available interactive computing notebooks.

<table align="center">
    <tr> <td align="left"><i>contributors</i></td> 
    <td align="left" valign="middle">
<a href="https://github.com/fmshka"><img src="https://github.com/fmshka.png" width="40"></a>
<a href="https://github.com/agnebik"><img src="https://github.com/agnebik.png" width="40"></a>
<a href="https://github.com/flopaleur"><img src="https://github.com/flopaleur.png" width="40"></a>
<a href="https://github.com/pierre-lamarche"><img src="https://github.com/pierre-lamarche.png" width="40"></a>
<a href="https://github.com/gjacopo"><img src="https://github.com/gjacopo.png" width="40"></a>
</td>  </tr> 
    <tr> <td align="left"><i>version</i></td> <td align="left">0.1</td> </tr> 
    <tr> <td align="left"><i>since</i></td> <td align="left">2019</td> </tr> 
    <tr> <td align="left"><i>license</i></td> <td align="left"><a href="https://joinup.ec.europa.eu/sites/default/files/eupl1.1.-licence-en_0.pdfEUPL">EUPL</a> <i></i></td> </tr> 
</table>

**Quick start**

**Run the notebooks (both `R` and `Python`) in [`binder`](https://mybinder.org/)**. Packages already installed to access Eurostat database.

 - Launch [`Jupyter`](https://jupyter.org/) alone:  [![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/eurostat/statistics-coded/master) <!--[![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/eurostat/statistics-coded/master?filepath=test.ipynb)-->
 - Launch [`JupyterLab`](https://jupyterlab.readthedocs.io/): [![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/eurostat/statistics-coded/master?urlpath=lab)
 - Launch [`RStudio`](https://rstudio.com/): [![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/eurostat/statistics-coded/master?urlpath=rstudio)
 
**Description**

The notebooks are organised according to the thematic structure already adopted for the Statistics Explained articles:

* [general/](general) for reproducing some of the Stastistics Explained articles on [_"General and regional statistics, EU policies"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=General_and_regional_statistics,_EU_policies),
* [economy/](economy) for [_"Economy and finance"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Economy_and_finance) articles,
* [**popul/**](popul) for [_"Population and social conditions"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Population_and_social_conditions) articles:

  * [notebook](https://github.com/eurostat/statistics-coded/blob/master/popul/young_people_social_inclusion/young-people-social-inclusion_R.ipynb) on [**young people and social inclusion**](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Young_people_-_social_inclusion),
  * [source code](https://github.com/eurostat/statistics-coded/tree/master/popul/income_consumption_wealth) for [**income, consumption and wealth**](https://ec.europa.eu/eurostat/web/experimental-statistics/income-consumption-and-wealth),
  * ...
* [**icts/**](icts) for [_"Industry and services"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Industry_and_services) articles:

  * [source code](https://github.com/eurostat/statistics-coded/tree/master/icts/multinational_enterprise_groups_SQL) for  [**structure of multinational enterprise groups in the EU**](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Structure_of_multinational_enterprise_groups_in_the_EU),
  * ...
* [agric/](agric) for [_"Agriculture, forestry and fisheries"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Agriculture,_forestry_and_fisheries) articles,
* [**external/**](external) for [_"International trade"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=International_trade) articles,
  * [notebook](https://github.com/eurostat/statistics-coded/tree/master/external/eu_int_trade_transport) for  [**EU international trade in transport services**](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=EU_international_trade_in_transport_services),
  * ...  
* [transp/](transp) for [_"Transport"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Transport),
* [envir/](envir) for [_"Environment and energy"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Environment_and_energy) articles,
* [science/](science) for [_"Science, technology and digital society"_](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Science,_technology_and_digital_society) articles.

**<a name="Resources"></a>Resources**

* _Eurostat_ [**online database**](https://ec.europa.eu/eurostat/data/database).
* **Statistics Explained** [main page](https://ec.europa.eu/eurostat/statistics-explained/index.php/Main_Page).
* `repo2docker` [configuration files](https://repo2docker.readthedocs.io/en/latest/config_files.html).
* `binder` [examples](https://github.com/binder-examples).
* `R` packages used to access open data from _Eurostat_: [`restatapi`](https://github.com/eurostat/restatapi) (via _SDMX_), [`eurostat`](http://ropengov.github.io/eurostat), [`rjstat`](https://github.com/ajschumacher/rjstat).
* `Python` packages used to access open data from _Eurostat_: [`jsonstat.py`](https://github.com/26fe/jsonstat.py), [`pandaSDMX`](https://github.com/dr-leo/pandaSDMX) (via _SDMX_), [`eurostatapiclient`](https://github.com/opus-42/eurostat-api-client), [`rsdmx`](https://github.com/opensdmx/rsdmx).
* [More](https://json-stat.org/tools/) on `JSON-stat` format and tools.
* Useful graphic tools galleries, in [`R`](https://www.r-graph-gallery.com/) and [`Python`](https://python-graph-gallery.com/).
* [**BBC Visual and Data Journalism cookbook for `R` graphics**](https://bbc.github.io/rcookbook/).

**<a name="References"></a>References**

* [**How Open Are Official Statistics?**](http://opendatawatch.com/monitoring-reporting/how-open-are-official-statistics/).
* Luhmann S., Grazzini J., Ricciato F., Meszaros M., Giannakouris K., Museux J.-M. and Hahn M. (2019): [**Promoting reproducibility-by-design in statistical offices**](https://www.researchgate.net/publication/332045930_Promoting_reproducibility-by-design_in_statistical_offices), in Proc. _New Techniques and Technologies for Statistics_, doi:[10.5281/zenodo.3240198](https://dx.doi.org/10.5281/zenodo.3240198).
* Grazzini J., Gaffuri J. and Museux J.-M. (2019): [**Delivering Official Statistics as Do-It-Yourself services to foster produsers' engagement with Eurostat open data**](https://www.researchgate.net/publication/332079417_Delivering_Official_Statistics_as_Do-It-Yourself_services_to_foster_produsers%27_engagement_with_Eurostat_open_data) in Proc. _New Techniques and Technologies for Statistics_, doi:[10.5281/zenodo.3240272](https://dx.doi.org/10.5281/zenodo.3240272).
* Grazzini J., Museux J.-M. and Hahn M. (2018): [**Empowering and interacting with statistical produsers: A practical example with Eurostat data as a service**](https://www.researchgate.net/publication/325973362_Empowering_and_interacting_with_statistical_produsers_a_practical_example_with_Eurostat_data_as_a_service), in Proc. _Conference of European Statistics Stakeholders_, doi:[10.5281/zenodo.3240557](https://dx.doi.org/10.5281/zenodo.3240557).
* Lahti L., Huovari J., Kainu M., and Biecek, P. (2017): [**Retrieval and analysis of Eurostat open data with the eurostat package**](https://journal.r-project.org/archive/2017/RJ-2017-019/RJ-2017-019.pdf), _The R Journal_, 9(1):385-392.
