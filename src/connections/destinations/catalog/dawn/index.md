---
title: Dawn Actions Destination
---

{% include content/plan-grid.md name="actions" %}

[Dawn](https://www.dawnai.com/){:target="_blank”} destination integration allows you to connect and target your Segment audiences with Dawn.

## Getting started

### Get Dawn Account Details

Before connecting the **Dawn (Actions)** destination you'll need your **Write Key** - You can get your write key at [app.dawnai.com](https://app.dawnai.com/) or by contacting Dawn Support.

### Create and Connect the Dawn Destination

1. From your Segment workspace's [Destination catalog page](https://app.segment.com/goto-my-workspace/destinations/catalog){:target="_blank”} search for **Dawn AI**.
2. Select **Dawn AI** and click **Add Destination**.
3. On the **Basic Settings** screen input the Taboola **Client ID** and **Client Secret** values.
4. Select the source to send events to Dawn from and click **Next**.
5. On the setup screen, give your new Dawn AI destination an name and ensure **Actions** is selected from the Destination framework. Click **Create destination**.
6. The destination will be created and you will be redirected to the **Settings** tab where there is a **Basic Settings** section.
7. In the **Write Key** field, enter your Dawn write key. 
8. Toggle the **Enable destination** switch and click on **Save Changes**. 
9. If you face issues with saving changes (eg. invalid credentials) please contact Dawn Support.

The Events will start to sync to Dawn shortly.

## Supported event types

1. **Track** - Used to record any actions your users perform, along with any properties that describe the action. The Track event type maps directly to Dawn's `track` endpoint. 
1. **Identify** - Lets you tie a user to their actions and record traits about them. The Identify event maps directly to Dawn's `identify` endpoint.
