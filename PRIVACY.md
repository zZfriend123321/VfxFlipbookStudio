# Privacy Policy - Easy VFX (VFX Flipbook Studio)

Last updated: 2026-08-04

Easy VFX ("the app") is a desktop application for generating VFX flipbook
and texture-sheet images. Your privacy is simple to describe:

## What we collect
Nothing. The app does not collect, store, transmit, or share any personal
information. There are no user accounts, no analytics, no telemetry, no
advertising, and no tracking of any kind. Nothing is ever sent to the
developer.

## How your data is handled
All work happens locally on your own device using your GPU. Images you
import and sheets you export stay on your computer. The app only reads or
writes files that you explicitly choose through the standard open and save
dialogs, plus a small amount of its own working data described below.

Background removal, vectorising and every other effect run entirely on your
machine. The models used for background removal are installed with the app
and executed on your own hardware; no image is uploaded to use them.

## The one exception: the AI Edit node
The app includes a node called **AI Edit** which can send an image to an
outside image-editing service, so that a change described in words can be
made to it. This is the only part of the app that uses the internet, and it
works like this:

- It does nothing unless you supply your own account key for a service and
  press the send button. There is no key built into the app.
- When you press it, the image from that node and the text instruction you
  typed are sent to the service you selected, using your key, and billed to
  your account with that service.
- Nothing else is sent: no other part of your project, no file paths, no
  information about you or your computer.
- If you instead point the node at software running on your own machine
  (such as a local ComfyUI installation), nothing leaves your computer at
  all.

You can use the entire app without ever touching this node.

## Third parties
Aside from the AI Edit node described above, the app contacts no external
servers. The Microsoft Store version receives updates through the Microsoft
Store.

If you use the AI Edit node with a hosted service, whatever you send is
handled under that service's own privacy policy, not this one:

- fal.ai - https://fal.ai/privacy
- OpenAI - https://openai.com/policies/privacy-policy

Please read the policy of whichever service you choose before sending
anything you would not want that service to hold.

## Files the app keeps on your computer
The app stores a small amount of working data in your local application
data folder (`%LOCALAPPDATA%\EasyVFX`):

- Any account key you enter, so you do not have to type it again. Keys are
  held on your machine only, are never written into a saved project file,
  and are only ever sent to the service they belong to in order to sign in.
- Cut-outs, traced results and returned edits, so a result does not have to
  be recomputed every time.

You can delete that folder at any time. The app will simply recreate what
it needs.

## Children
The app collects no personal information from anyone, including children.

## Changes to this policy
This policy will be updated if the app's handling of data changes. The date
at the top reflects the most recent change.

## Contact
Questions about this policy can be raised at:
https://github.com/zZfriend123321/VfxFlipbookStudio/issues
