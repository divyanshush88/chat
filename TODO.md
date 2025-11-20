# TODO: Add Live Video Chat Option

## Steps to Complete
- [x] Update HTML: Add video elements (local and remote video tags) above the messages area in the chat view.
- [x] Update CSS: Add styles for video containers, controls (start call button, toggle mic/camera, end call).
- [ ] Update JS: Add WebRTC state variables (peer connection, local/remote streams).
- [ ] Implement WebRTC functions: getUserMedia, create peer connection, handle signaling (offer/answer/ICE via Firestore).
- [ ] Integrate with session: Extend session doc for signaling fields, listen for changes.
- [ ] Add UI controls: Button to start video call, toggle audio/video, end call.
- [ ] Handle permissions and errors: Request media access, show errors if denied.
- [ ] Test functionality: Ensure video call works between two users.

## Progress Tracking
- Start with HTML updates.
- Then CSS.
- Then JS logic step by step.
