# ZR Performance Bundle Installation Guide

To install the ZR Performance Bundle, follow the steps below:

1. Ensure the below has been added to the `composer.json` **installer-paths**:
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
2. Run `composer require zr/zr-performance-bundle`
3. Run the following command (within the `/web` directory):

    ```sh
    ddev drush recipe recipes/custom/zr-performance-bundle
    ```

This command will execute the ZR Performance Bundle installation.
