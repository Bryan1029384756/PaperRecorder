<div align=center>
    <img src="./paperrecorder.png">
    <br /><br />
    <p><b><font size="+3">PaperRecorder</font></b></p>
</div>


## Overview
PaperRecorder for 1.20.1 is a Fork of paper allowing players to record players and replay it using the replay mod. <br>
Original Mod for ServerSideReplayRecorder https://github.com/thecolonel63/server-side-replay-recorder

## Commands
**/replay players (add|remove|list)** - Add/list/remove players to/from the blacklist/whitelist <br>
**/replay status** - Show the active recording list as well as if recording is enabled <br>
**/replay status (enable|disable)** - Toggle recording across entire mod <br>
**/replay region <regionName> (start|stop|status)** - Enable recording of a pre-defined large area independent of players <br>
**/replay file (player|region)** - Delete / Upload replay files without manually accessing the replay folder <br>
**/replay marker (player|region)** - Add a marker to the specified replay file <br>

## Config
Config is in **/config/ServerSideReplayRecorder.yml**

# Compatibility
This Paper Fork is compatible with [Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat). 
To use please download the [Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat) plugin for Bukkit and install in the plugins folder 
and PaperRecorder will take care of the rest. To hear the voices in the [Replay Mod](https://modrinth.com/mod/replaymod) please download
[Replay Voice Chat](https://modrinth.com/mod/replay-voice-chat)

## License
The PATCHES-LICENSE file describes the license for api & server patches,
found in `./patches` and its subdirectories except when noted otherwise.

The fork is based off of PaperMC's fork example found [here](https://github.com/PaperMC/paperweight-examples).
As such, it contains modifications to it in this project, please see the repository for license information
of modified files.
