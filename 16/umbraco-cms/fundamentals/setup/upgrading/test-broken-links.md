# Lychee Test File

## External links (valid)

- [Umbraco homepage](https://umbraco.com/)
- [Doc root](https://docs.umbraco.com/)

## Internal links (valid)

- [Property Editors](../../backoffice/property-editors/built-in-umbraco-property-editors/README.md)
- [Cloud Database](https://docs.umbraco.com/umbraco-cloud/expand-your-projects-capabilities/cloud-extensions/private-nuget-feed#step-3-publish-your-nuget-package)

## Internal anchors (valid)

- [Breaking changes](../../setup/upgrading/version-specific/README.md#find-your-upgrade-path)
- [Rich Text Editor Blocks](../../backoffice/property-editors/built-in-umbraco-property-editors/collection.md#order-by)
- [Relative link to directory](../../backoffice/)
- [Redirect link](https://docs.umbraco.com/umbraco-cms/customizing/foundation/working-with-data/store)
- [Image reference](../../../.gitbook/assets/are-you-hungry.png)

## Invalid Links

- [Training Link](https://umbraco.com/trainings)
- [Nonexistent Data Type](../../backoffice/property-editors/built-in-umbraco-property-editors/line.md)
- [Fake anchor](../../backoffice/property-editors/built-in-umbraco-property-editors/rich-text-editor/#blocks)

## Should Fail

## External links (invalid)

- [Broken external link](https://umbraco.com/thispagedoesnotexist)

## Internal links (invalid)

- [Nonexistent editor](../fundamentals/backoffice/property-editors/fake-editor.md)

## Internal anchors (invalid)

- [Fake anchor](../fundamentals/setup/upgrading/version-specific.md#this-anchor-does-not-exist)
- [Heading without file](upgrading/#breaking-changes) <!-- tricky case -->

## Mixed content

- [Relative link to dir](../fundamentals/backoffice/) <!-- may or may not pass -->
- [Image reference](../assets/images/logo.png) <!-- Lychee usually ignores unless configured -->

## Redirects (should pass if allow_redirect: true in .lychee.yml)

- [Redirecting link](https://umbraco.com/products/umbraco-cms/)