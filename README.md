# Panopticon: A Complete In-DRAM RowHammer Mitigation

The code in this repository implements a simple simulator of Panopticon targeting
DDR5 DRAM. 

The simulator is written in Julia using a JupyterLab notebook. If you are unfamiliar 
with these notebooks, we recommend installing Anaconda3 which will include JupyterLab, and then installing Julia 64-bit.

We used this simulator to experiment with different row activation workloads and evaluate Panopticon's overhead.

For more details on Panopticon please read our paper:

Tanj Bennett, Stefan Saroiu, Alec Wolman, Lucian Cojocar  
[Panopticon: A Complete In-DRAM Rowhammer Mitigation](https://stefan.t8k2.com/publications/dramsec/2021/panopticon.pdf)\
<em>Proceedings of the 1st Workshop on DRAM Security (DRAMSec)</em>,  June 2021.


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

