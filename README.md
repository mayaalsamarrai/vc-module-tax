# vc-module-tax

## Overview

The tax module is an engine for tax calculations and allows doing the following:

1. Extend the custom tax providers;
1. Tax providers registration using the code;
1. Display the list of available tax providers on UI;
1. Edit tax provider settings on UI;
1. Connect the tax providers to the selected Store;

## Scenarios

### View Tax Provider

1. Go to More->Stores->select the Store;
1. On Store details blade select the 'Tax providers' widget;
1. The list available tax providers will be displayed on 'Tax providers' blade;
1. Select a tax provider from the list;
1. The following details will be displayed: 

     1. Tax provider name;
     1. Tax provider code;
     'Is active' button- used to activate or de-activate the tax provider;
     1. 'Settings' widget.

![Tax providers](docs/media/screen-tax-providers.png)
![Tax providers details](docs/media/screen-tax-provider-details.png)

### Edit Tax Provider Settings

1. Select the 'Settings' widget on tax provider details blade;
1. The following default settings can be edited on UI if needed:

     1. Company code in Avalara system;
     1. Link to Avalara API service;
     1. Link to Avalara admin page.
1. Save the changes if any editing was made.

![Tax provider settings](docs/media/screen-tax-provider-settings.png)
