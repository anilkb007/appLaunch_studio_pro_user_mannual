# Apps and Frames

Everything you make is organised as **apps**, which contain **frames**. An
app can also hold **custom product pages**, each with its own frames.

## Apps

Each row in the **Folders** sidebar is one app: its icon (or a monogram
until you set one), its name, a storefront badge when it is linked to an App
Store Connect app, and the number of frames it contains.

- **Create** an app with the **+** button at the top of the sidebar. The
  **New App** sheet asks for a name and icon, and which default frames to
  create — either one per platform (**By platform**) or the full set of App
  Store screenshot sizes (**All App Store sizes**).
- **Select** the app row itself to work on its **App Version** — the
  screenshots for the app's main product page.
- **Right-click** an app for **Change App Icon…**, **Remove App Icon**,
  **Link to App Store Connect…** (or **Change App Store Connect Link…**),
  **Rename** and **Delete**.

> Deleting an app removes all of its frames and imported media immediately.
> There is no confirmation and no undo, so export anything you still need
> first.

## Custom product pages

Expand an app to see its **Custom Product Page** group. Custom product pages
are the alternative product pages App Store Connect lets you show to
different audiences; each one has its own set of frames.

- Right-click the group and choose **Add Custom Product Page**. The new page
  starts with one iPhone frame and its name ready to edit.
- Right-click a page for **Rename** or **Delete**.
- If the app is linked to App Store Connect, renaming a page creates or
  renames the matching custom product page in App Store Connect as well.

The **App Events** and **Product Page Header** entries are reserved for
upcoming features and currently show an empty state.

## Frames

The **Navigator** column lists the frames of the selected app or page. A
frame is a complete design — device, layout, background, text, localizations
and media — and it exports as one set of screenshots.

- **Create** a frame with the **+** button above the Navigator. In the
  **New Frame** sheet choose a **Platform**, then a **Device Frame** (grouped
  by screen size). The caption confirms the App Store size, for example
  *App Store size: 1320 × 2868 — iPhone 6.9″*. A new frame contains one
  empty screen.
- **Right-click** a frame for **Duplicate** (the copy is named *… Copy*),
  **Rename** and **Delete**.
- Frames keep their own device. Applying a template changes the layout, not
  the device.

## Auto-save

There is nothing to save. Every edit is written to disk about half a second
after you stop changing things, and the frame you are leaving is saved when
you select another one. The **Save Project** button in the Export card
forces an immediate save but is never required.

Your data lives in the app's Application Support folder, organised into
`projects`, `media`, `icons` and `templates`. Original screenshots are copied
into `media` when you import them, so you can move or delete the originals
afterwards.
