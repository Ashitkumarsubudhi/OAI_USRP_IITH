This is the repository that we have used to build the OAI-USRP setup:

For the False Base Station (FBS) work submitted in FNWF 2025, the files with their location we have modified in the 5g-ue-dev are:
1. **openairinterface5g-IITH/openair2/LAYER2/NR_MAC_UE/nr_ue_scheduler.c**
2. **openairinterface5g-IITH/openair2/LAYER2/NR_MAC_UE/nr_ra_procedures.c**
3. **openairinterface5g-IITH/openair2/LAYER2/NR_MAC_UE/mac_defs.h**

wherever we added code, we just added the comment IITH.

The files with their location we have modified in the 5g-du-dev-usrp are:
1. **openairinterface5g-IITH/openair2/GNB_APP/gnb_config.c**
2. **openairinterface5g-IITH/openair2/GNB_APP/gnb_paramdef.h**
3. **openairinterface5g-IITH/openair2/LAYER2/NR_MAC_gNB/gNB_scheduler_RA.c**
4. **openairinterface5g-IITH/openair2/LAYER2/NR_MAC_gNB/gNB_scheduler_ulsch.c**
5. **openairinterface5g-IITH/openair2/LAYER2/NR_MAC_gNB/gNB_scheduler_dlsch.c**
6. **openairinterface5g-IITH/openair2/COMMON/f1ap_messages_types.h**
7. **openairinterface5g-IITH/openair2/GNB_APP/MACRLC_nr_paramdef.h**

wherever we added code, we just added the comment IITH, except this file MACRLC_nr_paramdef.h
