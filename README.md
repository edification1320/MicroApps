# MicroApps

This repository contains the Fabric and Visualizer projects implemented following the micro-apps style of building apps in Fabric and Visualizer.

# ResourcesMAExport.zip

This zip file is a Visualizer project, a microapp for holding the resources that will be used commonly across all the microapps. This does not have dependency on any other microapps.

# CommonsMAExport.zip

This zip file is a Visualizer project, a microapp for holding the common UI elements, like skins, themes, templates, components, that will be used commonly across all the microapps. This microapp has a dependency on ResourcesMA microapps.

# AuthenticationMAExport.zip

This zip file is a Visualizer project, a microapp for the Login functionality. This microapp has a dependency on CommonsMA microapps. This microapp will be linked into the EdificationBankCA composite app.

# AccountsMAExport.zip

This zip file is a Visualizer project, a microapp for the Accounts functionality. This microapp has a dependency on CommonsMA microapps. This microapp will be linked into the EdificationBankCA composite app.

# EdificationBankCAExport.zip

This is a composite app. This composite app does not have any functionality built into it. This composite app, will have links to AuthenticationMA and AccountsMA microapps.

# ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# AuthenticationMA (v1.0).zip

This zip file is a Fabric microapp, a microapp for Login functionality, it will have identity services defined as part of this Fabric microapp. This Fabric microapp will be linked to the Visualizer AuthenticationMA microapp.

# AccountsMA (v1.0).zip

This zip file is a Fabric microapp, a microapp for Accounts functionality, it will have integration services defined as part of this Fabric microapp. This Fabric microapp will be linked to the Visualizer AccountsMA microapp.

# EdificationBankCA (v1.0).zip

This is a composite Fabric app. This composite app does not have any services built into it. This composite app, will have links to AuthenticationMA and AccountsMA microapps.

# ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Environment used for developing these Visualizer and Fabric apps

V9SP5 version of Visualizer and Fabric.
