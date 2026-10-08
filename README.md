# MotionSmith AI Animation Studio

AI-assisted 3D character animation authoring for Unreal Engine 5.8. MotionSmith supports motion generation, continuation, editing and retargeting in Unreal Editor.
add img

Official Fab listing: https://www.fab.com/listings/21c531e5-02b0-4d4a-960d-8cceab5dba34

## Version 1.0.0

- Platform: Windows 64-bit
- Unreal Engine: 5.8
- Required Unreal Engine plugin: IK Rig
- This repository's release ZIP contains the `KimodoMotion` plugin source and content. It does not contain the external AI runtime or Meta Llama model.

## Setup

1. Download `MotionSmith_1.0.0.zip` from this repository's Releases page after the release is published.
2. Extract the `KimodoMotion` folder to your Unreal project's `Plugins` directory. The source plugin may need to be compiled for the project.
3. Obtain `MotionSmithRuntime-1.0.0-Win64.zip` separately. Extract it manually into `%LOCALAPPDATA%\MSR\` and confirm `%LOCALAPPDATA%\MSR\runtime.json` exists.
4. Obtain Meta Llama 3 8B Instruct separately. In **Editor Preferences > Plugins > MotionSmith**, select its local directory in **Meta Llama Folder**, then click **Rescan**.

MotionSmith does not automatically download, install or extract the Runtime or Meta Llama model.

## Terms

Free availability does not by itself grant permission to modify or redistribute the plugin or bundled assets. No open-source license is declared in this repository.
