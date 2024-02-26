# A71EV2A_compound_order_2

Compound submission using pipeline starting from *all* new A71EV2A fragments

Imposed scoring cut-offs to reduce compounds for selection to ~100
- Enamine availability
- Maintain an interaction (residue-level) seen in each parent fragment 
- Num non-hyd ints > 2
- SuCOS > 0.55
- ComRMSD > 1.5
- Butina clustering using Morgan fingerprint for diversity selection (distance threshold of 0.3)

Resulted in 219 compounds. Employed manual selection to reduce this to 110 compounds. Removed 2 compounds that were submitted in a previous iteration to give a list of 108 compounds.
