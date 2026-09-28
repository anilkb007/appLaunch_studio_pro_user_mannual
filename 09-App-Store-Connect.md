# App Store Connect

Connect the app to your App Store Connect account to browse your apps, link
them to your local designs, and upload finished screenshots and app previews
without leaving the app. All App Store Connect features need **Pro**.

## Getting an API key

App Store Connect authenticates with an API key that you create once.

::: steps

### Open Users and Access

Sign in to App Store Connect, choose **Users and Access**, then the
**Integrations** tab and **App Store Connect API**.

### Generate a key

Create a **Team Key** (or an Individual Key) with the **App Manager** or
**Admin** role. Give it a name you will recognise, such as *App Launch
Studio*.

### Download the .p8 file

Click **Download API Key** and keep the `.p8` file somewhere safe. App Store
Connect lets you download it **only once**.

### Note the IDs

Copy the **Issuer ID** shown at the top of the page and the **Key ID** shown
next to your new key. You will paste both into the app.

:::

## Connecting

Scroll to the **App Store** section at the bottom of the Folders sidebar and
click **Set up App Store Connect…** (or the gear icon). In the sheet:

1. Paste the **Issuer ID** and **Key ID**.
2. Click **Import .p8…** and pick the key file. The key is stored encrypted
   in your Mac's Keychain; the file itself is not kept.
3. Click **Save & Test**. The status line changes from *Not connected* to
   *Connected · N apps*.

For security the app does not connect on its own at launch — click **Connect
to App Store Connect** in the sidebar when you want to work with your
account during a session.

> **Disconnect** removes the key from the Keychain and clears the Issuer and
> Key IDs. You will need the `.p8` file again to reconnect, so keep it.

## Browsing your apps

Once connected, the App Store section lists your apps with a **Refresh apps**
button. Expand an app for its versions, then its languages and their
screenshot sets — a count when screenshots exist, or an orange warning where
a set still needs uploads. **Custom Product Pages** appear beneath, marked
Visible or Hidden.

- Right-click an app for **Link to App** or **Open Linked Folder**.
- Right-click a custom product page for **Publish (Make Visible)** or **Hide
  Page**.

## Linking an app

Linking connects one of your local apps to one App Store Connect app, so
uploads know where to go and renamed custom product pages stay in sync.

Right-click a local app in the Folders sidebar and choose **Link to App Store
Connect…**, then pick the App Store Connect app. The sidebar row gains a
storefront badge, and the app's icon is downloaded to use as the folder
icon. Use **Change App Store Connect Link…** to point it elsewhere.

## Uploading screenshots

Open **Upload to App Store Connect** from a linked app's frame and choose:

| Field | Meaning |
| --- | --- |
| **Destination** | **App Store Version**, an existing **Custom Page**, or **New Page** to create one |
| **Version** | The app version to attach the screenshots to |
| **Sizes** | Which App Store screenshot sizes to send (Duo sizes are marked *Export only*) |
| **Languages** | Which enabled locales to upload; missing languages are added to the app for you |
| **App Previews** | Also upload the frame's recordings |

A summary line confirms the plan; while uploading, each item shows its
progress, ending with *Finished · n uploaded, m failed*.

Uploads are **added** to the existing screenshot sets. Nothing is removed
from App Store Connect, so delete outdated screenshots there if you are
replacing a set. Uploaded files are named
`<name>_<locale>_<width>x<height>_<n>.png`.

If you see *This folder isn't linked to an App Store Connect app*, link the
app first as described above.

## Common errors

| Message | What to do |
| --- | --- |
| *Authentication failed (401)* | The key was revoked, or the Issuer ID or Key ID is wrong. Re-check the IDs, or create a new key. |
| *Not connected* after **Save & Test** | Make sure the `.p8` matches the Key ID and that your Mac is online. |
| A set still shows the orange warning after upload | Upload again for the missing size or language, or refresh with **Refresh apps**. |
