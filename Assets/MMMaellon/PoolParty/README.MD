# POOL PARTY!

## Overview

This prefab makes it easy to have 100s of spawnable objects in your world.
It creates a pool (hence the name) of pickup objects that can take any appearance which you decide at spawn time. Instead of using Object Sync, we use our own syncing script which saves A LOT of data when it comes to kinematic objects by only syncing the moment objects are picked up and when they are dropped. Non-Kinematic objects are WIP.
I'm also throwing in tools to make it easy to align and place the pickups on flat surfaces.

## Setup

1) Drag the PoolParty prefab into your scene.
2) Drag in a bunch of Spawners as a child of the PoolParty Object
3) Drag a template prefab into the "Template" field of each Spawner. This decides what kind of object it can spawn. Drag multiple objects into that field if you want it to randomly spawn one of the prefabs. Synced scripts that are part of the template won't work.
4) Move the SpawnPoint on the spawner to where you want objects to appear. You can reparent it if you want.
5) Move the SpawnButton to where you want the spawn button to be. You can reparent it if you want or change the appearance and collider and stuff.
