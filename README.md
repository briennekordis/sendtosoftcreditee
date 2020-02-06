# This extension is deprecated
In CiviCRM 5.23+ and CiviRules 5.12+, support for the "Soft Credit is added/changed/deleted" tokens exist.  There's no longer a need for a CiviRule action on the contribution; you can use the existing "Send Email" action provided by the Email API extension with a soft credit trigger.

## sendtosoftcreditee

This extension adds a new CiviRules action, "Send E-mail to Soft Creditee".

The extension is licensed under [AGPL-3.0](LICENSE.txt).

## Requirements

* PHP v7.0+
* CiviCRM 5.16+

## Installation (Web UI)

This extension has not yet been published for installation via the web UI.

## Installation (CLI, Zip)

Sysadmins and developers may download the `.zip` file for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
cd <extension-dir>
cv dl sendtosoftcreditee@https://github.com/FIXME/sendtosoftcreditee/archive/master.zip
```

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/FIXME/sendtosoftcreditee.git
cv en sendtosoftcreditee
```

## Usage

After install, you will find a new CiviRule action on contributions, "Send E-mail to Soft Creditee".  Configure it identically to a typical "Send E-mail" action.
