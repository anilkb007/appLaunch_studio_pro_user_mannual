# Device Frames

The **Device Frame** card in the inspector controls which device your
screenshot sits in, where it sits, and whether it is drawn flat or as a
rotatable 3D model.

## Choosing a device

Pick a **Platform**, then a device from the frame picker. The canvas badge
and the Export card update to the matching App Store size.

| Platform | Bundled devices |
| --- | --- |
| iPhone | iPhone 16, iPhone 17, iPhone 17 Pro, iPhone 17 Pro Max, iPhone 18 Pro, iPhone 18 Pro Max, iPhone Air, iPhone Duo |
| iPad | iPad Pro (M5) 11″ and 13″ — Silver and Space Black |
| Mac | MacBook Pro 14″ and 16″, MacBook Air (M5) 13″ and 15″ |

Most devices come in several colours; each colour is its own entry in the
picker.

> Changing the **Platform** resets the frame and export size and switches
> 3D off on every screen of the frame.

### Orientation

- **iPad** frames have an **Orientation** control: Portrait or Landscape.
- iPhone and Mac frames are fixed — iPhone is portrait, Mac is landscape.

### iPhone Duo displays

The foldable iPhone Duo has a **Display** picker instead of an orientation
control: **Inner Open**, **Inner Open Landscape**, **Outer Closed**, **Outer
Closed Landscape** and **Outer Open**. Each display uses its own screenshot
slot, so the inner and outer screens can show different images.

## Frame slots — up to three devices

A screenshot can show more than one device, for example a phone in front of
a tablet. Use the **Frame slot** picker to switch between **Frame 1
(primary)**, **Frame 2** and **Frame 3**. The **+** button adds a slot and
the remove button deletes the selected one. Each slot has its own device,
size, position and rotation.

Adding a second or third frame is a **Pro** feature.

## Placing a flat (2D) frame

With **3D frame** switched off, these sliders position the selected slot:

| Control | Effect |
| --- | --- |
| **Device size** | Scales the device on the canvas |
| **Vertical offset** / **Horizontal offset** | Moves it up, down, left or right |
| **Rotation** | Tilts the device up to 45° either way (not available for the recording slot) |

**Apply to all screenshots** copies the placement to every media item in the
frame.

### Move mode

Switch **Move** on above the canvas (or double-click the canvas) to drag
frames and text directly. A rotate handle appears above the selected item,
pinch to resize, and click the title or subtitle to edit it in place. Switch
Move off when you are done so ordinary clicks stop moving things.

### Fine-tune screen rect

If a screenshot does not line up with the device's glass, expand
**Fine-tune screen rect** and adjust **X**, **Y**, **W** and **H**. **Reset
to Default** restores the calibrated values for that device.

## 3D frames

Switch **3D frame** on to replace the flat artwork with a rendered model you
can turn. Drag the model on the canvas to rotate it at any time — Move mode
is not required. 3D is available for iPhone 17 Pro Max, iPhone 18 Pro Max,
iPhone Duo and MacBook Pro 16″, and needs **Pro**.

### Placement

**Device size**, **Vertical offset**, **Horizontal offset**, **Tilt (X)**,
**Turn (Y)** and **Roll (Z)** position and pose the model. **Reset
orientation** returns it to a straight-on view.

### Lighting

**Reflections**, **Ambient** and **Key light** set the look of the model.
Lighting is shared by every 3D frame in the app, so all your renders match.
**Reset lighting** restores the defaults.

### iPhone Duo in 3D

- The **Fold** slider opens and closes the device; the quick-pose buttons
  jump to standing, fully folded, slightly folded and open poses in landscape
  or portrait, and rotate the device ±90°.
- Separate image slots feed the **Inner screen**, **Inner (portrait)**,
  **Inner screen (folded)**, **Outer screen** and **Outer (landscape)**.
  Recordings have the same set of slots.
- **Don't play videos while exporting** and **Use screenshots for the outer
  screen** control how recordings behave on the Duo's screens.
