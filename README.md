# Huet_etal_PLOSCompBio_2022_dataFiles

This repository serves as a source location for the data files associated with the paper "Demonstration of three-dimensional contact point determination and contour reconstruction during active whisking behavior of an awake rat" accepted to PLOS Computational Biology May 2022. 

Authors: Lucie A. Huet*, Hannah M. Emnett*, Mitra J. Z. Hartmann
*Authors contributed equally

Abstract: The rodent vibrissal (whisker) system has been studied for decades as a model of active touch sensing. There are no sensors along the length of a whisker; all sensing occurs at the whisker base. Therefore, a large open question in many neuroscience studies is how an animal could estimate the three-dimensional location at which a whisker makes contact with an object. In the present work we simulated the shape of a real rat whisker to demonstrate the existence of several unique mappings from triplets of mechanical signals at the whisker base to the three-dimensional whisker-object contact point. We then used high speed video to record whisker deflections as an awake rat whisked against a peg, and used the mechanics resulting from those deflections to extract the contact points along the peg surface. These results demonstrate that measurement of specific mechanical triplets at the base of a biological whisker can enable 3D contact point determination during natural whisking behavior. The approach is viable even though the biological whisker has non-ideal, non-planar curvature, and even given the rat’s real-world choices of whisking parameters. Visual intuition for the quality of the approach is provided in a video that shows the contour of the peg gradually emerging during active whisking behavior.

Acknowledgements: TBA

Citation: TBA

## Elastica3D and rat head model 
Please find Elastica 3D and the rat head model available with all Digital Rat files at: https://github.com/SeNSE-lab/DigitalRat/

## Figure Data
File A: [Huet_PLOSCB2022_figureData_part1](https://github.com/SeNSE-lab/Huet_etal_PLOSCompBio2022_dataFiles/edit/main/README.md)
File B: [Huet_PLOSCB2022_figureData_part2](https://github.com/SeNSE-lab/Huet_etal_PLOSCompBio2022_dataFiles/edit/main/README.md)

### Relevant Variables by Figure for the main text
Fig 1: N/A

Fig 2: gamma_undeflected, mapping_FX, mapping_FD, mapping_FT, mapping_MX, mapping_MB, mapping_MD, mapping_R, mapping_TH, mapping_PHI, mapping_POSx, mapping_POSy, mapping_POSz

Fig 3: gamma_undeflected, mapping_FX, mapping_FD, mapping_FT, mapping_MX, mapping_MB, mapping_MD, mapping_R, mapping_TH, mapping_PHI, mapping_POSx, mapping_POSy, mapping_POSz

Fig 4: mapping_FX, mapping_FD, mapping_FT, mapping_MX, mapping_MB, mapping_MD, mapping_R, mapping_TH, mapping_PHI, predicted_rtp_wobj, tracked_rtp_wobj, tracked_MD, tracked_MB, tracked_FX, tracked_filt_MD, tracked_filt_MB, tracked_filt_FX

Fig 5: sens_jac, sens_color, sens_pos

Fig 6: gamma_undeflected, predicted_cp_world, predicted_cp_wobj, tracked_cp_world, predicted_rtp_wobj, tracked_rtp_wobj, tracked_basepoint, tracked_emergence

### Relevant Variables by Figure for S1 Text
Fig A: N/A

Fig B: gamma_undeflected, gamma_deflected

Fig C: mapping_ER, mapping_FX, mapping_FD, mapping_FT, mapping_MX, mapping_MB, mapping_MD, mapping_R, mapping_TH, mapping_PHI, mapping_POSx, mapping_POSy, mapping_POSz
