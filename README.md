# [YAML](http://yaml.org/) snippets for AWS [CloudFormation](https://aws.amazon.com/de/cloudformation/) in VS Code

This extension adds some snippets to YAML based files for AWS CloudFormation.

Project located on [Github](https://github.com/dthielking/aws-cloudformation-yaml)

## Features

* Adds YAML base snippets to your VS Code to get CloudFormation resources
* Adds Json parameter config snippets for CloudFormation

## Extension Settings

Following Snippets do provide this extension for YAML files:

* AWSTemplate (Adds a complete template structure)
* NewResource (Adds a new resource)
* NewResourceWithTemplateURL (Adds a resource with TemplateURL)
* Parameter (Adds new parameter to parameter section of your template)
* Output (Adds structure of Output)
* Export (Adds structure of Export for Output)
* Tag (Adds Tag with Key and Value pair)
* Function List:
  * !FindInMap
  * !GetAtt
  * !ImportValue
  * !Join

Following snippets do provide this extenstion for JSON files:

* AWSConfig (Adds a complete parameter configuration)
* ParamKey (Adds new parameters to configuration file)

## Release Notes

You will find all release notes under following link:
[Release Notes](https://github.com/dthielking/aws-cloudformation-yaml/blob/master/CHANGELOG.md)
