## Description
CNS scripts to calculate pairwise residue-residue & atom-atom
energies (vdW and elec) according to the OPLS-X force field as
implemented in HADDOCK.

## Usage
Change the header of the script to point to your structure of choice.

````bash
    cns < calc_pairwise_residue.cns > /dev/null
    # Energies will be written to a file with the same name
    # as the structure and extension 'pwr_ene'

    cns < calc_pairwise_atom.cns > /dev/null
    # Energies will be written to a file with the same name
    # as the structure and extension 'pwa_ene'
````
