# Release notes

In this section we have summarised the changes to Umbraco Deploy released in each version. Each version is presented with a link to the [Deploy issue tracker](https://github.com/umbraco/Umbraco.Deploy.Issues/issues) showing a list of issues resolved in the release. We also link to the individual issues themselves from the detail.

If there are any breaking changes or other issues to be aware of when upgrading they are also noted here.

{% hint style="info" %}
If you are upgrading to a new major version you can find the details about the breaking changes in the [version specific updates](upgrades/version-specific.md) article.
{% endhint %}

## Release History

This section contains the release notes for Umbraco Deploy 13 including all changes for this version.

#### [**13.0.2**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.2) **(January 9th 2023)**

* Fixed issue with transfer of content using language variants [#193](https://github.com/umbraco/Umbraco.Deploy.Issues/issues/193)

#### [**13.0.1**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.1) **(December 21th 2023)**

* Fixes the display of the selected schedule date on queue for transfer.
* Fixes parsing property values within Nested Content and Block List that were previously saved by the Contrib value connectors.
* Fixed incorrectly including media files in export when 'Content files' wasn't selected.
* Add maximum file size validation to import file upload.

#### [**13.0.0**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.0) **(December 14th 2023)**

* All items from the 13.0.0 RCs and latest 12.2 features.

#### [**13.0.0-rc5**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.0) **(December 12th 2023)**

* Align with latest CMS RC.

#### [**13.0.0-rc4**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.0) **(December 11th 2023)**

* Add weight -100 to Deploy package migration (ensuring Deploy database tables are available before other package migrations are executed).
* Add fluent API for Deploy webhooks.

#### [**13.0.0-rc3**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.0) **(November 29th 2023)**

* Added optional deployment of webhooks as part of schema updates.
* Added Deploy specific webhook events.

#### [**13.0.0-rc2**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.0) **(November 15th 2023)**

* Exclude automatic relation type aliases (used for reference tracking) from deployment.
* Fix cyclic dependency between configuring `DeploySettings` and `ConnectionStrings`.

#### [**13.0.0-rc1**](https://github.com/umbraco/Umbraco.Deploy.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F13.0.0) **(November 6th 2023)**

* Compatibility with Umbraco 13:
  * See full details of breaking changes under the [version specific upgrade guide](upgrades/version-specific.md).
  * Update Richtext value connector to handle references in blocks.

## Legacy release notes

You can find the release notes for versions out of support in the [Legacy documentation release notes ](https://github.com/umbraco/UmbracoDocs/blob/umbraco-eol-versions/11/umbraco-deploy/release-notes.md)and[ Umbraco Deploy Package page.](https://our.umbraco.com/packages/developer-tools/umbraco-deploy/)

## [Deploy Contrib](https://github.com/umbraco/Umbraco.Deploy.Contrib)

{% hint style="info" %}
Deploy Contrib contains community contributions for Umbraco Deploy targetted for version 8 and above.

It offers connectors for the most popular Umbraco community packages. These are used by Deploy to aid with the deployment and transferring of content/property-data between environments.
{% endhint %}

#### Deploy Contrib 11.0.1 (February 14th 2023)

* Block grid editor support and fix for null reference exception (10+)
* Further caching for deploy operations.

#### Deploy Contrib 10.1.1 (February 14th 2023)

* Block grid editor support and fix for null reference exception (10+)
* Further caching for deploy operations.

#### Deploy Contrib 9.1.1 (February 14th 2023)

* Block grid editor support and fix for null reference exception (10+)
* Further caching for deploy operations.

#### Deploy Contrib 4.2.0, 9.1.0 and 10.1.0 (September 7th 2022)

* Used caching in value connectors to improve performance.
* Fixed issue with transfer of nested content string values using item templates (for example commencing with "\{{") that were erroneously considered as JSON.

#### Deploy Contrib 4.1.2, 9.0.2, 10.0.1 (July 12th 2022)

* Optimized existence checks in connectors

#### Deploy Contrib 4.1.1 (April 26th 2022)

* Fixes issue with deployment of nested content properties within Document Type grid editor values. [#82](https://github.com/umbraco/Umbraco.Deploy.Issues/issues/82)

#### Deploy Contrib 4.2.1 (February 21st 2023)

* All items listed under the 9.1.1, 10.1.1 and 11.0.1 releases (other than those indicated as only applying to higher versions).