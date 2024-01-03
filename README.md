# SerializableDictionaryPlugin

## What is this?

A UABEA plugin for importing and exporting the [serializable dictionaries](https://github.com/neuecc/SerializableDictionary)
used by Unity games such as Dragalia Lost.

Code has been adapted from the above linked repository by neucc / Yoshifumi Kawai under the terms of the MIT license.

## How do I use it?

Get the [latest release](https://github.com/sapiensanatis/SerializableDictionaryPlugin/releases/latest) and the latest
nightly build of [UABEA](https://github.com/nesrak1/UABEA). Put the DLL files from the release into UABEA's Plugins
folder, and then select any MonoBehaviour asset and the options to import/export as a serializable dictionary should
be present.

Currently no validation is performed on the MonoBehaviours to check if they are serializable dictionaries, so the plugin
will crash if used incorrectly.

