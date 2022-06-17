Contributing
------------

## Contribution Workflow

Whether you are reporting a bug or would like to see the addition of a new feature:

1. Open an issue
2. Respond to questions asked by the maintainer.
3. When ready, test the fixed version of the plugin. Let the maintainer know whether it works or describe any new/existing related issues.

If you have decided to do development yourself:

4. Fork the repository to your own GitHub account.
5. Clone your fork into your local instance of Moodle.
6. Develop and test your code changes. If you are adding a new feature, update the documentation.
7. Complete the testing described in the Style Guide section of this document.
8. Format your commit message as follows: Fix-xxx: Short messages describing the changes (where xxx is the issue number in GitHub).
9. If you created multiple commits, squash them into one commit.
10. Push your change to your fork.
11. Create a pull request (PR).
12. In the description of the PR, reference the issue number that this PR is addressing.

The rest of this document describes some of these steps in further detail.

## Opening an issue

**IMPORTANT**: You must open a new separate issue for each individual bug and feature request.

Whether you believe you found a bug or you would like to request a new feature, open a new issue in the issue tracker to start the discussion with the plugin's maintainer. There are several reasons for doing this. For example, it is possible that someone else is already working on your idea, your approach is not quite right, or that the functionality exists already. The ticket you submit in the issue tracker will be used to work that all out.

If you intend to develop and submit a pull request yourself, indicate this in your ticket so that multiple people don't end up working on the same issue at the same time. This will also create an opportunity to open a dialogue with the plugin maintainer to improve your changes of the fix or new feature being integrated down the road.

Keep in mind that the maintainer always get final say on whether new code will be integrated into the project.

If you are in a hurry to get the new feature or fix a bug, contact the maintainer directly and hire them to do the work. If the maintainer is not available, ask the maintainer to refer you to a developer who will be able to help you with your requirements.

### Reporting a bug

When submitting a new issue to report a bug, be sure to include the following information:

1. Description of the issue.
2. What you expected to happen.
3. Provide detailed steps on how to reliably reproduce the issue.
4. Specify the exact version of Moodle you are using.
5. Specify the exact version of the plugin you are using.
6. Specify the theme you are using - only required if the issue cannot be reproduced using the Boost theme.

### Requesting a new feature

When requesting a new feature:

1. Prefix the subject line with "Feature request: "
2. Describe the new functionality you would like to see added to the plugin.
3. Include a real-life example of why and how you will be using it (i.e. business requirement or user story).

## Style Guide

When developing code, always be sure to:

1. Ensure files are encoded in UTF-8.
2. Follow the official [Moodle Coding Style Guide](https://moodledev.io/general/development/policies/codingstyle).
3. Fully test your code's functionality with Moodle **Debug Messages** setting set to **DEVELOPER: extra Moodle debug messages for developers** and the **Display debug messages** setting checked. Ensure that there are no errors or warnings at all!
4. Test your code using the [Moodle Code Checker](https://moodle.org/plugins/local_codechecker) and [Moodle PHPdoc check](https://moodle.org/plugins/local_moodlecheck) plugins. Ensure that there are no errors or warnings at all.
5. Look at the existing style and adhere accordingly.
6. Add useful PHPUnit tests and make sure that it passes the test.
7. Updated the documentation if needed and make sure it is readable.

## Making a Pull Request

Once you have made all your changes, tested it thoroughly and updated the documentation, push it to your GitHub fork and make a pull request. Be sure to reference the original issue in the pull request. Expect some back-and-forth with regards to style and compliance of the Style Guide.

## Versioning

We use [SemVer](http://semver.org/) for versioning.
