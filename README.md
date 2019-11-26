# Contentful Tables

An ui-extension to add an editable table to handle tabular data as a [Contentful UI Extension](https://www.contentful.com/developers/docs/concepts/uiextensions/).

### ⚙️ Setup field Content Models

Add JSON Object field  
![figure](https://github.com/AnalogMemory/contentful-tables/blob/master/images/setup1.png "Add JSON Object field")

Configure appearance to use **Contentful Tables**  
![figure](https://github.com/AnalogMemory/contentful-tables/blob/master/images/setup2.png "Configure appearance")

### 📝 Editing Table

![figure](https://github.com/AnalogMemory/contentful-tables/blob/master/images/demo.gif "Editing the table")

## ✅ Easy Installation in Contentful Web App

* In the contentful web app to to `Settings > Extensions`
* Click the `Add extension`
* Choose `Install from Github`
* Paste this link `https://github.com/AnalogMemory/contentful-tables/blob/master/extension.json`

### Manual Installation

```sh
git clone https://github.com/AnalogMemory/contentful-tables.git
cd contentful-tables
npm install
```

### Configure

Create a configuration file with your credentials for Contentful.

```sh
cp .env.example .env
```

Open `.env` in a editor of your liking and add your Contentful space ID, and management token. [Learn how to obtain a token](https://www.contentful.com/developers/docs/references/authentication/#getting-an-oauth-token).

Load environment variables

```sh
source .env
```

### Create

```sh
npm run create
```

Create task will register the extension in your space on Contentful.

### Update

```sh
npm run update
```

Update task will upload the extension to your space on Contentful.

## License

Copyright &copy; Contentful Developer Relations

Licensed under the [MIT license](https://github.com/contentful-labs/ui-editable-table/blob/master/LICENSE).
