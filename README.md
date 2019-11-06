# App Script Deployment using Clasp

### CLASP CODELAB

Reference: https://codelabs.developers.google.com/codelabs/clasp/#0

#### Install clasp

```
npm i @google/clasp -g
```

#### Create a clasp title

```
clasp create --title "Clasp Codelab";
```

#### Clone AppScript project

```
clasp clone <SCRIPT_ID
```

#### Open project on script.google.com

```
clasp open
```

#### Push & pull remote code

```
clasp push

clasp pull
```

#### Versioning and Deployment

You can create a version using:

```
clasp version "Initial Version"
```

You can list multiple versions using:

```
clasp versions
```

You can deploy a specific version using:

```
clasp deploy 1 "Initial Deployment"
```

#### Sequence of steps pre-deployment of add-on

- clasp version '_VERSION_NAME_'
- clasp push
- clasp deploy _VERSION_ID_ '_DEPLOYMENT_NAME_
