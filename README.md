<p align="left"> <img title="Alfresco AQuA" src="v1.120.png" alt="Alfresco AQuA - Keep your content AUTOMAGICALLY organized"></p>
Simplifying Alfresco UX with Enterprise prod-ready features (ACA/ADF powered)

## Introduction

Multidevice Smart Workspace for content (ECM) and processes (BPM) AI assisted. Helping with your Digital Transformation process and strategy. Supported by [Venzia IT](https://venzia.es).</br>
Alfresco [AQuA](https://aqua.venzia.es) is built using [Alfresco Application Development Framework (ADF)](https://github.com/Alfresco/alfresco-ng2-components) components and was generated with [Angular CLI](https://github.com/angular/angular-cli).

## Features added in the latest release

* Companies/Departments/Sites Management and selector
  * User and content isolation
  * Entity selection for users that belongs to several entities
* Highligthed search terms in results and preview
* Datarooms feature to share folder with external users quickly.

## Available Features

| Feature                        | Description                                                        |
|--------------------------------|--------------------------------------------------------------------|
| My Tasks | Manage Alfresco Activiti embeded or standalone Tasks (available for Flowable BPM too)|
| Chatbot | Talk to Alfresco to execute your daily common actions as search, share or assign a task|
| Datalinks | Link your database information with Alfresco content easly, to enhance search capabilities or provide a two ways integration method.|
| Dashboard | Summary page about your repository content.

Please refer to the [release notes](https://github.com/venziait/aqua/releases) for details of all changes.

#### High level feature themes planned for 2020

* Collaboration & File Management
  * Google Docs edition
  * Digital Signature (web based)

# Alfresco Content Application (ACA)

Testing Supported By<br/>
<img width="160" src="docs/images/Browserstack-logo.svg" alt="BrowserStack"/>

#### What's new in the latest release

- Single Log Out
- WCAG AA accessibility improvements

Please refer to the [release notes] for details of all changes.

#### High level feature themes under consideration for future releases

- Extensibility
  - Building on the existing framework to further enhance the developer experience
- Collaboration & File Management
  - Folder rule creation
  - File/Folder linking via secondary association
- File Library Management
- Enhanced UI and user experience
  - Accessibility WCAG AA compliance
  - Search query input assistance
  - Metadata information drawer enhancements

### Want to help

Want to file a bug, contribute some code, or improve documentation? Excellent!
Read up on our guidelines for [contributing] and then check out one of our issues in the [Jira] or [GitHub].

## Compatibility

| ACA Version | Built with | Tested on |
| ----------- | ---------- | --------- |
| ACA 1.9     | ADF 3.6.0  | ACS 6.2   |
| ACA 1.8     | ADF 3.3.0  | ACS 6.1   |
| ACA 1.7     | ADF 3.0.0  | ACS 6.1   |
| ACA 1.6     | ADF 2.6.1  | ACS 6.1   |
| ACA 1.5     | ADF 2.6.0  | ACS 6.0   |
| ACA 1.4     | ADF 2.5.0  | ACS 6.0   |
| ACA 1.3     | ADF 2.4.0  | ACS 6.0   |
| ACA 1.2     | ADF 2.3.0  | ACS 5.2   |
| ACA 1.1     | ADF 2.2.0  | ACS 5.2   |
| ACA 1.0     | ADF 2.0.0  | ACS 5.2   |

## Available Features

| Version | Feature                    | Description                                                                                                                                                                                    |
| ------- | -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1.5     | My Files                   | Folder/File browsing of Personal Files.                                                                                                                                                        |
| 1.5     | File Libraries             | Create, find, join and browse the file libraries of sites created in the repository.                                                                                                           |
| 1.5     | Shared Files               | Lists all files that have shared.                                                                                                                                                              |
| 1.5     | Recent Files               | List files created and/or modified by the logged users within the last 30 days.                                                                                                                |
| 1.5     | Favorites                  | Lists all favorite files for the user.                                                                                                                                                         |
| 1.5     | Trash                      | Lists all deleted items stored in the trash can, users can restore or permanently remove. Admin user will see items deleted by all users.                                                      |
| 1.5     | Upload                     | Files and folders can be uploaded through the New button or by dragging and dropping into the browser.                                                                                         |
| 1.5     | Search                     | Quick search with live results, and full faceted search results page.                                                                                                                          |
| 1.5     | Actions                    | A number of actions can be performed on files and/or folders, either individually or multiples at a time.                                                                                      |
| 1.5     | Viewer                     | Viewing files in natively in the browser, unsupported formats are transformed by the repository.                                                                                               |
| 1.5     | Metadata                   | The information drawer can be configured in the app.config.json to display metadata information, by default file the Properties Aspect is shown and images will also include EXIF information. |
| 1.5     | File Sharing               | Share files, with time expiry if required, externally with uniquely generated URLs.                                                                                                            |
| 1.5     | Versioning                 | The version manager provides access and management of previous file versions, and the ability to upload new versions.                                                                          |
| 1.5     | Permissions                | Granular user permission management of the folders and files throughout the repository.                                                                                                        |
| 1.5     | Extensibility              | The application provides safe extension points allowing full customisation; see [Documentation](https://alfresco-content-app.netlify.com/#/extending/) for details.                            |
| 1.6     | Library management         | Join and favorite libraries. New search input to find Libraries, files and/or folders.                                                                                                         |
| 1.7     | Edit Offline               | Lock and unlock for editing, download current version, upload new version.                                                                                                                     |
| 1.7     | Edit with Microsoft Office | Extension to edit online with Alfresco Office Services (AOS)                                                                                                                                   |
| 1.7     | Single Sign-On (SSO)       | Support for Alfresco Identity Service, with ADF 3.0.0    |        
| 1.7     | Search Query Language      | Enhanced search input using the Alfresco Search Query Language    | 
| 1.8     | Localizations .            | Arabic, Czech, Danish, Finnish, Polish and Swedish |
| 1.8     | Metadata improvements      | Automatic display of aspects and properties |
| 1.8     | Search facet improvements  | Facet intervals and grouped facet queries |
| 1.8     | Extensibility improvements | Various - see [release notes](https://github.com/Alfresco/alfresco-content-app/releases) for details |
| 1.9     | Single Log Out | Users will be automatically logged out from the Content App after logging out from another application in the same browser session | 
| 1.9     | Accessibility improvements | Various - see [release notes](https://github.com/Alfresco/alfresco-content-app/releases) for details | 

[contributing]: https://github.com/Alfresco/alfresco-content-app/blob/master/CONTRIBUTING.md
[github]: https://github.com/Alfresco/alfresco-content-app/issues
[jira]: https://issues.alfresco.com/jira/projects/ACA
[release notes]: https://github.com/Alfresco/alfresco-content-app/releases
