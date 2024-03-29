# Appcircle _Custom Script_ component

You can use custom scripts for additional functionalities in your builds. Appcircle will run the commands in your custom scripts and perform the specified actions. These scripts will be run on the build agent and you can use any functionality of the virtual machine as you need.

Custom scripts can be written in Bash or Ruby. To add your own script, click on the custom script you want to edit in the workflow editor.

You can use the script editor area to add your own script and click Save button to save your script.

## Using environment variables

You can use environment variables in your custom scripts. Workflow steps can generate return values and these values can be used in the following workflow steps as well as custom script steps. 

You can use your own environment variables in custom scripts. For this purpose, create an environment variable group in the Appcircle Build module and add your own variables with key/value pairs.

Please refer to the following document for more information about managing environment variables: https://docs.appcircle.io/environment-variables/managing-variables

For a list of Appcircle-specific environment variables, please refer to the following documentation:  https://docs.appcircle.io/environment-variables/appcircle-specific-environment-variables

## Input Variables

### Required

- `Execute`: Script to execute with. For example bash or ruby.

### Optional

- `Script`: Script to execute.

## Relationship

Below workflow steps are related with this step and should be used as recommended.

### Required Steps

There is no required step that needs to be run beforehand for this step to work as expected.

### Preceding Steps

There is no preceding step advised to be run beforehand for this step to work as expected.

### Following Steps

There are no subsequent steps advised to be run for this step to work as expected.
