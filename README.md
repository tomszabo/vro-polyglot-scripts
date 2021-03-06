# vro-polyglot-scripts
A collection of vRealize Orchestrator Polyglot example scripts in Node.js, Python and PowerShell to bootstrap your multi language vRO development

![vRO Script Runtimes](https://github.com/tgeorgiev/vro-polyglot-scripts/blob/master/assets/vro.png)

## About this Repository
This repository provides simple template-like scripts to get you up to speed with the multi language development introduced in vRO 8.1. The functions are intended to be as simple and informative as possible to let you know the basics and extend further for your specific use cases.

You if are used to vRO you will notice that the new format and structure is different that the classical vRO JavaScript, on the other hand if you are familiar with AWS Lambda, Azure Functions and vRA ABX you will find it very similar. vRO multi-language scripts closely follows the format of those function execution engines.

## List of samples

### Node

[Simple Action](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/node/simple-action) - Get to know how your Node.js script can accept inputs and return output of different types

[Sync-Async](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/node/sync-async) - See how you can write your function and return an output using different flavours of synchronous and asynchronous handling (applicable only for Node.js)

[List EC2 instances using AWS SDK](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/node/aws) - Import 3rd party NPM modules, specifically the AWS SDK, and integrate with AWS services


### Python

[Simple Action](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/python/simple-action) - Get to know how your Python script can accept inputs and return output of different types

[List EC2 instances using AWS SDK](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/python/aws) - Import 3rd party PIP modules, specifically the AWS SDK, and integrate with AWS services


### PowerShell / PowerCLI

[Simple Action](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/powershell/simple-action) - Get to know how your PowerShell script can accept inputs and return output of different types

[Integrate 3rd party modules](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/powershell/3rd-party) - Import 3rd party PSGallery modules in your script

[List vSphere machines using PowerCLI](https://github.com/tgeorgiev/vro-polyglot-scripts/tree/master/powershell/vsphere) - Now we're talking



## Contributing
If you find any issue with the current scripts you can [create a issue](https://github.com/tgeorgiev/vro-polyglot-scripts/issues/new)

If you have any other Polyglot scripts that you want to share with the vRO community you can [create a pull request](https://github.com/tgeorgiev/vro-polyglot-scripts/compare)



## License
[MIT](https://github.com/tgeorgiev/vro-polyglot-scripts/blob/master/LICENSE)
