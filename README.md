# GTM Custom Template for trbo

## Overview

This is an unofficial Google Tag Manager [custom template](https://developers.google.com/tag-manager/templates) for the [trbo onsite personalization platform](https://www.trbo.com/). It allows tracking of all important data points along the on-site customer journey. In order to work, at least one tag in "Plugin code" mode must be integrated on every single page.

## Quickstart

Work on the template should be done in Google Tag Manager's native **template editor**. This is to ensure the template has access to all the latest features of the template editor, and to make sure it passes GTM's own validation when exporting the changes.

To **import** the template into Google Tag Manager:

1. In a Google Tag Manager **web** container (any container will do), browse to **Templates** and click to create a new template.
2. From the template action menu, choose **Import**.
3. Locate the `template.tpl` file from this repo, and import it into the template editor.

Make the changes you wish. Make sure the unit tests pass (in the **Tests** tab of the editor). Update the tests if necessary. 

Once you're done, follow these steps:

1. **Save** the template in the template editor.
2. From the action menu, choose **Export**.
3. Replace the `template.tpl` file in this repo with the exported file (make sure to keep `template.tpl` as its name)..
4. **Commit** the changes to the `template.tpl` file.
5. Copy the **commit hash**.
6. Edit `metadata.yaml` in the template folder, and add the hash with its `changeNotes` as the latest version.
7. Move the previous latest version into the list of `Older versions`.
8. Save changes to `metadata.yaml` and **commit** them.
9. Finally, push the changes to the repo (should include the commit to `template.tpl` and the commit to `metadata.yaml`).

After pushing the changes, Google Tag Manager should update the template in the [community gallery](https://tagmanager.google.com/gallery/#/) within some hours to some days.

Also see [detailed instructions on how to submit templates to the Community Template Gallery](https://developers.google.com/tag-manager/templates/gallery).

## Copyright and license

This tag template is based on the great work for [Facebook Pixel custom template](https://github.com/facebookarchive/GoogleTagManager-WebTemplate-For-FacebookPixel) by Simo Ahava.

Original copyright 2019 Simo Ahava. Modifications copyright 2022 Norman Höhne.

Licensed under the **[Apache License, Version 2.0](LICENSE)** (the "License");
you may not use this software except in compliance with the License.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.