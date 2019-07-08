# Going live

## Configure Domain

You will need to configure your registered domain on your Platform.sh project before going live, and you can do that either through the management console or by using the CLI.

## Through the management console

<video controls>
  <source src="/videos/management-console/set-domain-mc.mp4" type="video/mp4">
</video>

Now that you have changed your project to a production plan, you can click the same "Go live" button at the top of the project page. Alternatively, you can click "Settings" at the top of the page, and then visit the "Domains" section on the left.

Click the "Add+" button in the top right hand corner of the page, enter your registered domain and select if you want it to be the default domain for the project. You can add multiple domains to a project, but only one can be set as the default.

When you're finished, click "Add domain", and the project will once again redeploy to apply your changes.

## Using the CLI

You can also add a domain to your project using the Platform.CLI. From a terminal window, type the command

```bash
platform domain:add example.com --project <project ID>
```

The CLI will validate your registered domain and provision Let's Encrypt certificates for it.

<div class="buttons">
  <a href="#" class="prev-link button-link">Back</a>
  <a href="#" class="next-link button-link">I have configured my registered domain on my project</a>
</div>
