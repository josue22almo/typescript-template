How to use:

1. Create new repo using this template

    https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template

2. Install dependencies

    ```
    yarn
    ```
3. Rename the project

    - Rename dynamic values:
    ```
    src/apps/config/constants

    export const microserviceName = "escher-microservice-skeleton"
    ```
    - Rename static values:

    ```
    Search/Replace escher-microservice-skeleton
    ```
    - Rename package name:

    ```
    //package.json
    name: "some-project-name"
    ```

3. Done! `yarn test` should pass

4. Find errors in this repository or guide and update it!