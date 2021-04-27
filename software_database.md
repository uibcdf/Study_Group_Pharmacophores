# List of software to pharmacophore modeling

The following table summarizes the list of software we have found so far to build, and to work
with, pharmacophore models. The table includes these next features for each software:

|   Property | Letters  | When |
|---|---|---|
| Open Source | OS | If the code is available and with open source standards |
| Free |  FR | If the software is free to be used. Or at least there is a non-commercial or academic license |
| Proprietary | PR | If the software is non-free, copyrighted, and runs under commercial licenses |
| Pythonic | PY | The software is open source in Python, or there is an API in Python implemented |
| Multi-structures | MS | If the software provides the possibility to play explicitly with different structures of the same compound or receptor |
| Molecular Dynamics| MD | If the software provides the possibility to build pharmacophoric models running molecular dynamics or from molecular dynamics trajectories|
| Virtual Screening | VS | If the software runs virtual screenings |
| De Novo Design | DN | If the software is oriented to perform *de novo* design |


The software table:

| Name         | References | Links            | OS | FR | PR | PY | MS | MD | VS | DN | Comments |
| :--------    | :--------- | :--------------- | :-:| :-:| :-:| :-:| :-:| :-:| :-:| :-:| :------- |
| FLAPpharm (FLAP)   | [Cross2012GRID_cd][Cross2012GRID_cd] [Cross2012GRID_cn][Cross2012GRID_cn] [Baroni2007A_ce][Baroni2007A_ce] | [web][FLAP web] | N  |    | Y  |    |    |    | Y  |    |    |
| LigandScout  | [Wolber2005LigandScout_ce][Wolber2005LigandScout_ce] [Wolber2006Efficient_s7][Wolber2006Efficient_s7] | [web][LigandScout web] |    |    | Y  |    |    |    | Y  |    |    |
| MOE          |            | [web][MOE web]   |    |    | Y  |    |    |    | Y  |    |          |
| Phase (Schrödinger)       | [Dixon2006PHASE_jx][Dixon2006PHASE_jx] [Dixon2006PHASE_s6][Dixon2006PHASE_s6] | [web][Phase web] |    |    | Y  |    |    |    | Y  |    |   |
| Align-it     | [Taminau2008Pharao][Taminau2008Pharao] | [web][Align-it web] | Y  | Y  |    | Y  |    |    |    |    | Old Pharao |
| FieldTemplater (Forge) | [Cheeseright2006Molecular_cs][Cheeseright2006Molecular_cs] | [web][Forge web] |    |    | Y  |    |    |    |    |    |   |
| Dynophores   | [Thesis:Sydow2015][Thesis:Sydow2015] | [web][Dynophores web] [source][Dynophores GitHub] | Y  | Y  |    | Y  |    | Y  |    |    |   |
| HipHop (Catalyst)| [Kurogi2001Pharmacophore_01][Kurogi2001Pharmacophore_01] [Guner2004Pharmacophore_06][Guner2004Pharmacophore_06] [Dough1996Identification_cr][Dough1996Identification_cr] | [web][Catalyst web]     |    |    | Y  |    | Y? |    | Y  |    | Now in BioviaDiscovery Studio |
| HipoGen (Catalyst)| [Kurogi2001Pharmacophore_01][Kurogi2001Pharmacophore_01] [Guner2004Pharmacophore_06][Guner2004Pharmacophore_06] [Li2000HypoGen][Li2000HypoGen] | [web][Catalyst web]     |    |    | Y  |    |    |    | Y  |    | Now in BioviaDiscovery Studio |
| HipoRefine (Catalyst)| [Kurogi2001Pharmacophore_01][Kurogi2001Pharmacophore_01] [Guner2004Pharmacophore_06][Guner2004Pharmacophore_06] [Maynard2004HypoRefine][Maynard2004HypoRefine] | [web][Catalyst web]     |    |    | Y  |    |    |    | Y  |    | Now in BioviaDiscovery Studio |
| PharmaGist    | [Schneidman2008PharmaGist][Schneidman2008PharmaGist]  |  [web][PharmaGist web]  |    |  Y  |    |    |    |    |    |    | Web app |

[FLAP web]: https://www.moldiscovery.com/software/flap/ "FLAP 2.2 & WaterFLAP"
[Cross2012GRID_cd]: https://doi.org/10.1021/ci300153d "Cross, Simon, Massimo Baroni, Laura Goracci, and Gabriele Cruciani. “GRID-Based Three-Dimensional Pharmacophores I: FLAPpharm, a Novel Approach for Pharmacophore Elucidation.” Journal of Chemical Information and Modeling 52, no. 10 (2012): 2587–98."
[Cross2012GRID_cn]: https://doi.org/10.1021/ci300154n "Cross, Simon, Francesco Ortuso, Massimo Baroni, Giosuè Costa, Simona Distinto, Federica Moraca, Stefano Alcaro, and Gabriele Cruciani. “GRID-Based Three-Dimensional Pharmacophores II: PharmBench, a Benchmark Data Set for Evaluating Pharmacophore Elucidation Methods.” Journal of Chemical Information and Modeling 52, no. 10 (2012): 2599–2608."
[Baroni2007A_ce]: https://doi.org/10.1021/ci600253e "Baroni, Massimo, Gabriele Cruciani, Simone Sciabola, Francesca Perruccio, and Jonathan S Mason. “A Common Reference Framework for Analyzing/Comparing Proteins and Ligands. Fingerprints for Ligands And Proteins (FLAP): Theory and Application.” Journal of Chemical Information and Modeling 47, no. 2 (2007): 279–94."
[LigandScout web]: http://www.inteligand.com/ "Inte:Ligand"
[PharmaGist web]: https://bioinfo3d.cs.tau.ac.il/PharmaGist/php.php "PharmaGist webserver"
[Wolber2005LigandScout_ce]: https://doi.org/10.1021/ci049885e "Wolber, Gerhard, and Thierry Langer. “LigandScout:  3-D Pharmacophores Derived from Protein-Bound Ligands and Their Use as Virtual Screening Filters.” Journal of Chemical Information and Modeling 45, no. 1 (2005): 160–69."
[Wolber2006Efficient_s7]: https://doi.org/10.1007/s10822-006-9078-7 "Wolber, Gerhard, Alois A. Dornhofer, and Thierry Langer. “Efficient Overlay of Small Organic Molecules Using 3D Pharmacophores.” Journal of Computer-Aided Molecular Design 20, no. 12 (2006): 773–88."
[MOE web]: https://www.chemcomp.com/index.htm "Chemical Computing Group"
[Phase web]: https://www.schrodinger.com/products/phase "Schrödinger Inc."
[Dixon2006PHASE_jx]: https://doi.org/10.1111/j.1747-0285.2006.00384.x "Dixon, Steven L., Alexander M. Smondyrev, and Shashidhar N. Rao. “PHASE: A Novel Approach to Pharmacophore Modeling and 3D Database Searching.” Chemical Biology & Drug Design 67, no. 5 (2006): 370–72."
[Dixon2006PHASE_s6]: https://doi.org/10.1007/s10822-006-9087-6 "Dixon, Steven L., Alexander M. Smondyrev, Eric H. Knoll, Shashidhar N. Rao, David E. Shaw, and Richard A. Friesner. “PHASE: A New Engine for Pharmacophore Perception, 3D QSAR Model Development, and 3D Database Screening: 1. Methodology and Preliminary Results.” Journal of Computer-Aided Molecular Design 20, no. 10–11 (2006): 647–71."
[Align-it web]: http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/software.html "silicos-it"
[Taminau2008Pharao]: https://doi.org/10.1016/j.jmgm.2008.04.003 "Taminau, Jonatan, Gert Thijs, and Hans De Winter. “Pharao: Pharmacophore Alignment and Optimization.” Journal of Molecular Graphics and Modelling 27, no. 2 (2008): 161–69."
[Forge web]: https://www.cresset-group.com/software/field-templater/ "Forge, Cresset Software."
[Cheeseright2006Molecular_cs]: https://doi.org/10.1021/ci050357s "Cheeseright, Tim, Mark Mackey, Sally Rose, and Andy Vinter. “Molecular Field Extrema as Descriptors of Biological Activity:  Definition and Validation.” Journal of Chemical Information and Modeling 46, no. 2 (2006): 665–76."
[Dynophores web]: https://dynophores.readthedocs.io/en/latest/ "Dynophores' Read the docs"
[Dynophores GitHub]: https://github.com/dominiquesydow/dynophores "Dynophores' GitHub"
[Thesis:Sydow2015]: https://doi.org/10.18452/14267 "Dominique Sydow.'Dynophores: Novel Dynamic Pharmacophores'. 2015"
[Catalyst web]: https://www.3ds.com/products-services/biovia/products/molecular-modeling-simulation/biovia-discovery-studio/pharmacophore/ "Biovia Discovery Studio"
[Kurogi2001Pharmacophore_01]: https://doi.org/10.2174/0929867013372481 "Kurogi, Yasuhisa, and Osman Guner. “Pharmacophore Modeling and Three-Dimensional Database Searching for Drug Design Using Catalyst.” Current Medicinal Chemistry 8, no. 9 (2001): 1035–55."
[Doug1996Identification_cr]: https://doi.org/10.1021/ci950273r "Barnum, Doug, Jonathan Greene, Andrew Smellie, and Peter Sprague. “Identification of Common Functional Configurations Among Molecules.” Journal of Chemical Information and Computer Sciences 36, no. 3 (1996): 563–71."
[Guner2004Pharmacophore_06]: https://doi.org/10.2174/0929867043364036 "Guner, Osman, Omoshile Clement, and Yasuhisa Kurogi. “Pharmacophore Modeling and Three Dimensional Database Searching for Drug Design Using Catalyst: Recent Advances.” Current Medicinal Chemistry 11, no. 22 (2004): 2991–3005."
[Maynard2004HypoRefine]: - "Maynard, AJ, M Waldman, and J Sutter. “Hyporefine: Automated Identification of Exclusion Volumes in Pharmacophore Models.” In ABSTRACTS OF PAPERS OF THE AMERICAN CHEMICAL SOCIETY, 227:U686--U686, 2004."
[Li2000HypoGen]: - "Li, H, J Sutter, and R Hoffmann. “HypoGen: An Automated System for Generating 3D Predictive Pharmacophore Models.” Pharmacophore Perception, Development, and Use in Drug Design 2 (2000): 171."
[Schneidman2008PharmaGist]: https://doi.org/10.1093/nar/gkn187 "Dina Schneidman-Duhovny, Oranit Dror, Yuval Inbar, Ruth Nussinov, Haim J. Wolfson, PharmaGist: a webserver for ligand-based pharmacophore detection, Nucleic Acids Research, Volume 36, Issue suppl_2, 1 July 2008, Pages W223–W228"
