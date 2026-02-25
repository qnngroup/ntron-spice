# SPICE_models
SPICE model of nTron.

## nanocryotron (`ntron`)

Galvanically coupled [three-terminal electrothermal switch](https://pubs.acs.org/doi/10.1021/nl502629x).
Typically operated as an amplifier.
The gate is placed below the channel constriction.

See [section 3.3 of this thesis](https://webthesis.biblio.polito.it/15926/?template=default) for an explanation of the model.

![ntron](/docs/ntron.png)


## wide-gate symmetric nanocryotron (`ntron_symm`)

Gate width comparable to channel width, gate is centered on channel constriction.
Typically operated as a current summation comparator.

See [section 3.2.1 of this thesis](https://dspace.mit.edu/handle/1721.1/151424) for a comparison between `ntron` and `ntron_symm` models.

![ntron_symm](/docs/ntron_symm.png)
