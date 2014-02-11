        ___    ____  ___    ____  ____  ____  ______
       /   |  / __ \/   |  / __ \/ __ \/ __ \/_  __/
      / /| | / /_/ / /| | / /_/ / / / / /_/ / / /
     / ___ |/ _, _/ ___ |/ ____/ /_/ / _, _/ / /
    /_/  |_/_/ |_/_/  |_/_/    \____/_/ |_| /_/

ARAPORT Profile
===============

This is a [Drush](https://github.com/drush-ops/drush) make file and Drupal
Installation Profile for the [Arabidopsis Information Portal](https://araport.org).


## Requirements

You will need Drush installed globally.

## Usage

First, you need to install Drupal and module dependencies.

    $> drush make araport.make path/to/install/directory

You can omit the install path to install in the current directory. This will
download Drupal and all dependencies and place them in the correct locations.

Next, you need to setup Drupal with the **araport** installation profile. Copy
the `profiles/araport` directory to `path/to/install/directory/profiles`. You
can now access the Drupal instance and select **Arabadopsis Information Portal**
as an Installation Profile option.