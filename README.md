# Sift - Photo Cleanup | Support

## How It Works

Sift helps you clean your camera roll by swiping through photos one at a time.

- **Swipe right** — Keep the photo
- **Swipe left** — Send it to the deletion bin
- **Pinch** — Zoom in for a closer look

Nothing is deleted immediately. All photos you swipe left go to a review bin where you can undo any mistakes before confirming deletion.

## Frequently Asked Questions

**Are my photos deleted immediately when I swipe left?**
No. Swiped photos go to a review bin first. You confirm the final deletion yourself, and iOS will ask you one more time before anything is actually removed.

**Can I undo a swipe?**
Yes. Tap the undo button during a session to bring back the last swiped photo. You can also remove any photo from the deletion bin before confirming.

**Does Sift upload my photos anywhere?**
No. Sift works 100% on your device. No photos leave your phone, no data is collected, and no network requests are made.

**What permissions does Sift need?**
Sift needs read and write access to your photo library. Read access to show your photos, write access to delete the ones you choose. That's it.

**Why do I see an Apple confirmation prompt when deleting?**
This is a built-in iOS safety feature. Apple requires all apps to show this prompt before permanently deleting photos. It's an extra layer of protection.

**Does Sift work with iCloud Photos?**
Yes. Sift uses Apple's PhotoKit framework, which works with your photo library as-is, including iCloud Photos.

**I accidentally deleted photos I wanted to keep.**
Deleted photos go to the "Recently Deleted" album in the Photos app. Apple keeps them there for 30 days before permanent removal.

## Privacy

- All data processing happens on-device
- No network requests are made
- No analytics, tracking, or telemetry
- No user accounts or sign-in
- Photo identifiers are stored locally using SwiftData for deduplication (so reviewed photos don't reappear immediately)
- No data is shared with any third party

## Technical Notes

- Built with SwiftUI and PhotoKit
- Minimum deployment target: iOS 18.0
- No third-party dependencies
- No in-app purchases in v1.0 (free)

## Contact
If you have questions, feedback, or need help, reach out at: ivan@jvcr.se
We read every message.

