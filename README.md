# BigQueries documentation

**BigQueries** is a framework for data warehouse physical design to optimize big number of analytical queries. It is a modular tool, that can: (1) offers DBA the possibility to select different optimization structures (MV, HDP), based on the interaction of queries, (2) gives an estimation of the queries performance, (3) generates and display an unified query plan, (4) and gives partition schema and fragments allocation in parallel processing context.

## Requirements

BigQueries does not require advanced configuration hardware. However, for a more flexible use, we recommend to use a maximum of memory in order to accelerate graph partitioning of the hypergraph representing queries workload.

### Operating Systems Requirements

The framework is developed with java environment, Windows and Linux operating systems are supported (The framework is tested on Windows 8, Windows 7 and Ubuntu).

### Software Requirements

Before executing the BigQueries tool, ensure the java environment have been installed on your computer.

Data warehouse schema and statistics are get it directly from the DBMS or preformatted file. So, you need to have an access to your database.

## Download

All EnerQuery project files can be downloaded at https://github.com/lias-laboratory/bigqueries/releases

## Installation

* Unpack the archive (interphase-1.x.zip) in a target directory, eg: c:\bigqueries.
* Execute the bin/execute.bat file (windows) or bin/run.sh(Linux).

## Publications

### Journals

* Ahcène BOUKORCA, Ladjel BELLATRECHE, Sid-Ahmed Benali Senouci, Zoe FAGET, Coupling Materialized View Selection to Multi Query Optimization: Hyper Graph Approach, International Journal of Data Warehousing and Mining (IJDWM 2015), vol. 11, n. 2, 2015, pp. 62-84

### Conferences

* Dhouha Jemal, Rim FAIZ, Ahcène BOUKORCA, Ladjel BELLATRECHE, MapReduce-DBMS: An Integration Model for Big Data Management and Optimization, Database and Expert Systems Applications - 26th International Conference (DEXA 2015), 2015, pp. 430-439

* Ahcène BOUKORCA, Ladjel BELLATRECHE, Soumia BENKRID, HYPAD: Hyper-Graph-Driven Approach for Parallel Data Warehouse Design, Algorithms and Architectures for Parallel Processing - 15th International Conference (ICA3PP 2015), 2015, pp. 770-783

* Amine ROUKH, Ladjel BELLATRECHE, Ahcène BOUKORCA, Selma BOUARAR, Eco-DMW: Eco-Design Methodology for Data warehouses, 18th International Workshop on Data Warehousing and OLAP (DOLAP), 2015

* Ahcène BOUKORCA, Ladjel BELLATRECHE, Alfredo Cuzzocrea, SLEMAS : An Approach for Selecting Materialized Views Under Query Scheduling Constraints, 20th International Conference on Management of Data (COMAD 2014), 2014, pp. 66-73

* Ahcène BOUKORCA, Zoe FAGET, Ladjel BELLATRECHE, What-if Physical Design for Multiple Query Plan Generation, Proceedings of the 25th International Conference on Database and Expert Systems Applications (DEXA 2014), 2014, pp. 492-506

* Ramin Karimi, Ladjel BELLATRECHE, Patrick GIRARD, Ahcène BOUKORCA, Andras Hajdu, BINOS4DNA: Bitmap Indexes and NoSQL for Identifying Species with DNA Signatures through Metagenomics Samples, 5th International Conference on Information Technology in Bio- and Medical Informatics (ITBAM 2014), 2014

* Ahcène BOUKORCA, Ladjel BELLATRECHE, Sid-Ahmed Benali Senouci, Zoe FAGET, SONIC: Scalable multi-query OptimizatioN through Integrated Circuit, 24th International Conference on Database and Expert Systems Applications (DEXA), edited by LNCS Springer, 2013

* Ladjel BELLATRECHE, Sebastian Bress, Amira KERKAD, Ahcène BOUKORCA, Cheikh SALMI, The Generalized Physical Design Problem in Data Warehousing Environment:Towards a Generic Cost Model, Proceedings of the 31th IEEE International Convention MIPRO (Mipro2013), edited by IEEE, 2013

* Ladjel BELLATRECHE, Cheikh SALMI, Sebastian Bress, Amira KERKAD, Ahcène BOUKORCA, Jalil Boukhobza , How to Exploit the Device Diversity and Database Interaction to Propose a Generic Cost Model, 17th International Database Engineering & Applications Symposium (IDEAS '13), edited by BytePress/ACM and ACM's Digital Library, 2013

## Software licence agreement

* Details the license agreement of EnerQuery: [LICENCE](LICENCE)

## Historic Contributors

* [Ladjel BELLATRECHE](https://www.lias-lab.fr/members/bellatreche/) (LIAS/ISAE-ENSMA)
* [Ahcene BOUKORCA](https://www.lias-lab.fr/fr/members/ahceneboukorca/) (LIAS/ISAE-ENSMA)
* [Zoé FAGET](https://www.lias-lab.fr/fr/members/zoefaget/) (LIAS/University of Poitiers)
    
