1. Kernel Commit
The kernel API originates outside the `/drivers` directory (cross-subsystem), and the commit
introduces a new API, or
modifies an existing API, or
defines new usage conventions

2. Driver Commit
The driver commit is a passive migration, including:
purely mechanical adaptations (e.g., API replacement, parameter updates), or
some proactive changes within the driver (e.g., refactoring using new public helper)

