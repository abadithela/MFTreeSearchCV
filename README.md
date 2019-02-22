# MFTreeSearchCV

This is a package for fast hyper-parameter tuning using noisy multi-fidelity tree-search for scikit-learn estimators (classifiers/regressors). Given ranges and types (categorical, integer, reals) for several hyper-parameters, this package is desgined to search for a good configuartion by treating the k-fold cross-validation errors and different setting under different fidelities (levels of approximation based on amount od data used), as a multi-fidelity noisy black-box function. We acknowledge the support from [@kirthevasank](https://github.com/kirthevasank) for providing the original multi-fidelity black-box function code base. This work is based on the publications:

1. [A deterministic version of MF Tree Seach](http://proceedings.mlr.press/v80/sen18a/sen18a.pdf)
2. [A version that can hadle noise -- which is there in tuning](https://arxiv.org/pdf/1810.10482)

Please cite the above papers, if using this software in any publications/reports. 

## Getting Started


### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
