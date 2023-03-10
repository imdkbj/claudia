# destroy

Undeploy the lambda function and destroy the API and security roles

## Usage

```bash
claudia destroy {OPTIONS}
```

## Options

*  `--profile`:  AWS profile that is locally configured
*   https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-profiles.html
    * _For example_: development-abcd
    * _Defaults to_: AWS default profile
*  `--source`:  (_optional_) Directory with project files
    * _Defaults to_: current directory
*  `--config`:  (_optional_) Config file containing the resource names
    * _Defaults to_: claudia.json
