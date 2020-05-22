# L1Trigger-DTPhase2Trigger

## Instructions to download

```
cmsrel CMSSW_11_1_0_pre4
cd CMSSW_11_1_0_pre4/src
cmsenv
git cms-init
git cms-merge-topic  dtp2-tpg-am:AM_111X_dev
git clone git@github.com:dtp2-tpg-am/L1Trigger-DTPhase2Trigger.git L1Trigger/DTTriggerPhase2/data
scram b -j 8
```
