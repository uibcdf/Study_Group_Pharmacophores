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
| FLAPpharm    | [Cross2012GRID_cd][Cross2012GRID_cd] [Cross2012GRID_cn][Cross2012GRID_cn] [Baroni2007A_ce][Baroni2007A_ce] | [web][FLAP web] | N  |    | Y  |    |    |    | Y  |    |    |
| LigandScout  | [Wolber2005LigandScout_ce][Wolber2005LigandScout_ce] [Wolber2006Efficient_s7][Wolber2006Efficient_s7] | [web][LigandScout web] |    |    | Y  |    |    |    | Y  |    |    |
| MOE          |            | [web][MOE web]   |    |    | Y  |    |    |    | Y  |    |          |
| Phase        | [Dixon2006PHASE_jx][Dixon2006PHASE_jx] [Dixon2006PHASE_s6][Dixon2006PHASE_s6] | [web][Phase web] |    |    | Y  |    |    |    | Y  |    | Schrödinger |
| Align-it     | [Taminau2008Pharao][Taminau2008Pharao] | [web][Align-it web] | Y  | Y  |    | Y  |    |    |    |    | Old Pharao |
| Forge        | [Cheeseright20006Molecular_cs][Cheeseright20006Molecular_cs] | [web][Forge web] |    |    | Y  |    |    |    |    |    | FieldTemplater component of Forge |
| Dynophores   | [Thesis:Sydow2015][Thesis:Sydow2015] | [web][Dynophores web] [source][Dynophores GitHub] | Y  | Y  |    | Y  |    | Y  |    |    | In progress |

 
[FLAP web]: https://www.moldiscovery.com/software/flap/ "FLAP 2.2 & WaterFLAP"
[Cross2012GRID_cd]: https://doi.org/10.1021/ci300153d "Cross, Simon, Massimo Baroni, Laura Goracci, and Gabriele Cruciani. “GRID-Based Three-Dimensional Pharmacophores I: FLAPpharm, a Novel Approach for Pharmacophore Elucidation.” Journal of Chemical Information and Modeling 52, no. 10 (2012): 2587–98."
[Cross2012GRID_cn]: https://doi.org/10.1021/ci300154n "Cross, Simon, Francesco Ortuso, Massimo Baroni, Giosuè Costa, Simona Distinto, Federica Moraca, Stefano Alcaro, and Gabriele Cruciani. “GRID-Based Three-Dimensional Pharmacophores II: PharmBench, a Benchmark Data Set for Evaluating Pharmacophore Elucidation Methods.” Journal of Chemical Information and Modeling 52, no. 10 (2012): 2599–2608."
[Baroni2007A_ce]: https://doi.org/10.1021/ci600253e "Baroni, Massimo, Gabriele Cruciani, Simone Sciabola, Francesca Perruccio, and Jonathan S Mason. “A Common Reference Framework for Analyzing/Comparing Proteins and Ligands. Fingerprints for Ligands And Proteins (FLAP): Theory and Application.” Journal of Chemical Information and Modeling 47, no. 2 (2007): 279–94."
[LigandScout web]: http://www.inteligand.com/ "Inte:Ligand"
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

