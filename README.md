# paper.measurement_backaction

Example code from:

**LH18171B**

> Impact of measurement backaction on nuclear spin qubits in silicon
> by S. Monir, E. N. Osika, S. K. Gorman, et al.


## Details


* `spin_func.ipynb` is required to run all the other notebooks. It contains the functions to generate the hyperfine and Zeeman Hamiltonians, and also the Lindblad operators corresponding to electron tunnelling.

The notebooks
  * `read_1P.ipynb`, `read_1P.ipynb`, `read_1P.ipynb` and `res_1P.ipynb` simulate the readout pulse for 1P, 2P and 3P systems, and the resonant tunnelling pulse for a 1P system.

  * `1p1e_flip_master.ipynb` simulates the pulse sequence from J. J. Pla, Single atom spin qubits in silicon, Ph.D. thesis, UNSW Sydney (2013), Fig. 5.5 of page - 130.
    The results are plotted in supplementary figure FIG. S2


## Usage

* Ensure the packages listed in [notebooks/requirements.txt](notebooks/requirements.txt) are installed
* Open the notebook(s) in your preferred Jupyter Notebook environment