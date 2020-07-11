Toolkit for Building Robust ML models that generalize to unseen domains (RobustDG)
==================================================================================
`Divyat Mahajan <https://divyat09.github.io/>`_, 
`Shruti Tople <https://www.microsoft.com/en-us/research/people/shtople/>`_, 
`Amit Sharma <http://www.amitsharma.in>`_

`ICML 2020 Paper <https://arxiv.org/abs/1909.12732>`_ | `MatchDG paper <https://arxiv.org/abs/2006.07500>`_

For machine learning models to be reliable, they need to generalize to data
beyond the train distribution. In addition, ML models should be robust to
privacy attacks like membership inference and domain knowledge-based attacks like adversarial attacks.

To advance research in building robust and generalizable models, we are
releasing a toolkit for building and evaluating ML models, *RobustDG*. RobustDG contains implementations of domain
generalization algorithms and includes variety of evaluation benchmarks based
on out-of-distribution accuracy, robustness to privacy and adversarial attacks. 

It is easily extendable. Add your own DG algorithms and evaluate them on different benchmarks.


Installation
------------
To use the command-line interface of RobustDG, clone this repo and add the
folder to your system's PATH (or alternatively, run the commands from the
RobustDG root directory)

```
train ---<more params>
```

Demo
----

A quick introduction on how to use our repository can be accessed here in the `Getting Started notebook <https://github.com/microsoft/robustdg/blob/master/docs/notebook/robustdg_getting_started.ipynb>`_.

If you are interested in reproducing results from the MatchDG paper, check out the `Reproducing results notebook <https://github.com/microsoft/robustdg/blob/master/docs/notebooks/reproducing_results_matchdg_paper.ipynb>`_. 



Contributing
--------------

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the `Microsoft Open Source Code of Conduct <https://opensource.microsoft.com/codeofconduct/>`_.
For more information see the `Code of Conduct FAQ <https://opensource.microsoft.com/codeofconduct/faq/>`_ or
contact `opencode@microsoft.com <mailto:opencode@microsoft.com>`_ with any additional questions or comments.