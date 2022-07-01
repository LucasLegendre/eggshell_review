# eggshell_review

Contains the dataset, phylogenetic tree, and R code related to analyses for the following study:

Legendre, L. J., S. Choi, and J. A. Clarke. 2022. The diverse terminology of reptile eggshell microstructure and its effect on phylogenetic comparative analyses. <i>Journal of Anatomy</i>.

File description:

- 'Eggshell_review_project.html': HTML tutorial for the code used in the paper (all references and a detailed description of the protocol can be found in the online Supplementary Information of the paper)

- 'Eggshell_review_project.Rmd': original R script used to generate the HTML file, in Markdown format

- 'Datawhole_newproject.txt': dataset in TXT format, containing egg measurements and scoring for all three scoring procedures for 208 species of reptiles (fully referenced version is included as Supplementary Table 1 in Legendre et al., 2022)

- 'treewhole_newversion.trees.nex': phylogenetic tree for dataset, in NEXUS format

NOTE:

The tree as published in the reference cited above contains one minor error (M. Fabbri, pers. comm.): eggs originally attributed to taxon <i>Orodromeus makelai</i> (Dinosauria, Ornithischia – see Horner and Weishampel, 1988; Hirsch and Quinn, 1990) were later identified as eggs of a troodontid (Dinosauria, Theropoda – see Horner and Weishampel, 1996; Varricchio et al., 1997). We have modified the position of this taxon (now named 'Troodontid_indet') in our tree to reflect this change.
Some of the resulting ancestral reconstructions (when using SIMMAP) are slightly different from the ones present in the paper (see R script and HTML tutorial). This does not affect our general results and discussion and does not change the conclusions of our paper, as it supports our assessment of a disproportionate influence of taxon sampling, topology, and calibration on ancestral reconstructions. Similarly, the ambiguity of each coding strategy as described in the paper is not affected by this new topology.

References
- Hirsch, K.F., Quinn, B., 1990. Eggs and eggshell fragments from the Upper Cretaceous Two Medicine Formation of Montana. <i>Journal of Vertebrate Paleontology</i> 10, 491–511. 
- Horner, J.R., Weishampel, D.B., 1988. A comparative embryological study of two ornithischian dinosaurs. <i>Nature</i> 332, 256–257.
- Horner, R., Weishampel, D.B., 1996. Correction: A comparative embryological study of two ornithischian dinosaurs. <i>Nature</i> 383, 103.
- Varricchio, D.J., Jackson, F., Borkowski, J.J., Horner, J.R., 1997. Nest and egg clutches of the dinosaur <i>Troodon formosus</i> and the evolution of avian reproductive traits. <i>Nature</i> 385, 247–250.

