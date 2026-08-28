# Icarus_with_Collisionless_Heatflux
This repository contains the supporting code and data for the article: "Effects of observation-constrained suprathermal electrons in Icarus solar wind modeling",  submitted to Journal of Geophysical Research: Space Physics

The repository contains:
1) Modified mod_usr.t file
This user-defined configuration file for ICARUS includes an additional collisionless heat-flux term, implemented in the specialsource subroutine. By default, the radial dependence of $\alpha_\kappa(R)$ is described by a sigmoid-plus-offset function (see Eq. 15 in the paper), with parameters corresponding to the saturating profile shown in Figure 4. Alternative radial profiles can be activated by uncommenting the corresponding power-law-plus-offset or broken-log expressions in the file. The original ICARUS v3.3 code is available on repository: https://github.com/amrvac/amrvac/blob/master/tests/mhd/icarus/README.md
2) Inner Boundary files (.vtk) used in ICARUS runs (to be uploaded later)
3) Bin-averaged observational data set
This data set (named DS1 in the paper) describes the radial variation of kappa parameter (of electron halo), from the three missions, Helios 1 (0.3 - 1.0 AU), Cluster II (approximately 1 AU) and Ulysses (1.2 - 3.95 AU) described in Stverak et al (2008) and Lazar et al. (2020) (A&A paper) (to be uploaded later)
4) ICARUS simulation output files .vtu (to be uploaded later)
5) Jupiter notebooks for plotting and visualisation (to be uploaded later)
