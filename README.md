# [YAML](http://yaml.org/) snippets for AWS [CloudFormation](https://aws.amazon.com/de/cloudformation/) in VS Code

This extension adds some snippets to YAML based files for AWS CloudFormation.

Project located on [Github](https://github.com/dthielking/aws-cloudformation-yaml)

## Overview

* Adds YAML base snippets to your VS Code to get CloudFormation resources
* Adds Json parameter config snippets for CloudFormation

## Extension usage

Following Snippets do provide this extension for YAML files:

* AWSTemplate (Adds a complete template structure)
* Parameter section
  * Parameter (Adds new parameter to parameter section of your template)
* Resource section
  * NewResource (Adds a new resource)
  * NewResourceWithTemplateURL (Adds a resource with TemplateURL)
* Output section
  * Output (Adds structure of Output)
  * Export (Adds structure of Export for Output)
* Miscellaneous
  * Tags (Add Tag: Key, Value)
  * Function List:
    * !FindInMap
    * !GetAtt
    * !ImportValue
    * !Join
    * !Sub

Following snippets do provide this extenstion for JSON files:

* AWSConfig (Adds a complete parameter configuration)
* ParamKey (Adds new parameters to configuration file)

## Release Notes

You will find all release notes under following link:
[Release Notes](https://github.com/dthielking/aws-cloudformation-yaml/blob/master/CHANGELOG.md)
