+++
title = "Installing the library"
weight = 200
+++

## npm install

Before you can use the table viewer in your application, you'll need to install
the npm module:

```console
npm install cdk-dynamo-table-viewer@3.0.0
```

{{% notice info %}}

**Windows users**: on Windows, you will have to stop the `npm run watch` command
that is running in the background, then run `npm install`, then start
`npm run watch` again. Otherwise you will get an error about files being
in use.

{{% /notice %}}

Output should look like this:

```
+ cdk-dynamo-table-viewer@3.0.0
```

----

Now we are ready to add a viewer to our app.
