# Finalized

85_At: Take At_new.psp8 Much faster convergence
87_Fr:  Take Fr.psp8. Smoother convergence 
88_Ra: Rerunning Ra_new.psp8
89_Ac: Take Ac_new
90_Th: Running Th_5f_new_new: : Much better
91_Pa: AE EOS looks OK but best pseudo has 5.44 df. Running Pa_5f_new: Does not improve XXX
92_U: Running U_5f_new: Does not improve XXX
93_Np: AE EOS looks OK but best pseudo has 15.50 df!
94_Pu: Take Pu-5spdf-6spd-7s.psp8
95_Am: Running Am-5spdf-6spd-7s.psp8: Does not improve: Take Am_5f_origin
96_Cm: Take Cm-5spdf-6spd-7s.out
97_Bk: FIXME AE EOS looks suspicious. New results are needed.
98_Cf: Running Cf-5spdf-6spd-7s.psp8. If this does not fix the problem, 
       take Cf_5f.psp8, slightly better than Cf_origin_5f.psp8
99_Es:  FIXME: AE EOS is completely wrong!
100_Fm: FIXME: AE EOS is completely wrong!
101_Md: FIXME: AE EOS is suspicious
102_No: All pseudos are good, should find compromise btw accuracy and convergence ratio
103_Lr: Running: Lr_5f_new.psp8: Take: Lr_5f_new
104_Rf: Running Rf_new
105_Db: Running Db.in, AE EOS looks OK.
106_Sg: Take Sg.psp8
107_Bh: Take Bh.psp8 Perhaps, one can accelerate a bit the convergence.
108_Hs: Take Hs.psp8
109_Mt: Take Mt.psp8
110_Ds: running Ds_new
111_Rg: running Rg.in
112_Rg: running Cn_new.in
113_Nh: Requires extra work
114_Fl: Take Fl.psp8
115_Mc: Take Mc.psp8
116_Lv: Requires extra work
117_Ts: Requires extra work, use Ts.in as starting point
118_Og: ???


# AE results

Weird results for AE EOS of 100_Fm  ------> REDONE AND UPDATED #CT

# pseudos_ac_she

5f 91-92 rifare 

118-119 rifare

no5f da 90 a 102 guardare attentamente

no 5f 103 fare 

# MG CHANGELOG

Ac: Add 1 projector for f to improve logder.

Th_5f.in: Decrease rc for d by 0.5
          NB: This pseudos uses a sligly excited configuration with fractional occupancies.

Pa_5f.in: Optimize qcut, now ecut ~58

U_5f.in: Optimize qcut, decrease core radii, now ecut ~58, previously it was ~68

Np_5f.in: Optimize qcut, decrease core radii, now ecut ~58, previously it was ~62

Pu_5f.in: decrease rc for d by 0.1, no change in qcut values. 
          Already very good and similar to Np_5f.in
 
Am_5f.in: decrease rc for d by 0.2, no change in qcut values. ecut ~70

Cm_5f.in: decrease rc for d by 0.2, minor adjustments in qcut values. ecut ~70

Bk_5f.in: decrease rc for d by 0.2. No change in qcut values. ecut ~72

CF_5f.in: decrease rc for d by 0.2. Important optimization of qcut values: from ~105 to ~72

Es_5f.in: decrease rc for d by 0.2. No change in qcut values. ecut ~75

Fm_5f.in: decrease rc for d by 0.2. Minor adjustment in qcut values. ecut ~73

Md_5f.in: decrease rc for d by 0.2. Minor adjustment in qcut values. ecut ~75

No_5f.in: decrease rc for d by 0.2. Minor adjustment in qcut values. ecut ~78

Lr_5f.in: decrease rc for p by 0.2, d by 0.05. Minor adjustment in qcut values. ecut ~95 due to rc 1.2 for 5f.
          BTW: twpo possible configurations: [Rn]5f147s27p1 or 5f146d17s2

Rf: decrease rc for p and d. Minor adjustment in qcut values. ecut ~95, previous one ~105
Fb: decrease rc for p and d. Minor adjustment in qcut values. ecut ~96, previous one ~105
Sg: decrease rc for p and d. Minor adjustment in qcut values. ecut ~98, previous one ~108
Bh: decrease rc for p and d. Minor adjustment in qcut values. ecut ~100, previous one ~108
Hs: decrease rc for p and d. Minor adjustment in qcut values. ecut ~102, previous one ~108
Mt: decrease rc for p and d. Minor adjustment in qcut values
Ds: decrease rc for p and d. Minor adjustment in qcut values, increase qc for f, ecut 120,  previous one ~140
Ds: decrease rc for p and d. Minor adjustment in qcut values, increase qc for f, ecut 120,  previous one ~140
Cn: decrease rc for p and d. Minor adjustment in qcut values, increase qc for f, ecut 120,  previous one ~160
Ng: Minor adjustment in qcut values, ecut 125,  previous one ~128

Fl: Add projector for f with ep = 0.05 to improve f-logder
Mg: Add projector for f with ep = 0.05 to improve f-logder
Lv: Add projector for f with ep = 0.05 to improve f-logder
Ts: Decrease rcs significantly. Add projector for f with ep = 0.05 to improve f-logder
Og: Decrease rcs significantly e.g from 1.6 to 1.4. Add projector for f with ep = 0.05 to improve f-logder


Fr: Add two projectos for f to improve logder.  Minor adjustment in qcut values. Ecut now ~35

At: Decrease core radii using my new Po-spd.in as starting point. Add extra projector for f-channel with ep 0.05


### FCC COMPUTATIONAL DETAILS####

Spin Orbit Coupling	no
Spin Polarization	collinear (Z)
Smearing Fermi-Dirac	0.001 Ha
K-points	15 x 15 x 15

### OXIDES COMPUTATIONAL DETAILS
------- WE DO NOT USE THESE RESULTS FOR THE PAPER  #CT
Spin Orbit Coupling no
Spin Polarization   collinear (Z)
Smearing Fermi-Dirac    0.05 Ha
K-points    5 x 5 x 5

### DATA FOR PAPERS
1) Delta-Gauge (meV) (FCC system)
2) Lattice percentage difference between AE and PW (FCC system)
3) Plot of hints
4) Delta-Gauge (meV) vs hints
5) Difference between V0 B0 and B0' obtained with AE and PW (FCC system)

