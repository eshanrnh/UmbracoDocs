
# Test file for Umbraco documentation

this file contains a bunch of common errors and styleguide issues to test automations

## Acronyms and abbreviations

the CMS (content management system) is sometimes called CMS but its best to define it first.  
dont confuse API and api usage. also, abbreviations like SQL or HTML should be capitalized.  
Simple Mail Transfer Protocol (SMTP) stands for Simple Mail Transfer Protocol and should be spelled out on first use.

## Punctuation mistakes

- Missing periods in list items  
- Inconsistent comma usage, like this, or this  
- Double spaces after periods. like this.

## Repeated repeated words and typos

This is a test test to see if repeated repeated words can be caught.  
The the system should flag those those mistakes.

## Lists capitalization inconsistency

- First item with lowercase  
- Second Item starting with uppercase  
- third item with lowercase again  
- `cmd`

1. Numbered list item one  
2. numbered list item two (lowercase start)  
3. Numbered List Item Three (uppercase start)

## Contractions and informal language

Don't use contractions like can't, won't, shouldn't in official docs.  
It's better to write do not, will not, should not.  
gonna test informal language like gonna and kinda too.

## Passive voice vs active voice

The content is managed by the admin.  
Users are allowed to edit their profiles.  
Errors are fixed by developers quickly.

## Incorrect links and formatting

Check out https://umbraco.com/cloudportal for more info.  
Also see [for more info](cloudportal.md) <- relative link missing slash  
[Broken Link](../docs/not-exist.md)  
Inline code without backticks like this public void Test() is wrong.

## Code block without language

```
function test() {
  console.log("hello");
}
```

## Image without alt text

![](../images/umbraco-logo.png)

## Mixed terminology usage

Use umbraco CMS or Umbraco cms or umbraco Cloud portal inconsistently.

## Email and Umbraco mentions

Please contact support@umbraco.com for help.  
This is a simple example to check email and Umbraco references.

## Long sentences with run on punctuation!!!

This sentence, has too many commas, and periods... and ellipsis... and it just keeps going on and on and on and on without stopping

## Extra spaces and tabs

This line has two spaces at the end.  
This line has a	tab character.

---

End of the test file.  
