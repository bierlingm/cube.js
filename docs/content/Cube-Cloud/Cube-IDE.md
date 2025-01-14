---
title: Cube IDE
permalink: /cloud/cube-ide
category: Cube IDE
menuOrder: 1
---

With Cube IDE, you can write and test and you Cube.js Data Schema from your
browser. Cube Cloud can create branch-based develolment API instances to test changes in the data schema
in your frontend applications before pushing them into production.

<div style="position: relative; padding-bottom: 60.504201680672274%; height: 0;"><iframe src="https://www.loom.com/embed/101b6291b0ba4d1d8982faa3b8c5bd55" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

## Development Mode

In development mode, you can safely make changes to your project without affecting production deployment. Development mode uses a separate Git branch and allows testing your changes in Playground or via a separate API endpoint specific to this branch. This development API hot-reloads your schema changes, allowing you to quickly test API changes from your applications.

To enter development mode, navigate to the **Schema** page and click **Enter
Development Mode**.

![](https://raw.githubusercontent.com/cube-js/cube.js/master/docs/content/Cube-Cloud/enter-dev-mode.png)

When development mode is active, a grey bar will be visible on the top of the screen. It provides
several useful controls and indicators:
* The name of the current development Git branch
* The status of the development API. After any changes to the project, the
  API will hot-reload changes and the API status will show it.
* "Copy API URL" will copy the API URL to the clipboard for the current development branch.

You can exit development mode by clicking **Exit** button in the grey banner.

![](https://raw.githubusercontent.com/cube-js/cube.js/master/docs/content/Cube-Cloud/dev-mode-bar.png)
