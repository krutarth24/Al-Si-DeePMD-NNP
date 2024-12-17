# Al-Si-DeePMD-NNP

The NNP is trained using the Smooth Edition of Deep Potential (DeePot-SE) from DeePMD pack-age. Our NNP is constructed using a 3-layer embedding net with 32-64-128 nodes, and a 3-layer fitting net with 128 nodes in each layer. The fitting net maps the embedded inputs to the atomic energies and forces. The interaction cutoff radius is 6.0 Å with smoothening at 5.6 Å. The model is trained for 2×10^6 steps, with a batch size of 2, with a learning rate starting at 1×10^-3 , and a decay rate of 0.98. The prefactors for the energy and force loss contributions to the loss function were set as pestart = 0.1, pelimit = 10, pfstart = 1000, pflimit = 1.

The model was trained using DeePMD-kit v2.1.5.
