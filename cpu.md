# CPU

This section contains concepts that depend only on the CPU, but that cannot be tested on userland because they'd require ring 0.

Examples:

- real mode concepts. Userland cannot switch to real mode.
- segment registers.

This section does not include concepts that depend on hardware other than the CPU itself, e.g. BIOS.

Concepts that *can* be tested from userland will be tested at: <https://github.com/cirosantilli/assembly-cheat>
