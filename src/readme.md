# SRC Folder

## Folder Structure
```
├── assets
│   ├── file
│   ├── icons
│   └── ilustrations
├── components
│   ├── atoms
│   ├── modals
│   └── molecules
├── config
│   ├── redux
│   └── router
├── pages
│   └── ...
├── parameter
│   ├── aws
│   ├── date
│   ├── filterList
│   ├── global
│   ├── localData
│   ├── mask
│   ├── menu
│   ├── page
│   ├── path
│   ├── progressStep
│   ├── roles
│   └── status
├── services
│   ├── auth
│   ├── aws
│   ├── data
│   ├── generate
│   ├── localData
│   ├── localStorage
│   ├── location
│   └── pickers
└── utils
    ├── colors
    ├── customController
    ├── data
    ├── date
    ├── fonts
    ├── regex
    ├── showMessage
    ├── styles
    └── validate
```

## Assets
contains files or image assets that will be used statically in the app.

| Folder   | Description                       |
| :--------  | :-------------------------------- |
| `file` | contains the files to be used for the application |
| `icons` | contains the files icon or mini image to be used for the application |
| `ilustrations` | contains the files image to be used for the application |


## Components

| Folder   | Description                       |
| :--------  | :-------------------------------- |
| `atoms` | contains the basic components which will then be used to build application views or be used in molecules components |
| `modals` | contains dynamic modal components that can be used as base modals based on the condition of the properties that have been installed |
| `molecules` | contains a collection of several component atoms that have been arranged to be used as one dynamic component |

## Config

| Folder   | Description                       |
| :--------  | :-------------------------------- |
| `redux` | contains state global management setting REDUX |
| `router` | contains path routing page application |


## Pages
Contains all the page folders shown on the application

## Parameter
contains path or static parameters used in the application

| Folder   | Description                       |
| :--------  | :-------------------------------- |
| `aws` | contains all parameters that use on aws service |
| `date` | contains parameter data date |
| `filterList` | contains parameter data list for filter |
| `global` | contains parameter data const for global |
| `localData` | contains parameter data const for parameter name to save be a lazy data in local data |
| `mask` | contains parameter const for masking data by regex |
| `menu` | contains data list data, icon, name and route menu |
| `path` | contains const path for accessing API endpoint |
| `progressStep` | contains data array point for step progress on form |
| `roles` | contains data dummy user for login and user roles |
| `status` | contains data status data on feature menu |

## Services
contains function service for access API or processing data

| Folder   | Description                       |
| :--------  | :-------------------------------- |
| `auth` | contains function for authentication |
| `aws` | contains function for manage data AWS |
| `data` | contains function for manage data API by model endpoint |
| `generate` | contains function for generating data (ex: pdf) |
| `localData` | contains function manage or access default data local |
| `localStorage` | contains function manage or access default data local |
| `location` | contains function manage service location |
| `picker` | contains function manage picker service |

## Utils
contains function, style, and data global

| Folder   | Description                       |
| :--------  | :-------------------------------- |
| `colors` | contains data color theme |
| `customController` | contains custom hook for controlling data |
| `data` | contains function for processing or manage data |
| `date` | contains function manage data date |
| `fonts` | contains function and data for manage fonts |
| `regex` | contains function validate data using regex |
| `showMessage` | contains function show message data |
| `styles` | contains function and data for manage styling |
| `validate` | contains function for validate form |