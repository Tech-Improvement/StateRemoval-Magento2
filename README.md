This simple extension allow you to hide US states where you don't ship in checkout

It's compatible with Magento 2.4.X CE, ECE, EE

intall using:

run composer require anduel/module-state-removal

run bin/magento setup:upgrade && bin/magento setup:di:compile && bin/magento setup:static-content:deploy -f

Set your states that you want to hide by going in Stores->Configurations->Anduel State Removal
