---
-api-id: M:Windows.UI.Notifications.BadgeUpdater.StartPeriodicUpdate(Windows.Foundation.Uri,Windows.Foundation.DateTime,Windows.UI.Notifications.PeriodicUpdateRecurrence)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public void StartPeriodicUpdate(Windows.Foundation.Uri badgeContent, Windows.Foundation.DateTime startTime, Windows.UI.Notifications.PeriodicUpdateRecurrence requestedInterval)
-->

# Windows.UI.Notifications.BadgeUpdater.StartPeriodicUpdate

## -description
Begins a series of timed updates for the badge from a web resource that the updater is bound to. Updates begin at a specified time. Note that only web resources (http/https) are allowed in a periodic update.
<!-- @WRITER erictill 1/13/2012 : Nathan wants the following added, but I have no idea what he's talking about. Wrote him. : Only one periodic update can occur for each tile (per type). -->

## -parameters
### -param badgeContent
The Uniform Resource Identifier (URI) from which the XML content of the badge update will be retrieved.

### -param startTime
The time at which the Uniform Resource Identifier (URI) should first be polled for new badge content.

### -param requestedInterval
The frequency with which the Uniform Resource Identifier (URI) is polled for new badge content, following the initial update at *startTime*.

## -remarks

## -examples

## -see-also
[StartPeriodicUpdate(Uri, PeriodicUpdateRecurrence)](badgeupdater_startperiodicupdate_1967457783.md), [App tiles and badges sample](http://go.microsoft.com/fwlink/p/?linkid=231469), [Guidelines and checklist for tiles and badges](http://msdn.microsoft.com/library/e825f754-97dd-41c2-aff4-4dfb60eda677), [How to clear a badge](http://msdn.microsoft.com/library/6b2d57e0-51aa-4bce-894e-fa3fd32d77bb), [How to send a glyph or numeric badge in a local notification](http://msdn.microsoft.com/library/6b2d57e0-51aa-4bce-894e-fa3fd32d77bb), [How to set up periodic notifications for badges](http://msdn.microsoft.com/library/96c67773-2e5b-4278-b16d-2f813b16580c), [How to update a badge through push notifications](http://msdn.microsoft.com/library/bb962e30-6c95-4186-8a0e-6683140e17c7), [Badge XML schema](XREF:TODO:badge.Schema_Root), [Badge overview](http://msdn.microsoft.com/library/a64c58bb-d9c9-4c09-a685-4df94fa7dfdd)