# doc-acs-gbm

## List of the IBAS triggers

https://github.com/volodymyrss/doc-acs-gbm/blob/master/all_acs_ibas_triggers.csv

List of all triggers from:

https://www.isdc.unige.ch/integral/ibas/cgi-bin/ibas_acs_web.cgi

## ACS data for known triggers

https://github.com/volodymyrss/doc-acs-gbm/blob/master/acs_for_gbm.csv

Simple INTEGRAL SPI-ACS data summary for the GBM triggers. 

Few plots for the bursts with high S/N in SPI-ACS but low GBM Fluence to Fluence Error ratio (whatever it means), with these conditions:

```python
R.integral_detstat_best_scale_snr > 15.
R.integral_detstat_excvar_bkg < 1.5
R.gbm_FLUENCE/R.gbm_FLUENCE_ERROR < 10
```
