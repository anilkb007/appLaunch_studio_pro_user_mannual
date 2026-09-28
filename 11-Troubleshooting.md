# Troubleshooting

Quick answers to the questions we hear most. If yours is not here, the
relevant page of this guide has more detail on each feature.

## Design and canvas

| Symptom | Cause | Fix |
| --- | --- | --- |
| My screenshot does not fill the device's screen | The image was taken on a different device or cropped | Use a screenshot from the matching simulator or device, or adjust **Fine-tune screen rect** in the Device Frame card |
| Clicking the canvas moves things around | **Move** mode is on | Click **Move** above the canvas (or double-click the canvas) to switch it off |
| I cannot rotate the device | The recording slot is selected, or the frame is in 3D | Rotation applies to screenshot slots in 2D; in 3D drag the model or use **Tilt**, **Turn** and **Roll** |
| The Orientation control is missing | Only iPad frames rotate | iPhone frames are portrait and Mac frames are landscape by design |
| **3D frame** is greyed out or missing | The device has no 3D model, or you are on the free plan | 3D is available for iPhone 17 Pro Max, iPhone 18 Pro Max, iPhone Duo and MacBook Pro 16″ with **Pro** |
| Changing platform undid my design | Switching platform resets device, size and 3D | Duplicate the frame first if you want to try another platform |
| A template wiped my translations | Templates replace title and subtitle in every language | Duplicate the frame before applying a template |

## Localization

| Symptom | Cause | Fix |
| --- | --- | --- |
| Auto-translate does nothing or is unavailable | Apple Intelligence is off or unsupported | Turn on Apple Intelligence in **System Settings** (macOS 26 or later) |
| Some languages stay empty after translating | Apple Intelligence supports about 29 App Store languages | Type those translations by hand, in the Localization tab or the Localized Editor |
| The canvas shows the wrong language | The **Language** pop-up chooses the preview language | Pick the language you want to check above the canvas |

## Export

| Symptom | Cause | Fix |
| --- | --- | --- |
| **Export Current** is disabled | The free plan's export allowance is used up | Wait for the hourly window, or subscribe to Pro |
| *Export failed* alert | The destination is not writable, or a media slot is empty | Choose another folder and make sure each slot has an image |
| My recording cannot be exported | App previews must be 15–30 seconds | Trim the recording; clips under 15 s can still be exported with **Export Anyway** |
| The export size is wrong | The Export card preset does not match the device | Choose the correct preset — the canvas badge shows the size that will be written |

## App Store Connect

| Symptom | Cause | Fix |
| --- | --- | --- |
| *Authentication failed (401)* | Wrong Issuer ID or Key ID, or the key was revoked | Re-check the IDs in **Users and Access ▸ Integrations**, or create a new key |
| The sidebar says *Not connected* after relaunch | The app never connects automatically | Click **Connect to App Store Connect** in the App Store section |
| *This folder isn't linked to an App Store Connect app* | Uploads need a linked app | Right-click the app and choose **Link to App Store Connect…** |
| I clicked **Disconnect** and now need my key | Disconnect deletes the key from the Keychain | Import the `.p8` again; if you no longer have it, create a new key in App Store Connect |
| Duo sizes show *Export only* in the upload sheet | App Store Connect does not yet accept iPhone Duo screenshots | Export them for later; upload the other sizes now |

## Subscription

| Symptom | Cause | Fix |
| --- | --- | --- |
| Pro features are locked after reinstalling | The entitlement has not been re-read yet | Open **Subscribe to Pro…** and click **Restore Purchases** |
| Features unlocked on one Mac but not another | Different Apple ID, or not yet refreshed | Sign in with the same Apple ID and restore purchases |

## Still stuck?

Choose **About App Launch Studio Pro** from the app menu to find your version
and build number, and include them when you get in touch.
