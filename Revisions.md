### [Revision 54](https://code.google.com/p/flexfieldcontrollib/source/detail?r=54) (28-Jun-08) ###

  * Changed base of `FlexFieldControl` to `ContainerControl` so that its `AutoScaleMode` could be set to `AutoScaleMode.Dpi`.  Also set the `FixedWidth` and `FixedHeight` control styles to true.  These changes fix rendering problems when screen resolution is 120 dpi.
  * Using `Graphics.DrawString()` rather than `TextRenderer.DrawText()` in `SeparatorControl`.  `TextRenderer` does not use the correct baseline at 120 dpi.

### [Revision 52](https://code.google.com/p/flexfieldcontrollib/source/detail?r=52) (27-Apr-08) ###
  * Added propagation for `PreviewKeyDown`, `KeyDown`, and `KeyUp` events.

### [Revision 49](https://code.google.com/p/flexfieldcontrollib/source/detail?r=49) (19-Dec-07) ###
  * Added a Visual Studio 2008 project. The VS 2005 and VS 2008 projects have the same source code. Some minor changes were made to remove code analysis warnings.

### [Revision 42](https://code.google.com/p/flexfieldcontrollib/source/detail?r=42) (20-Nov-07) ###
  * Added `Dispose()` calls when recreating subcontrols on `FieldCount` change.

### [Revision 38](https://code.google.com/p/flexfieldcontrollib/source/detail?r=38) (23-Oct-07) ###
  * `ReadOnly` should now really be read-only.

### [Revision 36](https://code.google.com/p/flexfieldcontrollib/source/detail?r=36) (27-Sep-07) ###
  * Added proper event propagation for some mouse events.
  * Added `AnyBlank` property.
  * Removed superfluous code.
  * Addressed a potential resource leak when calculating text size.
  * Compliant with FxCop 1.35.

### [Revision 29](https://code.google.com/p/flexfieldcontrollib/source/detail?r=29) (23-Jul-07) ###
  * Fixed bug related to setting text of fields with leading zeros.

### [Revision 26](https://code.google.com/p/flexfieldcontrollib/source/detail?r=26) (23-Jul-07) ###
  * `GotFocus` and `LostFocus` events are consistently raised.
  * Added `AllowInternalTab` property was added to allow tabbing within the control. The default value is `false`.

### [Revision 22](https://code.google.com/p/flexfieldcontrollib/source/detail?r=22) (27-Jun-07) ###
  * Changes to `Text` property are persisted in design mode.
  * `KeyPress` event can be trapped by clients of the library.

### [Revision 20](https://code.google.com/p/flexfieldcontrollib/source/detail?r=20) (5-Jun-07) ###
  * Initial release.