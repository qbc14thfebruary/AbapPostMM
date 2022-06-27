# AbapPostMM: Materials Management
Post MM in SAP
Create: PO: 
Goto tcode Me21N then fill in the necessary information to initialize the PO

Create program by clone reponseve.

Run and goto tcode MIGO fill Material Document and Year

Check  assign code to transaction for BAPI goods movement: https://wiki.scn.sap.com/wiki/display/ERPSCM/Goods+Movements+with+BAPI

Movement Indicator in Structure BAPI2017_GM_ITEM_CREATE in BAPI_GOODSMVT_CREATE.
 - value: B: GOODSMVT_CODE = 01.
 - value: F: GOODSMVT_CODE = 02.
