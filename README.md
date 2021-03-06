## Pathfinder plugin for the Quilvyn RPG character sheet generator

The quilvyn-pathfinder package bundles modules that extend Quilvyn to work with
the First Edition Pathfinder RPG, applying the rules of the
<a href="http://legacy.aonprd.com/">Pathfinder 1E Reference Document</a>.

### Requirements

quilvyn-pathfinder relies on the core and srd35 modules installed by the
quilvyn-core package.

### Installation

To use quilvyn-pathfinder, unbundle the release package into a plugins/
subdirectory within the Quilvyn installation directory, then add or uncomment
the 'plugins/Pathfinder.js' entry in the PLUGINS definition in quilvyn.html. An
entry for 'plugins/PathfinderPrestige.js' can also be added or uncommented to
use the prestige classes from the campaign setting rulebook. 

### Usage

Once the Pathfinder plugin is installed as described above, start Quilvyn and
choose Pathfinder from the Rules menu in the editor window.
