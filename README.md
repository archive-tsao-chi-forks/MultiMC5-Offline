# Offline patches for MultiMC5
Credit to [@AfoninZ](https://github.com/AfoninZ "@AfoninZ") for his patches.

------------

**Builds with the patch applied are available on the releases page.**

------------

For building, download the patch file (don't clone this repo!) to the same directory as the MultiMC5 repo and apply it like this:

**First follow the steps prior to these ones:**
- **Windows:** [step 2 in the build guide](https://github.com/MultiMC/MultiMC5/blob/develop/BUILD.md#compile-from-command-line-on-windows "step 2 in the build guide") 
- **Linux:** [cloning the MultiMC5 repo](https://github.com/MultiMC/MultiMC5/blob/develop/BUILD.md#building-from-command-line "cloning the MultiMC5 repo")
- **MacOS:** [cloning the MultiMC5 repo]( https://github.com/MultiMC/MultiMC5/blob/develop/BUILD.md#os-x "cloning the MultiMC5 repo")

**Then:**
- Run the command: `git am 0001-offline-patch.patch` and continue with the build guide normally.

