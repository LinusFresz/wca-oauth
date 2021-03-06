# wca-oauth
=======
# meteor-worldcubeassociation-oauth

This repository hosts two Meteor packages:
[jfly:accounts-worldcubeassociation](https://github.com/jfly/meteor-worldcubeassociation-oauth/tree/master/accounts-worldcubeassociation),
which depends on
[jfly:worldcubeassociation](https://github.com/jfly/meteor-worldcubeassociation-oauth/tree/master/worldcubeassociation).

This code is largely styled after the
[accounts-facebook](https://github.com/meteor/meteor/tree/devel/packages/accounts-facebook)
and [facebook](https://github.com/meteor/meteor/tree/devel/packages/facebook)
packages maintained by MDG.

## Quick Start

- Run `meteor add jfly:accounts-worldcubeassociation` in your Meteor project directory.
- If you weren't already using accounts in your project, see
  <https://www.meteor.com/accounts> for details on necessary things like the
  `accounts-ui` package.

## Example

- Check out the live demo at <http://wca-oauth-demo.meteor.com/>! Source code available [here](https://github.com/jfly/meteor-worldcubeassociation-oauth/tree/master/demo).

## Publishing accounts-worldcubeassociation or worldcubeassociation

- Edit `package.js` and bump version number.
- `meteor publish`

## Testing changes to accounts-worldcubeassociation

- Create a demo/packages directory, and create a symlink to accounts-worldcubeassociation in there:
```
~/gitting/wca-oauth/meteor @kaladin> ls -l demo/packages/
total 0
lrwxrwxrwx 1 jeremy jeremy 35 May 28 13:21 accounts-worldcubeassociation -> ../../accounts-worldcubeassociation
```
