# War Thunder — Manual QA Test Cases

**Overall status:** Not Run

| ID | Area | Test case | Expected result | Priority | Status |
|---|---|---|---|---|---|
| WT-001 | Launch | Start the game from the launcher/client | Game reaches login/main flow without crash | High | Not Run |
| WT-002 | Login | Complete login with valid account | Account loads successfully | High | Not Run |
| WT-003 | Main Menu | Navigate through primary menu sections | Each section opens without broken navigation | High | Not Run |
| WT-004 | Graphics | Change graphics preset | New preset applies without crash | Medium | Not Run |
| WT-005 | Graphics | Change texture quality | Setting applies and UI reflects selection | Medium | Not Run |
| WT-006 | Display | Switch Fullscreen to Windowed/Borderless | Display mode changes correctly | High | Not Run |
| WT-007 | Display | Change resolution and confirm | Resolution changes and remains usable | High | Not Run |
| WT-008 | Display | Cancel/revert a display change | Previous display setting is restored | Medium | Not Run |
| WT-009 | Audio | Change master volume | Output volume changes accordingly | Medium | Not Run |
| WT-010 | Audio | Mute and unmute audio | Audio state changes correctly | Medium | Not Run |
| WT-011 | Controls | Open control settings | Controls screen loads correctly | High | Not Run |
| WT-012 | Controls | Rebind a key to an unused key | Binding saves and functions in gameplay | High | Not Run |
| WT-013 | Controls | Attempt conflicting key binding | Conflict is handled or clearly communicated | Medium | Not Run |
| WT-014 | Persistence | Restart after changing graphics setting | Saved setting persists after restart | High | Not Run |
| WT-015 | Persistence | Restart after rebinding a control | Saved control persists after restart | High | Not Run |
| WT-016 | Alt+Tab | Alt+Tab from hangar and return | Game restores without freeze/crash/major UI issue | High | Not Run |
| WT-017 | Alt+Tab | Alt+Tab during Test Drive/battle and return | Session remains usable after returning | High | Not Run |
| WT-018 | Battle Flow | Enter Test Drive or a suitable battle session | Loading completes and gameplay starts | High | Not Run |
| WT-019 | HUD | Verify essential HUD elements after spawn | Required HUD elements render correctly | High | Not Run |
| WT-020 | Settings In Session | Open allowed settings during gameplay | Menu opens and closes without blocking gameplay state | Medium | Not Run |
| WT-021 | Return Flow | Exit Test Drive/battle using normal flow | Player returns to hangar/menu correctly | High | Not Run |
| WT-022 | Repeated Navigation | Rapidly open/close several menu panels | UI remains responsive and coherent | Medium | Not Run |
| WT-023 | Input | Rapidly switch keyboard/mouse focus between menu elements | No stuck input or unusable menu state occurs | Medium | Not Run |
| WT-024 | Settings | Apply several settings sequentially before leaving menu | Final selections are reflected correctly | Medium | Not Run |
| WT-025 | Exit | Exit the game through the normal menu | Client closes normally without hang/crash | High | Not Run |

## Execution rule
A test case changes from `Not Run` only after it is actually executed on the recorded build. Any failure must be backed by notes and, where useful, screenshot/video evidence.
