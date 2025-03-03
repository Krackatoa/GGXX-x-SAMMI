# Guilty Gear XX Accent Core +R x SAMMI

A Bridge Extension for [SAMMI](https://sammi.solutions). Take interactions in game and turn them into stream gimmicks!

## Extension Function

This extension allows you to receive data from [TheLettuceClub's ACPR Live Content Mod](https://github.com/TheLettuceClub/GGXXACPR_Framework/releases) in the form of Extension Triggers inside SAMMI. A collection of example buttons have been provided with some experimental functionality to get you started.

![image](https://github.com/user-attachments/assets/1d0db460-9b5c-4290-98d0-3eeec3f4666e)

## Quick Start Guide

Step 1: Download [SAMMI](https://sammi.solutions).

Step 2: Follow the various [SAMMI Onboarding Tutorials](https://sammi.solutions/docs/getting-started/step-by-step).

Step 3: Install GGXXACPR x SAMMI as a [SAMMI Bridge](https://sammi.solutions/docs/bridge) Extension.

Step 4: Boot up Guilty Gear XX Accent Core +R while SAMMI and SAMMI Bridge are open to automatically connect.

Step 5: Make use of the various Extension Triggers generated by GGXX to drive stream gimmicks!

Step 6 (Optional): Copy the text found in the Example Deck text file to your clipboard, then import it to Sammi via the Paste Deck command. 

## Using the Mod

### Accessing Events via Extension Triggers

The following Extension Triggers are available for use. Add them to buttons via a button's Trigger menu. They all contain extremely relevant data within that can be accessed via the `Trigger Pull Data` command.

![image](https://github.com/user-attachments/assets/34395efd-6aea-4121-9f25-9a759efc57e3)
![image](https://github.com/user-attachments/assets/3bade3e1-5989-4002-a941-5af0860be8ef)

| Extension Trigger | Description |
| --- | --- |
| `ggxx_stateUpdate`| Occurs once a frame. Contains all sorts of cool gamestate data. |
| `ggxx_hitEvent` | Occurs on Hit or Block. Contains relevant data. |
| `ggxx_roundStartEvent` | Triggers on Round Start. |
| `ggxx_roundEndEvent` | Triggers on Round End. |

## More Information

Check out the documentation for [TheLettuceClub's Mod](https://github.com/TheLettuceClub/GGXXACPR_Framework/releases) for more information.
