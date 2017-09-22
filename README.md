# Meeting Manager

Treat Meetings as a controlled document with workflow and closed-loop action item follow-up.

This package adds a "Meeting" ItemType under Portfolio in the TOC. This ItemType is intended to track the results, participants and action items from a Meeting.

The goal of this solution is to enable companies to keep a formal record of information that is often either undocumented or loosely controlled by meeting minutes.

Action items assigned during the Meeting result in notifications and reminders being sent via email, and a workflow activity that appears in the user's Innovator InBasket until the work is marked as complete.

## History

This project and the following release notes have been migrated from the old Aras Projects page. 

Release | Notes
--------|--------
[v1.3](https://github.com/ArasLabs/meeting-manager/releases/tag/v1.3) | Fixes an issue with long Action Item descriptions
[v1.2](https://github.com/ArasLabs/meeting-manager/releases/tag/v1.2) | Updated to work with 8.2.0 and 9.0.1
[v1](https://github.com/ArasLabs/meeting-manager/releases/tag/v1) | Initial Version

#### Supported Aras Versions

Project | Aras
--------|------
[v1.3](https://github.com/ArasLabs/meeting-manager/releases/tag/v1.3) | 8.2.0, 9.0.1
[v1.2](https://github.com/ArasLabs/meeting-manager/releases/tag/v1.2) | 8.2.0, 9.0.1
[v1](https://github.com/ArasLabs/meeting-manager/releases/tag/v1) | 8.1.1

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **meeting-manager** import packages

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\meeting-manager\Import\imports.mf` file in the Manifest File field.
6. Select all packages in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Created by Constantin Klein.

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE) for license rights and limitations.
