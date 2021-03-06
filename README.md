# metal-sweeper

Experimental Github Action for managing [Equinix Metal](https://metal.equinix.com) Projects.

> :bulb: See also:
> * [equinix-metal-project](https://github.com/displague/metal-project-action) action
> * [equinix-metal-examples](https://github.com/displague/metal-actions-example) examples

Given a Equinix Metal User API Token and a Project ID, the project will be deleted with all resources in that project.

Create a project with the [Equinix Metal Project Action](https://github.com/displague/metal-project-action).

See the [Equinix Metal Actions Example](https://github.com/displague/metal-actions-example) for usage examples.

## Input

With | Environment variable | Description
--- | --- | ---
`userToken` | `METAL_AUTH_TOKEN` | (required) A Equinix Metal User API Token
`projectID` | `METAL_PROJECT_ID` | (required) Project ID that will be deleted.
`keepProject` | `KEEP_PROJECT` | When set to the default of `false`, the project will be deleted after all project contents are deleted.

## Output

There are no outputs.
