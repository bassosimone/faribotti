# Processing Neubot data from M-Lab

## Install, configure, and use gsutil for archive-mlab-oti bucket

```
$ pip install gsutil
$ gsutil config
This command will create a boto config file at /Users/sbasso/.boto
containing your credentials, based on your responses to the following
questions.
Please navigate your browser to the following URL:
  [snip]
In your browser you should see a page that requests you to authorize access to
Google Cloud Platform APIs and Services on your behalf. After you approve, an
authorization code will be displayed.

Enter the authorization code: [snip]

Please navigate your browser to https://cloud.google.com/console#/project,
then find the project you will use, and copy the Project ID string from the
second column. Older projects do not have Project ID strings. For such projects,
click the project and then copy the Project Number listed under that project.

What is your project-id? archive-mlab-oti

gsutil developers rely on user feedback to make improvements to the
tool. Would you like to send anonymous usage statistics to help
improve gsutil? [y/N]

Boto config file "$HOME/.boto" created. If you need to use a proxy to access
the Internet please see the instructions in that file.gsutil config
$ gsutil ls -r gs://archive-mlab-oti/neubot/2018
```

