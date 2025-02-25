# facet2-lattice
Lattice files for the FACET-II accelerator


CHANGELOG:
* 2/25/2021, G. White & M. Woodley: changes to reflect in-tunnel hardware for INJ, BC11, BC14 & S20 (see MAD xsif files for details)
* 11/5/2020, G. White: Added model-independent data directory for storing e.g. Beam stay clear data
* 05/18/2020, G. White: Imported (older) ImpactT files for FACET-II injector (warning, doesn't exactly match GPT files)
* 03/03/2020, G. White: Files imported into slac lab / facet2-lattice github repo
* 07/21/2017, G. White: Re-formatted decks by MDW and re-configured injector for FACET-II requirements
* 05/02/2017, G. White: Updated to v1.4.4 DR optics (added steering correctors and BPMs to lattice)
* 04/28/2017, G. White: Added BC20E optics & updated DRTBC11 optics for v1.43 DR optics
* 04/27/2017, G. White: Added BC20P optics
* 07/13/2017, G. White: Updated structure for main Linac decks compiled by M. Woodley
* 04/26/2017, G. White: Update PRLTDR optics to be compatible with v1.43 DR optics
* 03/23/2016, G. White: Update to v1.43 of DR optics (sliced magnet models)
* 11/15/2016, G. White: Add v1.4 of DR optics (Harmonic #=51, with 2 or 4 RF cavities)
* 04/13/2016, G.White: TDR version
* 02/08/2015, G.White: Initial CVS release.

This archive file contains lattice files in MAD8 (or XSIF) and Lucretia format for the FACET2 electron and positron beam lines.
Also electron beam line and positron damping ring in bmad format.
Also positron damping ring in AT format.

See MAD/doc directory for some documentation.

CONTENTS:
* Data/ : Model independent data : Beam stay clear files
* MAD/doc/ : Documentation directory
* MAD/FACET2e.mad8 : Master deck file for parsing electron beamlines
* Lucretia/models/FACET2e/FACET2e.mat : Lucretia file for electron beamlines
* MAD/FACET2p.mad8 : Master deck file for parsing positron beamlines
*   INJ / DL10 / BC11 / BC14 / L1 / L2 / L3 / LI20 .xsif : Subsystem decks
* MAD/FACET2p_PRLTDR.xsif : XSIF lattice for positron return line to DR injection.
* MAD/FACET2p_DRTBC11.xsif : Positron system from DR extraction, through vertical extraction
                        dogleg, through first e+ bunch compressor chicane, beam diagnostic
                        waist and horizontal dogleg injection to main beamline in last
                        BC11 bend magnet.
* MAD/FACET2p_DR.xsif : Positron damping ring v1.4.4
* MAD/FACET2p_DR.bmad : Positron damping ring v1.4.3 (BMAD format)
* Lucretia/models/FACET2p_DR.mat : Lucretia lattice files for positron damping ring
* AT/FACET2p_DR.mat : AT positron damping ring model
* QDDSQ*.[xsif|bmad] : Sliced quad-sextupole arc models for DR
* BA/BD.[xsif|bmad] : Sliced models for bend-quad-sextupole arc magnets for DR
* ImpactT: Matlab scripts and supporting ImpactT data files to generate FACET-II electron injector lattice up to exit of L0a
