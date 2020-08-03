# SN-BASED EMULATING FRAMEWORK

This repository contains the **emulating framework** to model distributed self-adaptive systems with decentralized adaptation control.
The modeling framework is based on [Symmetric Nets](https://www.iso.org/standard/52070.html).
This repository contains the SN modules composing the framework along with running examples (based on a manufacturing system case study).

Published papers describing the emulating framework are as follows:

* Capra L., Camilli M. (2020) Emulating Self-adaptive Stochastic Petri Nets. In: Gribaudo M., Iacono M., Phung-Duc T., Razumchik R. (eds) Computer Performance Engineering. EPEW 2019. Lecture Notes in Computer Science, vol 12039. Springer, Cham. https://doi.org/10.1007/978-3-030-44411-2_3
* L. Capra and M. Camilli, "A Symmetric Nets Emulator for Adaptive P/T Nets," 2018 20th International Symposium on Symbolic and Numeric Algorithms for Scientific Computing (SYNASC), Timisoara, Romania, 2018, pp. 183-190, doi: 10.1109/SYNASC.2018.00038
* Capra, L., & Camilli, M. (2018). Towards Evolving Petri Nets: a Symmetric Nets-based Framework. IFAC-PapersOnLine, 51(7), 480-485

All the models can be opened and simulated/analyzed by using the [GreatSPN](http://www.di.unito.it/~amparore/mc4cslta/editor.html) software tool.

### Content:

*    `Emulator.PNPRO`: emulator SN model (nominal + optimized versions);
*    `Emu_modules.PNPRO`: separated modules composing the whole framework;
*    `Emu_ams.PNPRO`: asymmetric manufacturing system example along with CSLTA requirements;
*    `Emu_sms.PNPRO`: symmetric manufacturing system example along with CSLTA requirements;

### Contacts:

*    [Lorenzo Capra](https://homes.di.unimi.it/capra/) - capra@di.unimi.it
*    [Matteo Camilli](https://matteocamilli.github.io/) - matteo.camilli@unibz.it
