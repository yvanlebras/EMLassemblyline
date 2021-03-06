# The EML Assembly Line

The Ecological Metadata Language (EML) is a metadata standard developed by the ecological community for persistence, discoverability, and reuse of ecological data. While the highly detailed structure of the EML schema is necessary to meet these ends, it confronts the inexperienced data provider with a steep learning curve that few have time to tackle. To lower the bar for data documentation, while still maintaining metadata detail and quality, we've created the `EMLassemblyline` R code package. A user-friendly workflow to help craft high quality EML metadata yourself. The assembly line is useful for publishing one-off data packages or to provide a foundation for a data package factory.

The assembly line requires little operational knowledge of the R programming language or technical understanding of the EML schema. All you need is to know your dataset and how it was made, a little patience for following our step by step instructions, and how to operate a spread sheet editor. If this is your first time on the assembly line, it may take the better part of a day to become oriented and to produce your first EML metadata file.


## Getting started

### Contents

#### Documenation

[A schematic representation of the assembly line process.](https://github.com/EDIorg/EMLassemblyline/blob/master/documentation/schematic.md)

[A list of the EML schema elements that are populated by the assembly line with some notes on the level of detail supplied to these elements.](https://github.com/EDIorg/EMLassemblyline/blob/master/documentation/schema_use.md)

[Instructions for operating the EML assembly line](https://github.com/EDIorg/EMLassemblyline/blob/master/documentation/instructions.md)

#### R package

`EMLassemblyline` is a collection of wrapper functions to the `EML` R package developed by [Boettiger et al. (2017)](https://github.com/ropensci/EML). For an understanding of what is going on under the hood of the assembly line, we recommend you first take a look at the `EML` R package. Once you understand this you will be able to customize the assembly line for your own workflows or become a developer of this project.

The `EMLassemblyline` R package is available here on GitHub. To install, go to your RStudio Console window and enter these lines of code:

```
# Install and load devtools
install.packages("devtools")
library(devtools)

# Install and load EMLassemblyline
install_github("EDIorg/EMLassemblyline")
library(EMLassemblyline)
```

Now reference the documentation listed above to start operating the assembly line.

## Contributing

We welcome contributions of all forms including code, bug reports, and requests for development. Please reference our [code conduct](https://github.com/EDIorg/EMLassemblyline/blob/master/CODE_OF_CONDUCT.md) and [contributing guidelines](https://github.com/EDIorg/EMLassemblyline/blob/master/CONTRIBUTING.md) for submitting pull requrests.

## Versioning

This project follows the [semantic versioning specification](https://semver.org).

## Authors

Several people have participated in this project. [View the current list of team members and contributors](https://github.com/EDIorg/EMLassemblyline/blob/master/AUTHORS.md).

## Related materials

[Learn everything you wanted to know about the Ecological Metadata Language standard.](https://knb.ecoinformatics.org/#external//emlparser/docs/index.html)

[Reference the community developed best practices for EML content.](https://environmentaldatainitiative.org/resources/assemble-data-and-metadata/step-3-create-eml-metadata/best-practices-for-dataset-metadata-in-ecological-metadata-language-eml/)
