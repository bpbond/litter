# litter
Update of Holland ORNL DAAC litter database

**Check For-C database**

1. Add DOI and year to Holland studies (`Holland_DOIs.csv`)
2. Add species codes (PIBA2, etc.) and leaf habit (DBL, EBL, DNL, ENL)
3. Check [Zhang et al. 2008](http://dx.doi.org/10.1093/jpe/rtn002) data and studies
4. Import data from SRDB
5. Check [Vogt et al. 1986](https://www.sciencedirect.com/science/article/pii/S0065250408601221)
6. Other databases? LTER, FLUXNET BADM, ...?
7. Go through downloaded WOS records.

These steps should be programmatic as much as possible, probably using a [drake](https://github.com/ropensci/drake) pipeline.
