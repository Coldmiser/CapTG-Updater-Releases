# Blocked Windows updates

CapTG Updater does not install the updates listed here, on any machine, and hides them in Windows Update.
Remove a line to release the update: within about an hour each machine unhides and installs it.

Only lines that start with a KB number count (a leading `-`, `*` or `|` is fine). Anything after the number
is a note. Headings, other text and struck-out numbers are ignored. Don't delete this file to unblock
everything: machines keep the last copy they read. Remove the KB lines instead.

This file is public: KB numbers and the reason only, never client or computer names.

To block an update on only some machines, set `WindowsUpdateExclusions` (REG_SZ, `KB1;KB2`) under
`HKLM\SOFTWARE\CapTG\UpdateService` on those machines instead.

## Blocked

(none)
KB1111111
KB1111112
